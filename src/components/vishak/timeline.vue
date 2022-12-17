<template>
    <div id="timeline">
      <div class="cf mp32">
        <HeadingText name="Timeline"/>
      </div>
<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2 class="">12th December 2022</h2><br/>
      <p>Last date for registrations</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>6th December 2022</h2>
      <p>Workshop</p>
    </div>
  </div>
   <div class="container left">
    <div class="content">
      <h2>6th to 14th December 2022</h2><br/>
      <p>idea submission </p>
    </div>
  </div>
   <div class="container right">
    <div class="content">
      <h2>17th December 2022</h2><br/>
      <p>Evaluation of ideas</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>18th December 2022</h2><br/>
      <p>Publishing of round 1 results</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>22nd December 2022</h2><br/>
      <p>Round 2 filtering</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>29th December 2022</h2><br/>
      <p>Final round</p>
    </div>
  </div>
</div>
    </div>
</template>

<script>
import  HeadingText from '../HeadingText.vue';

export default {
    name: "TimelineSec",
    components: { HeadingText }
}
</script>

<style scoped>
* {
  box-sizing: border-box;
}

/* Set a background color */
.timeline {
  background-color:var(--blueNeutral);
  border-radius: 32px;
  /* font-family: Helvetica, sans-serif; */
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  /*Changed this for negative spacing! */
  max-width: 640px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: white;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 24px;
  right: -14px;
  background-color: white;
  border: 4px solid #FF9F55;
  top: 14px; 
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50%;
}

/* Add arrows to the left container (pointing right) */
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent white;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -16px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
/* Place the timelime to the left */
  .timeline::after {
    left: 31px;
  }

/* Full-width containers */
  .container {
    width: 88%;
    padding-left: 70px;
    padding-right: 25px;
  }

/* Make sure that all arrows are pointing leftwards */
  .container::before {
    left: 60px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
  }

/* Make sure all circles are at the same spot */
  .left::after, .right::after {
    left: 15px;
  }

/* Make all right containers behave like the left ones */
  .right {
    left: 0%;
  }
}
</style>
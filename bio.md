---
layout: default
---
[Projects](./projects.html) | [Brief Bio](./bio.html) | [Resume](./resume.html) | [Past Life](http://pravegaracingvit.herokuapp.com/) | [Gimmicks](https://www.behance.net/kvarada) | [Contact](./contacts.html)

# Brief Bio

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #FFFFFF;
  font-family: Helvetica, sans-serif;
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: black;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 1px 1px;
  position: relative;
  background-color: black;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid black;
  top: 15px;
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
  top: 2px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid black;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent black;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 2px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid black;
  border-width: 10px 10px 10px 0;
  border-color: transparent black transparent transparent;
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
  width: 100%;
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
</head>
<body>

<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2> Sep. 2019</h2>
      <p>Joined the perception team at Rivian, coding algorithms for adventureous electric vehickles</p>
    </div>
  </div>

  <div class="container right">
    <div class="content">
      <h2>May 2019</h2>
      <p>Walked at the Master's graduation cerermony at Penn State; this was an unforseen dream back when I was in college in India. Huge thanks to the ARPA-E and the ME deaprtment at Penn State for funding my Master's education. </p>
    </div>
  </div>

  <div class="container left">
    <div class="content">
      <h2>Nov. 2018</h2>
      <p>Joined the sensor fusion team at NIO USA, to research and code algorithms for Level-4 self-driving electric cars; there used to be a time when I thought I would never get here because I did not have a CS degree. Exciting stuff! </p>
    </div>
  </div>

  <div class="container right">
    <div class="content">
      <h2>Aug. 2017</h2>
      <p>Will be spending the Fall at Volvo Group at Hagerstown, Maryland in their Advanced Technology and Research Group, developing energy optimization algorithms for their trucks </p>
    </div>
  </div>

  <div class="container left">
    <div class="content">
      <h2>Aug. 2016</h2>
      <p>Joined The Pennsylvania State University's Mechanical Engineering department to pursue a Master's in Mechanical Engineering, specializing in robotics and state estimation; I will be purusing Master's research in the Intelligent Vehicles and Systems Group. </p>
    </div>
  </div>

  f<div class="container right">
    <div class="content">
      <h2>May 2015</h2>
      <p>Our work on the patient transfer device has been applied for an Indian patent.</p>
    </div>
  </div>

  <div class="container left">
    <div class="content">
      <h2>July 2014</h2>
      <p>Joined IISc as a junior reseach fellow at Indian Institute of Science; I chose to gain some research experiene over the existing offers from the industry. </p>
    </div>
  </div>

  <div class="container right">
    <div class="content">
      <h2>May 2014</h2>
      <p> Graduated from VIT University with a Bachelor's degree </p>
    </div>
  </div>

</div>

</body>
</html>

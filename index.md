---
title: false
---
<figure class="figure">
  <center>
  <img src="{{ site.baseurl }}/assets/cover.png" alt="advertisement for the workshop" class="vid-fluid rounded center">
  </center>
</figure>

# Yá’át’ééh 👋 (Welcome!)

> We are updating our dates to July 19-21, 2022 to accomodate more educators and students!

<div class="message">
  Are you curious about how Artificial Intelligence (AI) can be used to improve your everyday life? Do you ever wonder how your cell phone understands and responds to a question that you ask it? Have you heard the term Artificial Intelligence (AI), or Machine Learning (ML), but aren’t sure about possible uses of ML or AI, or how you might prepare for a career in this field?
</div>

This 3-day, hands-on/virtual workshop for high school teachers and students will give you experience in developing a real-world, applied application of artificial intelligence (AI) at the edge through hands-on examples of Tiny Machine Learning (TinyML). TinyML is a cutting-edge field that brings the transformative power of machine learning (ML) to small low-power computing devices. This course will expose participants to the applications, algorithms, hardware, and software of TinyML.

> No prior experience is expected!

Participants will be given an [Arduino Tiny Machine Learning Kit](https://store.arduino.cc/usa/tiny-machine-learning-kit) which they will use for hands-on exploration of the opportunities and challenges of TinyML by deploying and testing their own TinyML models. Following the completion of the course, students will be well positioned to excel in the [HarvardX Professional Certificate Program in Tiny Machine Learning](https://www.edx.org/professional-certificate/harvardx-tiny-machine-learning), a free online MOOC that dives deeper into the world of Tiny Machine Learning with more hands-on experiences.

This program is a collaboration between [Navajo Technical University](http://www.navajotech.edu/), the [Harvard John A. Paulson School of Engineering and Applied Sciences](https://www.seas.harvard.edu/), and [Barnard College, Columbia University](https://barnard.edu/), and will be run virtually from July 19 to July 21, 2022.  The workshop is targeted for secondary school educators and students. We will be accepting up to 50 attendees and preference will be given to students and educators affiliated with schools that serve the Navajo Nation.

To apply as a student please fill out this form by July 1, 2022: [https://bit.ly/EASI-22-Student](https://bit.ly/EASI-22-Student)!

To apply as an educator please fill out this form by July 1, 2022: [https://bit.ly/EASI-22-Teacher](https://bit.ly/EASI-22-Teacher)!
<br>Educators selected for the workshop will be compensated for their time.

We look forward to exploring TinyML with you this summer!

## Preliminary Schedule
The workshop will be held on [Zoom](https://harvard.zoom.us/j/96801670645?pwd=ZExnSElaQ0swcFFhTWVocU5RbS9NQT09).
<div id = "LOCAL_TIME"></div><br/>

{% include schedule_table table_data = site.data.schedule %}

### Questions?
***
Contact [easi-staff@googlegroups.com](mailto:easi-staff@googlegroups.com) with any questions regarding this workshop.

### Supporters
***
We would like to thank the [IEEE CS](https://www.computer.org/) for their generous support of this program through the [IEEE CS Diversity & Inclusion Fund](https://www.computer.org/press-room/2022-news/ieee-cs-diversity-inclusion-programs).

<script>
  // top time
  var start = new Date('7/21/2022 12:00:00 PM MDT');
  var end = new Date('7/21/2022 3:00:00 PM MDT');
  var localTime = start.toLocaleTimeString([], {timeStyle: 'short'}) + " to " + end.toLocaleTimeString([], {timeStyle: 'short'});
  var startString = "The workshop will run each day from <b>12:00 PM to 3:00 PM MDT (New Mexico Time) which is "
  var endString = " in your local timezone</b> (according to your computer system time). Times below adjusted to that time zone. Exact timing and topics subject to change."
  document.getElementById('LOCAL_TIME').innerHTML = startString + localTime + endString;
  
  // all times
  var timeElements = document.getElementsByClassName("GMT_TIME");
  for (var i = 0; i < timeElements.length; i++) {
    dateStr = '6/22/2022 ' + timeElements[i].innerHTML + ' MDT'
    var gmt_time = new Date(dateStr);
    timeElements[i].innerHTML = gmt_time.toLocaleTimeString([], {timeStyle: 'short'})
  }
</script>
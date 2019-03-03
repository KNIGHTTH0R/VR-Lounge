# VR Lounge
## A VR Video Player in your browser!

![VR-Lounge thumbnail](https://skyreep.github.io/VR-Lounge/thumbnail.png "VR Lounge")

### Live Demo
[Live Demo](github.com/skyreep/VR-Lounge)

### Description
A web application built for cross-platform 360 videosphere VR experiences. This project was built using HTML, CSS, JS, Bootstrap, and A-Frame. This project was completed as part of an 8 hour rapid development cycle for Coastal Carolina University's CSCI 495 IS Capstone course, Spring 2019.

### Dependencies
<ul>
  <li>
    Boostrap
  </li>
  <li>
    A-Frame
  </li>
</ul>
  
### Usage
A-Frame can be a finnicky beast! If you're interested in working with this project I reccomend you visit its Glitch page. Glitch makes working with A-Frame much easier. You can also remix this project and create your own repo with the changes directly from Glitch, or you can download the full package directly to your system. Since the content was uploaded and hosted by Glitch it can be opened locally from your file explorer. When working with your own project however, it's important to note that any VR media you wish to show must be uploaded via a service that supports CORS headers (Amazon S3 Buckets and Glitch for example).
You can find and remix this project's Glitch project here: 
[Glitch Repo](glitch.com/edit/#!/skyreep-vr-lounge)

### Future Work
There is a known bug that causes the "click to start the video" alert to stay on the screen when playing unless refreshed on Desktop. 
I would also like to add keyboard control to the videos for desktop. During development I had it working in A-Frame version 0.7.1, but upon upgrading to 0.9.0 for other important features, it broke the keyboard control, and I have since removed it as a result (clicking and dragging is still functional).

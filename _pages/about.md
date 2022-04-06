---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html

style: javascript-comic-001.css
googlewebfonts: Gloria+Hallelujah
---

{% include open-embed.html %}

<head>
<script type="text/javascript" src="https://code.jquery.com/jquery-3.3.1.min.js"></script>

<style>
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: #cccccc;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
  font-family: "Times New Roman", Times, serif;
}

#myBtn:hover {
  background-color: #555;
}

table
{
    table-layout: fixed;
    width: 100px;
}

/* td
{
    border: 1px solid green;
    overflow: hidden;
} */
</style>

</head>

<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>

<script>
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    document.getElementById("myBtn").style.display = "block";
  } else {
    document.getElementById("myBtn").style.display = "none";
  }
}

function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

<span style="font-size:1.1em;">"What I Cannot Create, I Do Not Understand."</span>
<br/>

<!-- <span style="font-size:1.1em;">"Know how to solve every problem that has been solved."</span>
<br/> -->

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
<span style="font-size:0.9em;">- Richard Feynman</span>
<br/>

<!-- &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
<span style="font-size:0.9em;">(1988, Caltech, his last blackboard notes)</span> -->

# About Me

Hi! I am a graduate student at the University of Washington, Seattle, majoring in Electrical and Computer Engineering. My primary interest lies in low-level and high-level software, and I have five years of professional work experience in firmware development.

Currently, I'm seeking full-time firmware/software engineering opportunities in the US. If you think I'm a good fit, kindly contact me via email (<code class="highlighter-rouge">sjena94 at uw dot edu </code>).

How to pronounce my name?
<audio controls>

  <source src="audio/robot.mp3" type="audio/mpeg">
  <p>Your browser doesn't support HTML5 audio. Here is
     a <a href="audio/robot.mp3">link to the audio</a> instead.</p>
</audio>

<!-- \\[
\begin{split}
r &= \begin{pmatrix} R & 0 \\\\ 0 & 1 \\\\ \end{pmatrix} \\\\\\\\
t &= \begin{pmatrix} I & T \\\\ 0 & 1 \\\\ \end{pmatrix}
\end{split}
\\]

<br/> -->

<br/>
<strong><a href="https://drive.google.com/file/d/1wYLskop5OqqyRbLXd-7XvoaRsyYzhfM6/view?usp=sharing" target="_blank">Curriculum Vitae</a> (last updated: February 2022)</strong>

<!-- <br/>

<!--

SW Projects

DSA
1. Snakes Game: Array, Game Loop
2. Sudoku: Backtracking, 2D Array
3. Travel Planner: Dijkstra, Graph
4. Splitwise Cashflow Minimization: Heap, Graphs
5. Whatsapp Chatlist: LRU Cache, Hashmap
6. Text Editor: Stack
7. FileZipper:Binary Trees, Huffman Encoding
8. Photoeditor: Multi-Dimentional Arrays
9. Contact List: Trees, Tries
10. Chatbot: Trees, APIs, JSON
11. CB Mario: Greedy Programming, Phasors
12. Jumpy Frog: Dynamic Programming, Phasors


Backend
1. QMoney
2. QEats
3. T-Mobile


Course Projects
1. Gymbo
2. HuskyMap


Firmware Projects


∗ Led the software and firmware side of the development board, which is currently being used in the CS684 course at IIT
Bombay and was used in eY Robotics Competition by 364 participants.
∗ Developed an OTA application for ESP32 to start a Wireless Access Point, host a file server and allow OTA firmware
update of the onboard microcontrollers, i.e. ATmega2560 and ESP32.
∗ Modified the bootloader and partition table of ESP32 to enable switching between OTA application and user
application in the flash, based on the status of a GPIO pin.

 -->
<br/>

<!-- ____________________________________________________________ -->
<!-- ____________________________________________________________ -->

# Education

<table style="width:100%">

<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/uw.png" alt="UW-Logo"> <br/> <b>University of Washington  <br/> Seattle</b> <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>Sep. 21 - Mar. 23</b>
		<br/> MS ECE
    	<br/> Department of Electrical and Computer Engineering 
    	<br/> <b>GPA: 4.0/4.0</b>
    	<!-- <br/> <a href="https://drive.google.com/file/d/17GNP998P4cYmE27QAbyp5UAo8KkBX3Uw/view?usp=sharing"  target="_blank">Degree</a>
    	&emsp;<a href="https://drive.google.com/file/d/1pDvEFoeXen2UTtuZxRjV01oSdienWoaf/view?usp=sharing"  target="_blank">Transcript</a> -->
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/bit-mesra.jpg" alt="BIT-Logo"> <br/> <b>Birla Institute of Technology <br/> Mesra</b> <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>Aug. 13 - Jun. 17</b>
		<br/> BE ECE 
    	<br/> Department of Electronics and Communication 
    	<br/> <b>CGPA: 8.07/10.00</b> <br/> (First Class with Distinction) 
    	<br/> <a href="https://drive.google.com/file/d/17GNP998P4cYmE27QAbyp5UAo8KkBX3Uw/view?usp=sharing"  target="_blank">Degree</a>
    	&emsp;<a href="https://drive.google.com/file/d/1pDvEFoeXen2UTtuZxRjV01oSdienWoaf/view?usp=sharing"  target="_blank">Transcript</a>
    </td>
  </tr>

</table>

<br/>


<!-- ____________________________________________________________ -->
<!-- ____________________________________________________________ -->


# Experience

<table style="width:100%">

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/tesla.png" alt="tesla-Logo"> <br/>  Palo Alto, CA <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>Jun. 22 - Dec. 22</b> 
    	<br/> Autopilot Firmware Intern
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="70px" height="70px" src="{{site.baseurl}}/_pages/logos/tmobile.png" alt="tmobile-Logo"> <br/> <b>T-Mobile</b> <br/>Seattle, WA <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>Jan. 22 - Jun. 22</b> 
    	<br/> Capstone Project Member, 
    	<br/> UW ENGINE
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/iit-bombay.png" alt="IITB-Logo"> <br/> <b>IIT Bombay</b> <br/>Mumbai, India <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>Jan. 19 - Present</b> 
    	<br/> Senior Project Technical Assistant, 
    	<br/> Embedded Real-Time Systems Lab,
    	<br/> Computer Science and Engineering Department
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/csir-nio.png" alt="NIO-Logo"> <br/> <b>CSIR <br/> National Institute of Oceanography</b> <br/>Panajim, India <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>Jun. 18 - Jan. 19</b> 
    	<br/> Project Assistant II, 
    	<br/> Automonous Weather Station Lab,
    	<br/> Marine Instrumentation and Computer Department 
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/numadic.png" alt="Numadic-Logo"> <br/> <b>Numadic IoT</b> <br/>Mumbai, India <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b> Feb. 17 - May 18 </b>
    	<br/> Feb. 17 - Jun. 17, Firmware Intern 
    	<br/> Jul. 17 - May 18, Junior Firmware Developer 
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/iit-kanpur.jpg" alt="IITK-Logo"> <br/> <b>IIT Kanpur</b> <br/>Kanpur, India <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>May 16 - Jul. 16</b> 
    	<br/> Undergraduate Researcher, 
    	<br/> Summer Undergraduate Research and Excellence Program,
    	<br/> Mechanical Engineering Department 
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/ongc.jpg" alt="ONGC-Logo"> <br/> <b>Oil and Natural Gas Corporation</b> <br/>Vadodara, India <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>May 15 - Jun. 15</b> 
    	<br/> Summer Intern, 
    	<br/> Regional Electronics Lab, Vadodara
    	<br/> 
    </td>
  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/logos/wosca.png" alt="WOSCA-Logo"> <br/> <b>Women's Organisation for <br/> Socio-Cultural Awareness</b> <br/>Keonjhar, India <br/></td>
    <td style="width: 30%;" align="center"> 
    	<b>May 14 - Jul. 14</b>, 
    	<br/><b>Dec 14 - Jan. 15</b>, 
    	<br/><b>Dec 15 - Jan. 16</b>, 
    	<br/> Volunteer Teacher <br/>
    </td>
  </tr>

</table>

<br/>


<!-- ____________________________________________________________ -->
<!-- ____________________________________________________________ -->


# Projects

## Firmware Projects

<table style="width:100%">

<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/eyfi.png" alt="UW-Logo"> <br/> <br/> 
	<b> eYFi-Mega Development Board </b> <br/> 
	Patent Pending <br/>(<a style="font-size:0.8em;" href="https://drive.google.com/file/d/1Zu8DRXQV6ZWR5S5kxHddBm599YaU18YV/view?usp=sharing"  target="_blank">IN 202121023159</a>)<br/>
	IIT Bombay <br/>
	<a href="https://products.e-yantra.org/eyfi-mega/"  target="_blank">Product Page</a>
	</td>
    <td align="left"> 
		<center><i>C, HTTP Server, Bootloader, OTA Update, ESP32, AVR</i></center>
		<ul>
			<li>
			Led the software and firmware side of the development board, which is currently being used in the CS684 course at IIT Bombay and was used in eY Robotics Competition by 364 participants.
			</li>
			<li>
			Developed an OTA application for ESP32 to start a Wireless Access Point, host a file server and allow OTA firmware update of the onboard microcontrollers, i.e. ATmega2560 and ESP32.
			</li>
			<li>
			Modified the bootloader and partition table of ESP32 to enable switching between OTA application and user application in the flash, based on the status of a GPIO pin.
			</li>
		</ul>  
    </td>
  </tr>

  <tr>
  	<td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/nubot.png" alt="UW-Logo"> <br/> <br/> 
	<b> Nubot GPS Tracker </b> <br/> 
	Numadic <br/>
	<!-- <a href="https://products.e-yantra.org/eyfi-mega/"  target="_blank">Product Page</a> -->
	</td>
    <td align="left"> 
		<center><i>C, Flash Memory, OTA Update, ESP32</i></center>
		<ul>
			<li>
			Extended life of W25N01GV 1Gb NAND Flash Memory used in Nubot by 29% by developing a custom logical data structure to push data in O(logN) and retrieve data from it in O(logN) (N = Total number of pages in the flash).
			</li>
			<li>
			Wrote an OTA server to serve firmware and a client for ESP32 to fetch firmware using just sockets in C.
			</li>
			<li>
			Developed a GATT Client Android App to debug Nubot v2 wirelessly over BLE.
			</li>
		</ul>  
    </td>
  </tr>

  <tr>
  	<td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/nubit.png" alt="UW-Logo"> <br/> 
	<b> Nubit Temperature Logger </b> <br/> 
	Numadic <br/>
	<!-- <a href="https://products.e-yantra.org/eyfi-mega/"  target="_blank">Product Page</a> -->
	</td>
    <td align="left"> 
		<center><i>C, Javascript, HTTP Server, AJAX, ESP32, FreeRTOS, WLAN</i></center>
		<ul>
			<li>
			Wrote firmware for this device which enabled it to host an HTTP server and serve a dynamic HTML page to plot temperature logged in real-time and provide an interface for the user to download logged data over Wi-Fi.
			</li>
		</ul>  
    </td>
  </tr>

</table>



## Software Projects (Data Structures and Algorithms Focused)

<table style="width:100%">


<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/huyskymaps.png" alt="UW-Logo"> <br/> 
	<b> HuskyMaps </b> <br/> 
	University of Washington <br/>
	Course Project <br/>
	</td>
    <td align="left">
    <center><i>Java, Data Structures and Algorithms</i></center>
    	<ul>
    		<li> 
			Implemented several algorithms in Java to add functionalities to HuskyMaps like autocomplete using Ternary Search Trees, changing the priority of an item using Optimized Min Heap and seam-carving of an image using Adjacency Lists, Topo Sort, Dijkstra’s and Dynamic Programming.
			</li>
    	</ul>
    </td>
	</tr>


<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/snake.png" alt="UW-Logo"> <br/>
	<b> Snakes Game </b> <br/>
	Personal Project <br/>
	<a href="https://souravjena.github.io/snake_game/"  target="_blank">Play!</a>
	</td>
    <td align="left">
		<center><i>Javascript, OOP, Arrays, Game-Loop</i></center>
		<ul>
			<li>Built this classic game to learn OOP and Arrays data-structure.</li>
			<li>Learned about Game-Loops also.</li>
		</ul>
    </td>
  </tr>

</table>


## Software Projects

<table style="width:100%">

<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/tmobile.png" alt="UW-Logo"> <br/> 
	<b> 5G Home Internet QoS Prediction App </b> <br/> 
	T-Mobile <br/>
	Ongoing Project <br/>
	</td>
    <td align="left">
    <center><i>XCAL/XCAP, Java, Python, Kotlin, scikit-learn, Spring, Android Studio
</i></center>
    	<ul>
    		<li> 
			Collecting outdoor/indoor low and mid-band, 4G and 5G data using XCAL/XCAP.
			</li>
			<li> 
			 Training an ML model to predict the quality of service for 5G mid-band from low or 4G mid-band signals.
			</li>
			<li> 
			 Developing an Android app and the backend of the app for potential customers to predict the expected internet speed of T-Mobile 5G Home Internet at their home before they subscribe for the service.
			</li>
    	</ul>
    </td>
	</tr>



<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/eyantra.png" alt="UW-Logo"> <br/> 
	<b> eY IoT Framework </b> <br/> 
	IIT Bombay <br/>
	<a href="https://e-yantra-r3.github.io/ey-iot-framework/"  target="_blank">Documentation</a> <br/>
	</td>
    <td align="left">
    <center><i>Python, Pytorch, OpenCV, Deep Learning, Computer Vision</i></center>
    	<ul>
    		<li> Developed an embedded software framework for ESP32 with two interns to write event-driven code for IoT applications.
			</li>
    	</ul>
    </td>
	</tr>
	<tr>
	<td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/eysim.png" alt="UW-Logo"> <br/> 
	<b> eY IoT Circuit Simulator </b> <br/> 
	IIT Bombay <br/>
	<a href="https://www.youtube.com/embed/iXrWR6PEd-E"  target="_blank">Video</a> <br/>
	</td>
    <td align="left">
    <center><i>C++, Qt 5, Python, MQTT</i></center>
    	<ul>
    		<li> Forked and modified SimulIDE to add eYFi-Mega in it for circuit simulation.
			</li> 
			<li>
			Integrated it with a self-developed python middleware to allow MQTT Pub-Sub through the simulator.
			</li>
    	</ul>
    </td>
  </tr>
	<tr>
	<td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/arduino.png" alt="UW-Logo"> <br/> 
	<b> Arduino <br/> (For eYFi-Mega) </b> <br/> 
	IIT Bombay <br/>
	<a href="https://www.youtube.com/embed/XiOXn4fECPA"  target="_blank">Video</a> <br/>
	</td>
    <td align="left">
    <center><i>Golang, curl</i></center>
    	<ul>
    		<li> Wrote a Golang CLI program to allow wireless uploading of Arduino sketches on both the controllers of
eYFi-Mega (ESP32 and ATMega2560) via Arduino IDE.
			</li> 
    	</ul>
    </td>
  </tr>
	<tr>
	<td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/hlmsoft.png" alt="UW-Logo"> <br/> 
	<b> HLMSoft </b> <br/>
	IIT Kanpur <br/>
	<a href="https://drive.google.com/file/d/10GQhUYejyLO33X-e44WHkGzVVf4vWjAe/view"  target="_blank">Report</a> <br/>
	</td>
    <td align="left">
    <center><i>C++, Qt</i></center>
    	<ul>
    		<li> Developed HLMSoft in C++ using Qt Framework to link additive and subtractive manufacturing commands into
a single G-Code file enabling the controller of the CNC machine to control milling and welding unit for hybrid layered
manufacturing.
			</li> 
    	</ul>
    </td>
  </tr>
</table>

## Robotics Project

<table style="width:100%">

<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/vargibots.png" alt="UW-Logo"> <br/> <br/>
	<b> Vargi-Bots </b> <br/> 
	IIT Bombay <br/>
	Accepted in IEEE EDUCON 2022 <br/>
	<a href="https://github.com/e-yantra-r3/vb_simulation_pkgs"  target="_blank">Github</a> <br/>
	<a href="https://www.youtube.com/embed/upjR6p2-RZU?start=133"  target="_blank">Video</a> <br/>
	</td>
    <td align="left">
    <center><i>Python, ROS, Gazebo, OpenCV, MQTT, HTTP</i></center>
    	<ul>
    		<li>Partnered with two team members to build a fully automated <br/> 
			shipping warehouse with two UR5 Robotic Arms in Gazebo Simulator.
			</li>
    		<li>
			It can receive online orders via MQTT, log the data in a Google Sheet, <br/> 
			send email notifications, and display relevant information on a hosted dashboard in real-time.
			</li>
			<li>
			It was used to teach 1880 students ROS, Python, OpenCV, <br/> 
			Robotic Manipulation and IoT.
			</li>
    	</ul>
    </td>

  </tr>
  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/micromouse.png" alt="UW-Logo"> <br/>
	<b> International Micromouse Challenge</b> <br/> 
	Techfest 19-2020 & 20-2021, IIT Bombay <br/>
	<a href="https://drive.google.com/file/d/1N10GsUFk6qPmNsMxOwZvo-TO3amay-sx/view"  target="_blank">Certificate</a> <br/>
	<a href="https://drive.google.com/file/d/1Xvpvki7hyFNJYde4SkV3xRy7aYj7rbDw/view?usp=sharing"  target="_blank">Rulebook</a> <br/>
	</td>
    <td align="left">
    <center><i>Python, ROS, Gazebo, URDF</i></center>
    	<ul>
    		<li> Judged the competition and provided technical assistance to the organizers of the competition.
			</li>
			<li>
			Developed an URDF micromouse model equipped with LIDAR and generated a URDF maze for the competition.
			</li>
    		<li>
			Wrote a sample python script to run the micromouse in the maze.
			</li>
    	</ul>
    </td>

  </tr>

  <tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/rr.png" alt="UW-Logo"> <br/>
	<b> Rapid Rescuer </b> <br/> 
	IIT Bombay <br/>
	<a href="https://ieeexplore.ieee.org/document/9453995"  target="_blank">IEEE Paper</a> <br/>
	<a href="https://www.youtube.com/embed/pu-BkZVaOLQ"  target="_blank">Video</a> <br/>
	</td>
    <td align="left">
    <center><i>C, Sockets, Sensors</i></center>
    	<ul>
    		<li> Partnered with three team members in building MicroMouse like theme for the e-Yantra Robotics Competition
2019-20 to teach on OpenCV, Socket Programming, Embedded Systems and Hardware Designing to around 4000
students through Task Based Training.
			</li>
    	</ul>
    </td>

  </tr>

</table>

## Deep Learning Project

<table style="width:100%">

<tr>
    <td style="width: 30%;" align="center"><img width="100px" height="100px" src="{{site.baseurl}}/_pages/projects/gymbo.png" alt="UW-Logo"> <br/> 
	<b> GymBo </b> <br/> 
	University of Washington <br/>
	Course Project <br/>
	<a href="https://www.youtube.com/embed/HcZkt09OFKg"  target="_blank">Video</a> <br/>
	</td>
    <td align="left">
    <center><i>Python, Pytorch, OpenCV, Deep Learning, Computer Vision</i></center>
    	<ul>
    		<li>Developed a deep learning-based workout assistant application to identify mistakes during an exercise and count the
number of incorrect repetitions in a set of exercises. A ResNet3D-18 backbone was used to classify the exercises, and a
pre-trained OpenPose MobileNetv1 was used to generate the kinematic model of the user doing the exercise.
			</li>
    	</ul>
    </td>

  </tr>

</table>


<br/>

<!-- ____________________________________________________________ -->
<!-- ____________________________________________________________ -->
<!-- ____________________________________________________________ -->


# Patent and Publications

<table style="width:100%">
  
  <tr>
    <td>
      <b><span style="font-size:1.1em;">An Apparatus having at least Dual-Microcontrollers on a Printed Circuit Board (eYFi-Mega Development Board)</span></b>
      <!-- <br/> <span style="font-size:0.8em;">Jun. 19 - Present, </span> -->
      <b><span style="font-size:0.8em;">IIT Bombay</span></b>
      <br/> <span style="font-size:0.8em;"> Dr. Kavi Arya, Prasad Trimukhe, Sourav Jena, Kalind Karia</span> 
      <br/> <b><span style="font-size:0.8em;">Link:</span></b>
      <a style="font-size:0.8em;" href="http://products.e-yantra.org/eyfi-mega/"  target="_blank">Product Page</a> 
      <br/> <b><span style="font-size:0.8em;">Status: Patent Pending (Application No: <a style="font-size:0.8em;" href="https://drive.google.com/file/d/1Zu8DRXQV6ZWR5S5kxHddBm599YaU18YV/view?usp=sharing"  target="_blank">IN 202121023159</a>) </span></b>

<!--       <br/><br/><span style="font-size:0.85em;">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eu mi vel libero vestibulum imperdiet. Nam non lectus at purus placerat bibendum ac vel ipsum. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Vestibulum molestie ultricies ullamcorper. Nullam quis tortor lobortis, hendrerit elit a, malesuada tortor. Curabitur sed sollicitudin odio, at posuere ante.
      </span><br/><br/> -->

    </td>

  </tr>

  <tr>
    <td>
      <b><span style="font-size:1.1em;">Integrating Industry 4.0 in engineering education during a global pandemic: Approach and Learning Efficacy</span></b>
      <!-- <br/> <span style="font-size:0.8em;">Jun. 19 - Present, </span> -->
      <b><span style="font-size:0.8em;">IIT Bombay</span></b>
      <br/> <span style="font-size:0.8em;">Sourav Jena, Gayatri Ranade, Ruchi Sharma, Dr. Kavi Arya</span>
	  <br/> <b><span style="font-size:0.8em;">Status: Accepted in <a style="font-size:0.8em;" href="http://www.educon-conference.org/current/"  target="_blank">IEEE EDUCON 2022 </a> Conference, Tunis, Tunisia</span></b> 
	  
<!--       <br/> <b><span style="font-size:0.8em;">Links:</span></b>
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Paper</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Project Page</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Video Demo</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Source Code</a>
      <br/> <b><span style="font-size:0.8em;">Status: Ongoing</span></b> -->

<!--       <br/><br/><span style="font-size:0.85em;">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eu mi vel libero vestibulum imperdiet. Nam non lectus at purus placerat bibendum ac vel ipsum. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Vestibulum molestie ultricies ullamcorper. Nullam quis tortor lobortis, hendrerit elit a, malesuada tortor. Curabitur sed sollicitudin odio, at posuere ante.
      </span><br/><br/> -->

    </td>

  </tr>

  <tr>
    <td>
      <b><span style="font-size:1.1em;">PBL Approach in Online Robotics Competition in Resource-Poor Environments: Maze Solver Robot</span></b>
      <!-- <br/> <span style="font-size:0.8em;">Jun. 19 - Present, </span> -->
      <b><span style="font-size:0.8em;">IIT Bombay</span></b>
      <br/> <span style="font-size:0.8em;">Suprabha Jadhav, Kalind Karia, Prasad Trimukhe, Sourav Jena, Dr. Kavi Arya</span>
	  <br/> <b><span style="font-size:0.8em;">Status: Published in IEEE EDUCON 2021 Conference, Vienna, Austria </span></b>
	  <br/> <b><span style="font-size:0.8em;">Link:</span></b>
      <a style="font-size:0.8em;" href="https://ieeexplore.ieee.org/document/9453995"  target="_blank">Paper</a>  
<!--       <br/> <b><span style="font-size:0.8em;">Links:</span></b>
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Paper</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Project Page</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Video Demo</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Source Code</a>
      <br/> <b><span style="font-size:0.8em;">Status: Ongoing</span></b> -->

<!--       <br/><br/><span style="font-size:0.85em;">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eu mi vel libero vestibulum imperdiet. Nam non lectus at purus placerat bibendum ac vel ipsum. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Vestibulum molestie ultricies ullamcorper. Nullam quis tortor lobortis, hendrerit elit a, malesuada tortor. Curabitur sed sollicitudin odio, at posuere ante.
      </span><br/><br/> -->

    </td>

  </tr>

  <tr>
    <td>
      <b><span style="font-size:1.1em;">Desk-Farmer: Cultivation on the Office-Desk</span></b>
      <!-- <br/> <span style="font-size:0.8em;">Jun. 19 - Present, </span> -->
      <b><span style="font-size:0.8em;">IIT Bombay</span></b>
      <br/> <span style="font-size:0.8em;">Rishikesh Madan, Sourav Jena, Rathin Biswas, Dr. Kavi Arya</span>
	  <br/> <b><span style="font-size:0.8em;">Status: Published in Lecture Notes in Civil Engineering, Springer Singapore </span></b>
	  <br/> <b><span style="font-size:0.8em;">Link:</span></b>
      <a style="font-size:0.8em;" href="https://link.springer.com/chapter/10.1007/978-981-33-4114-2_19"  target="_blank">Paper</a>  
<!--       <br/> <b><span style="font-size:0.8em;">Links:</span></b>
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Paper</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Project Page</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Video Demo</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Source Code</a>
      <br/> <b><span style="font-size:0.8em;">Status: Ongoing</span></b>
 -->
<!--       <br/><br/><span style="font-size:0.85em;">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eu mi vel libero vestibulum imperdiet. Nam non lectus at purus placerat bibendum ac vel ipsum. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Vestibulum molestie ultricies ullamcorper. Nullam quis tortor lobortis, hendrerit elit a, malesuada tortor. Curabitur sed sollicitudin odio, at posuere ante.
      </span><br/><br/> -->

    </td>

  </tr>

  <tr>
    <td>
      <b><span style="font-size:1.1em;">Retrofitment of CNC machines for Hybrid Layered Manufacturing</span></b>
      <!-- <br/> <span style="font-size:0.8em;">Jun. 19 - Present, </span> -->
      <b><span style="font-size:0.8em;">IIT Kanpur</span></b>
      <br/> <span style="font-size:0.8em;">Sourav Jena, Ravi Raj, Prof. J. Ramkumar</span>
	  <br/> <b><span style="font-size:0.8em;">Status: Published in SURGE 2016 </span></b>
	  <br/> <b><span style="font-size:0.8em;">Link:</span></b>
      <a style="font-size:0.8em;" href="https://drive.google.com/file/d/10GQhUYejyLO33X-e44WHkGzVVf4vWjAe/view?usp=sharing"  target="_blank">Report</a>  
<!--       <br/> <b><span style="font-size:0.8em;">Links:</span></b>
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Paper</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Project Page</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Video Demo</a>, 
      <a style="font-size:0.8em;" href="http://www.yahoo.com"  target="_blank">Source Code</a>
      <br/> <b><span style="font-size:0.8em;">Status: Ongoing</span></b>

      <br/><br/><span style="font-size:0.85em;">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eu mi vel libero vestibulum imperdiet. Nam non lectus at purus placerat bibendum ac vel ipsum. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Vestibulum molestie ultricies ullamcorper. Nullam quis tortor lobortis, hendrerit elit a, malesuada tortor. Curabitur sed sollicitudin odio, at posuere ante.
      </span><br/><br/> -->

    </td>

  </tr>

</table>

<br/>

# Honors and Awards

[//]: # "Trophy emoji ~🏆~"
[//]: # "First Place emoji ~🥇~"
[//]: # "Second Place emoji ~🥈~"
[//]: # "Third Place emoji ~🥉~"

<table style="width:100%">
  <tr>
    <td align="left">🏆 <b>Summer Undergraduate Research Grant for Excellence 2016, IIT Kanpur</b> 
    	<br/> Awarded to 0.0575% of 1600 applicants. <a href="https://drive.google.com/file/d/0B97KaJlgFNSPVXJtSUFoakgtaGs/view?usp=sharing&resourcekey=0-X6TWiZo0MGvXP8TS_g6uhQ"  target="_blank">Certificate</a>
    </td>
  </tr>
  
  <tr>
    <td align="left">🏆 <b>Renesas GR-Kaede Design Contest 2015, Bengaluru</b> 
    	<br/> Finalist (Top 20) among 2000 abstracts. <a href="https://drive.google.com/file/d/0B97KaJlgFNSPbVB1UXl1bndrNW8/view?usp=sharing&resourcekey=0-WqHb-NKow8ht55L_LHyf0w"  target="_blank">Certificate</a>
    </td>
  </tr>

  <!-- <tr>
    <td align="left">🏆 <b>Wild Soccer, Techkriti 15, IIT Kanpur</b> 
    	<br/> Finalist (Top 20) among 2000 abstracts. <a href="https://drive.google.com/file/d/1cvO9a9oV0y8HSgw3f9sog_1GdWMpHGRE/view?usp=sharing"  target="_blank">Certificate</a>
    </td>
  </tr>

  <tr>
    <td align="left">🏆 <b>Aqua Soccer, Anwesha 2015, IIT Patna</b> 
    	<br/> Finalist (Top 20) among 2000 abstracts.
    </td>
  </tr>

  <tr>
    <td align="left">🏆 <b>Death Race, Anwesha 2015, IIT Patna</b> 
    	<br/> Finalist (Top 20) among 2000 abstracts.
    </td>
  </tr>

  <tr>
    <td align="left">🏆 <b>Indo-US Robo League 2014</b> 
    	<br/> Finalist (Top 20) among 2000 abstracts.
    </td>
  </tr> -->

</table>

<br/>

# Teaching

<table style="width:100%">
    <tr>
      <td align="left">2019-2021, <b>Embedded Systems Instructor</b>, IIT Bombay
      </td>
    </tr>
    <tr>
      <td align="left">2015-17, <b>Instructor</b>, Roboitcs Club, BIT Mesra
      </td>
    </tr>
    <tr>
      <td align="left">2013-16, <b>Community Tutor</b>, Women's Organisation for Socio-Cultural Awareness
      </td>
    </tr>
    <tr>
      <td align="left">2016-17, <b>Vice Captain</b>, ECE Soccer Team, BIT Mesra
      </td>
    </tr>
</table>

<br/>
<br/>

# Position of Responsibility

<table style="width:100%">
    <tr>
      <td align="left">2020-21, <b>Judge</b>, International Micromouse Challenge, Techfest 2020, IIT Bombay
      </td>
    </tr>
    <tr>
      <td align="left">2016-17, <b>Traning and Placment Officer</b>, BIT Mesra
      </td>
    </tr>
    <tr>
      <td align="left">2015-17, <b>President</b>, Robotics Club, BIT Mesra
      </td>
    </tr>
    <tr>
      <td align="left">2016-17, <b>Vice Captain</b>, ECE Soccer Team, BIT Mesra
      </td>
    </tr>
</table>

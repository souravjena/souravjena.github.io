---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<html>
<head>

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
  background-color: #808080;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
</style>
</head>
<body>

<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>

<script>
// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    document.getElementById("myBtn").style.display = "block";
  } else {
    document.getElementById("myBtn").style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

<!-- ********************************* START *********************************  -->

 <table style="width:100%">

  <col width="130">
  <col width="80">

  <tr>
    <td>
    	<span><img src="bit-mesra.jpg" alt="" border=3 height=100 width=100></img></span>
    	<span style="horizontal-align: middle;">Title of the project</span>
	</td>
    
    <td>Smith</td>
  </tr>

  <tr>
    <td>Eve</td>
    
    <td>Jackson</td>
  </tr>

</table> 


<!-- ********************************* END *********************************  -->

</body>
</html>
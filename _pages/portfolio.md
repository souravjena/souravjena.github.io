---
layout: archive
title: "Portfolio"
permalink: /portfolio/
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

<h2>Table of Contents</h2>

 <br><table style="width:100%">

  <col width="130">
  <col width="80">

  <tr>
    <td><a href="#Project-A">Project-A</a></td>
    <td>Links</td>
  </tr>

  <tr>
    <td>Eve</td>
    
    <td>Jackson</td>
  </tr>

</table> 



<h3 id="Project-A">Project-A</h3>
<p style="font-size:1em"> Lorem Ipsum </p>

<!-- ********************************* END *********************************  -->

</body>
</html>
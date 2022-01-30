---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
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

/*A:link { COLOR: black; TEXT-DECORATION: none; font-weight: normal }
A:visited { COLOR: black; TEXT-DECORATION: none; font-weight: normal }
A:active { COLOR: black; TEXT-DECORATION: none }
A:hover { COLOR: blue; TEXT-DECORATION: none; font-weight: none }
*/

a:hover, a:visited, a:link, a:active
{
    text-decoration: none;
}

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

 -->

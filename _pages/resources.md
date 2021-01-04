---
layout: single
permalink: /resources/
author_profile: true
title: "Resources"
---


<div style="float: right">
    Something that stays right and is not wrapped in a para.
</div>

{::options parse_block_html="true" /}

<div>
    This is wrapped in a para.
</div>
<p>
    This can contain only *span* level elements.
</p>


<h2>JavaScript Confirm Box</h2>


<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  var txt;
  if (confirm("Press a button!")) {
    txt = "You pressed OK!";
  } else {
    txt = "You pressed Cancel!";
  }
  document.getElementById("demo").innerHTML = txt;
}
</script>



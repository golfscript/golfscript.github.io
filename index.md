# GolfScript.js

## A full JavaScript interpreter for GolfScript

Read more about it and download the code at <https://github.com/golfscript/golfscript.js>

You can test some GolfScript in your browser below

<script src="/golfscript.js/golfscript.js"></script>
<script>const get = id => document.getElementById(id)</script>

<textarea id="code" placeholder="code" style="width:100%;height:100px"># Greatest common divisor
2706 410
{.@\%.}do;</textarea>
<button onclick="get('output').innerText=GolfScript(get('code').value)">Go</button>
<pre id="output"></pre>
<style>header ul {display:none}</style>

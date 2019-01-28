<h1><a id="JStrianglefunction_0"></a>JS-triangle-function</h1>
<p>A function to draw a triangle using 3 parameteres.</p>

<p>You can see the live preview on: <a href="https://negrut112.github.io/JS-triangle-function/">https://negrut112.github.io/JS-triangle-function/</a>.<br>
  
<a href="https://i.imgur.com/EzsjnuW.jpg">https://i.imgur.com/EzsjnuW.jpg</a></p>

<b>HTML</b>

<p>I have used the HTML to define the area where I’m working defining the height, width and the border style:</p>
<p>&lt;canvas id=“myCanvas” height=“310” width=“500” style=“border: 1px solid black”&gt;&lt;/canvas&gt;</p>

<b>JavaScript</b>

<p>On JS , I made a function to generate a equilateral triangle using 3 parameters: first two are for starting point (top point) and the 3rd is the length of a side.</p>
<p>function triangle(x,y,a){<br>
context.fillStyle=‘rgb(203, 219, 0,0.7)’<br>
context.strokeStyle=‘grey’<br>
context.beginPath();<br>
context.moveTo(x, y); // starting point<br>
context.lineTo(x-a/2,y+Math.sqrt(a<em>a-a/2</em>a/2)); // math formulas to find the left bottom point<br>
context.lineTo(x+a/2,y+Math.sqrt(a<em>a-a/2</em>a/2)); // math formulas to find the right bottom point<br>
context.lineTo(x, y);<br>
context.fill();<br>
context.stroke();<br>
}</p>

<h1>Script for converting PNG pictures to ROM (6 bits)</h1>
<h3>Author: Luis Leon Vega</h3>
<br>
<h3>Description:</h3>
<p>With this script, you can convert the PNG pictures and compress it with a 6 bit resolution (RGB). Also, you can generate an .bin files with the color info to upload it into a ROM for doing UI in a VGA implemented in a FPGA</p>
<br>
<h3>Specs:</h3>
<p>I recommend you these specs for using this script:</p>
<ul>
  <li><b>Input file:</b> example.png * I've not tested it in other formats</li>
  <li><b>Output file:</b> example.bin</li>
  <li><b>Size:</b> It's not limited (I used this with a 640X480 picture)</li>
</ul>
<br>
<h3>Using example:</h3>
<p>For using this script you need Matlab or Octave to run it. For using you need to write the script name ("ImgToROM") and send the picture's name as a parameter. Something like:</p>
<p> >>ImgToROM('example.png');</p>
<p>With this, you can run it and generate the .bin file </p>
<br>
<h3>About:</h3>
<p>This script was made for a project at the Tecnológico de Costa Rica in the course of Digital Electronics Lab. You can use it freely if it helps you </p>

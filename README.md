d3MapMaker
==========

An automated d3 map maker. 
Input the 3 character country code of the country you want. Example: AFG for Afghanistan, (this will improve in next updates) and you will get an index.html file with your map in SVG using D3 and scaled to 900.


# Instructions
You need to install  the <a href="http://www.gdal.org/" target="_blank">(GDLA) Geo spatial Data Abstraction Library</a>. Mac users download from <a href="http://www.kyngchaos.com/software/frameworks" target="_blank">this link</a>

Once you have downloaded GDAL install it.

Create a repo for this map 

<pre>
  <code>
    mkdir myMap
  </code>
</pre>

Cd to that repo

<pre>
  <code>
    cd myMap
  </code>
</pre>

Run the python script

<pre>
  <code>
    ./fetch.py
  </code>
</pre>

You will then be prompted to enter the name of the country that you want a map of. Type it in, hit enter and that should be it.

<strong>NOTE</strong>: The scale of the map is set to 900. You might see it a bit small or maybe not even at all. Make sure to inspect your DOM to corroborate that the map was created.

This will create what you need an launch a localhost:7777. Go that that URL and you should see your map.

## Todos
<ol>
  <li>Make the dictionary of countries more robust to handle special characters, partial type ins etc.</li>
  <li>Include js code to center the map projection and scale it to something bigger than 900</li>
</ol>


  
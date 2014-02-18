<html><head>
  <meta http-equiv="Content-Type" content="text/html;charset=utf-8">
  <style type="text/css">
  </style>
</head><body>
<div id="header">
<h1> dbap4live </h1>
<h2> dbap spatialisation tool inside Ableton Live  </h2>
</div>
<h3>Dependancies</h3>
<strong>You need to have Jamoma installed in your computer for running dbap4live.</strong>
<h3>Files</h3>
<ul><li><span style="font-weight: bold; font-style: italic;">dbapSTRack.adg</span> is the device you load on each stereo track you want to spatialize<br>
</li>
  <li><span style="font-weight: bold; font-style: italic;">dbapRack.adg</span> is the device you load on a mono track you want to spatialize</li>
  <li><span style="font-weight: bold; font-style: italic;">dbapSetup.amxd</span> is the device you load one time per project for allowing remote control via OSC</li>
  <li><span style="font-weight: bold; font-style: italic;">dbapRemote.amxd</span> is the max patch you run to control the position of the source (need dbapSetup.amxd in the Live project)<br>
  </li>
</ul>
<h3>Installation</h3>
<ul><li>unzip <span style="font-weight: bold; font-style: italic;">dbap4live-0.x.zip</span> in ~user/Library/Application Support/Ableton/Library/Presets/Audio Effects/Max Audio Effect.</li>
  <ul>
    <li><span style="font-style: italic; color: rgb(91, 91, 91);">You can use a folder-alias if you want to work with a subversion repository.</span></li>
    <ul>
      <li><span style="font-style: italic; color: rgb(91, 91, 91);">make an alias of the trunk</span></li>
      <li><span style="font-style: italic; color: rgb(91, 91, 91);">put this alias in the Max Audio Effect folder.</span><br>
      </li>
    </ul>
  </ul>
<li>Drag and Drop the rack <span style="font-weight: bold; font-style: italic;">dbapSTRack</span> in the audio track you want to spatialize with a STEREO source.<br>
</li><li>Drag and Drop the rack <span style="font-weight: bold; font-style: italic;">dbapRack</span> in the audio track you want to spatialize with a MONO source.</li></ul>
<h3>Credits</h3>
<ul>
<li>Pascal Baltazar</li>
<li>Renaud Rubiano</li>
</ul>
<h3>Change-log</h3>
<ul>
<li>0.3.0</li>
<ul><li>Live API change the way to access the track name from a device inside a rack</li></ul>
<li>0.2.4</li>
<ul><li>Recovering parameter storage</li></ul>
<li>0.2.2</li>
<ul><li>Fix bug when loading the Mono-rack the first time.</li>
<li>Add documentation via Live-contextual help</li></ul>
<li>0.2.1</li><ul><li>Fix bug when loading the Stereo-rack the first time.</li></ul></ul>
<h3>Licence</h3>
<p>The software documentation and other distributed materials are licensed under the terms of the GNU GPL.
<br>
More information is available from the Free Software Foundation.</p>
</body></html>

---
layout: default
title: Home
---

<h3><a name="welcome-to-github-pages" class="anchor" href="#welcome-to-github-pages"><span class="octicon octicon-link"></span></a>Description</h3>

<p>This mod adds slopes and a custom variety of vanilla-inspired blocks to Minecraft. The custom nature of these blocks allows players to cover them using most solid blocks in the game. Once covered, they look and act just like the block they're mimicking, but in entirely new shapes! For example, make some obsidian stairs that are resistant to explosions. Or, make glowstone take the shape of a pyramid top. With Carpenter's Blocks, building takes on new possibilities!</p>

<h3><a name="designer-templates" class="anchor" href="#designer-templates"><span class="octicon octicon-link"></span></a>Downloads</h3>

<h4>Dependencies</h4>
<span id="label-minecraft" onclick="window.open('https://minecraft.net/')">MINECRAFT</span>
<p>The minimum required version of Minecraft to run a build.  Builds are compiled using SRG names, which may enable them to run on later builds of Minecraft.  Please keep in mind this does not guarantee stability unless the Minecraft version matches exactly.</p>
<span id="label-forge">FORGE</span>
<p>The necessary version of Forge to run a build.  Grab the version you need <a href="http://files.minecraftforge.net/" target="_blank">here</a>.

<h4>Builds</h4>

<div id="download-container">
   <div id="development-header" class="text-shadow">
      Development (for <a href="http://www.patreon.com/mineshopper" class="patron text-shadow" target="_blank">Patrons</a> only)
   </div>
   <div id="download-content">
      <div style="display: none;">
         <span id="label-warn">!</span><span style="font-style: italic;">There are currently no development builds.</span>
      </div>
      
      <span id="label-minecraft">1.7.10</span>
      <span id="label-forge">10.13.0.1180</span>
      Carpenter's Blocks 3.2.5 <div class="expand">View Changelog</div><br>
      <div class="hidden">
         <ul id="changelog">
            <li>Refactored safe code to help prevent crashes.</li>
            <li>Now must sneak to apply safe upgrade.</li>
            <li>Bed designs now fully support texture packs.</li>
            <li>Fixed some conditions where plants could not be placed on covered blocks.</li>
            <li>Fixed slope selection not cycling backwards correctly.</li>
            <li>Fixed minor bug in ladder placement validation.</li>
            <li>Rewrote packet handler.</li>
            <li>Fixed plant fertilization crashing server.</li>
            <li>Bed designs should now load properly on Unix systems. [Noxilie]</li>
            <li>Code cleanup.</li>
            <li>Ownership properties shifted over to new UUID system.</li>
            <li>Forge build requirement set at 1180.</li>
         </ul>
      </div>
      
      <span id="label-minecraft">1.7.2</span>
      <span id="label-forge">10.12.2.1121</span>
      Carpenter's Blocks 3.2.5
      <div class="expand">View Changelog</div><br>
      <div class="hidden">
         <ul id="changelog">
            <li>Refactored safe code to help prevent crashes.</li>
            <li>Now must sneak to apply safe upgrade.</li>
            <li>Bed designs now fully support texture packs.</li>
            <li>Fixed some conditions where plants could not be placed on covered blocks.</li>
            <li>Fixed slope selection not cycling backwards correctly.</li>
            <li>Fixed minor bug in ladder placement validation.</li>
            <li>Rewrote packet handler.</li>
            <li>Fixed plant fertilization crashing server.</li>
            <li>Bed designs should now load properly on Unix systems. [Noxilie]</li>
            <li>Code cleanup.</li>
            <li>Upgraded Forge build requirement to 1121.</li>
         </ul>
      </div>
      
      <span id="label-minecraft">1.6.4</span>
      <span id="label-forge">9.11.1.965</span>
      Carpenter's Blocks 3.2.5 <div class="expand">View Changelog</div><br>
      <div class="hidden">
         <ul id="changelog">
            <li>Backported from master branch and brought up to date.</li>
            <li>Fixed flower pot soil and plant not migrating to 1.7.</li>
            <li>Upgraded Forge build requirement to 965.</li>
         </ul>
      </div>
      
   </div>
</div>

<div id="download-container">
   <div id="stable-header" class="text-shadow">
      Stable (Recommended)
   </div>
   <div id="download-content">
      <span id="label-minecraft">1.7.2</span>Carpenter's Blocks 3.2.4<br>
      <span id="label-minecraft">1.6.4</span>Carpenter's Blocks 2.1.2<br>
      <span id="label-minecraft">1.5.2</span>Carpenter's Blocks 1.9.9
   </div>
</div>

<div id="download-container">
   <div id="extra-header" class="text-shadow">
      Extras
   </div>
   <div id="download-content">
      <span id="label-extra">LEGACY</span>Legacy versions can be found by browsing the <a href="http://adf.ly/dMfV4" target="_blank">root download folder</a>.<br>
      <a href="changelog.html">View Complete Changelog</a>
   </div>
</div>

<h3><a name="designer-templates" class="anchor" href="#designer-templates"><span class="octicon octicon-link"></span></a>Migrating 1.6.X worlds to 1.7.X</h3>

<p>To migrate your Carpenter's Blocks 1.6.4 worlds to 1.7.2, follow these steps:</p>
<ol>
   <li>Load Carpenter's Blocks v2.1.2 or later for MC 1.6+ into your mods folder in the 1.6.4 subdirectory.</li>
   <li>Load Carpenter's Blocks v3.2.0 or later for MC 1.7+ into your mods folder in the 1.7.2 subdirectory.</li>
   <li>Start the game in Minecraft 1.6.4 and load the world.</li>
   <li>Ensure ALL chunks with Carpenter's Blocks have been loaded into memory by visiting all locations where the blocks are used.</li>
   <li>Exit game.</li>
</ol>
<p>The blocks should now be prepared for migration. Start the game in Minecraft 1.7.2 and load the world. Note: run the latest recommended version of Forge for 1.7.2 to ensure you don't run into problems.</p>

<p>What won't survive the migration:</p>
<ul>
   <li>Placed doors and beds will disappear, so be sure to destroy them first.</li>
   <li>Chisel patterns and designs will disappear from placed blocks.</li>
</ul>
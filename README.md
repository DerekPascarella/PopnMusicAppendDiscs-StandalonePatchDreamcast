<h1>Pop'n Music - Append Discs 3 and 4</h1>
<p align="center"><img width="521" height="188" src="https://github.com/DerekPascarella/PopnMusicAppendDiscs-StandalonePatchDreamcast/blob/main/pop_n_music_append_disc_title_screens.png?raw=true"></p>
Patches that allow "Append Discs" 3 and 4 to boot as standalone games, rather than requiring they be launched first with Pop'n Music 2.
<br><br>

<h2>Download Patches</h2>
<ul>
 <li><a href="https://github.com/DerekPascarella/PopnMusicAppendDiscs-StandalonePatchDreamcast/raw/main/Pop'n%20Music%203%20-%20Append%20Disc%20(Standalone).dcp">Pop'n Music 3 - Append Disc (Standalone).dcp</a></li>
 <li><a href="https://github.com/DerekPascarella/PopnMusicAppendDiscs-StandalonePatchDreamcast/raw/main/Pop'n%20Music%204%20-%20Append%20Disc%20(Standalone).dcp">Pop'n Music 4 - Append Disc (Standalone).dcp</a></li>
</ul>

<h2>Patching Instructions</h2>
<ul>
 <li><b>GDI Format (Users of ODEs or Emulators)</b><br><img align="right" width="250" src="https://github.com/DerekPascarella/UniversalDreamcastPatcher/blob/main/screenshots/screenshot.png?raw=true">The DCP patch file shipped with this release is designed for use with <a href="https://github.com/DerekPascarella/UniversalDreamcastPatcher">Universal Dreamcast Patcher</a> v1.3 or newer.  Note that Universal Dreamcast Patcher supports both TOSEC-style GDI and Redump-style CUE disc images as source input.<br><br><ol type="1"><li>Click "Select GDI or CUE" to open the source disc image.</li><li>Click "Select Patch" to open the DCP patch file.</li><li>Click "Apply Patch" to generate the patched GDI, which will be saved in the folder from which the application is launched.</li><li>Click "Quit" to exit the application.</li></ol></li>
 <br>
 <li><b>CDI Format (Users Burning to CD-R)</b><br><img align="right" width="250" src="https://i.imgur.com/r4b04e7.png">The XDelta patch file shipped with this release can be used with any number of Delta utilities, such as <a href="https://www.romhacking.net/utilities/704/">Delta Patcher</a>. Ensure the source CDI has an MD5 checksum of <tt>4B21B746AFA604211910DC40C993DF87</tt>.<br><br><ol type="1"><li>Click the settings icon (appears as a gear) and enable "Backup original file" and "Checksum validation".</li><li>Click the "Original file" browse icon and select the unmodified CDI.</li><li>Click the "XDelta patch" browse icon and select the XDelta patch.</li><li>Click "Apply patch" to generate the patched CDI in the same folder containing the original CDI.</li><li>Verify that the patched CDI has an MD5 checksum of <tt>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</tt>.</ol></li>
</ul>

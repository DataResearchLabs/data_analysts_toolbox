<img align="left" src="https://github.com/DataResearchLabs/data_analysts_toolbox/blob/main/text_files_end_of_line_editor/img/icon_end_of_line_editor.png" width="64px">

# End-of-Line Editor (EOLE)
[![License: CC0](https://img.shields.io/badge/License-CC0-red)](LICENSE "Creative Commons Zero License by DataResearchLabs (effectively = Public Domain")
![current_build Office_365](https://img.shields.io/badge/Access_Version-Office_365-yellow)
[![Latest Release](https://img.shields.io/badge/Latest_Release-V2.0.1.44482-blue)](https://github.com/DataResearchLabs/data_analysts_toolbox/tree/main/text_files_end_of_line_editor/download)
[![YouTube](https://img.shields.io/badge/YouTube-DataResearchLabs-brightgreen)](http://www.DataResearchLabs.com)
#### Part of the "Data Analysts' Toolbox"


## Overview
* **What**: A free, simple utility for identifying and changing end-of-line characters in text files.<br>
* **Levelset**: Windows PC files end lines with CR+LF (carriage return + line feed).  Linux, Unix, and the newer MAC end lines with just LF.  The older MacOS ended lines with CR.  Text editors and applications in the various operating systems often cannot read files written in another OS until you change the end of line characters.<br>
* **Why**: Sometimes you need to convert a text file created in Linux (LF terminator) into a file PCs can read (CR+LF terminator).  Same for the reverse direction, or going to or from the old MacOS.  On rare occasions, you'll even see files that for whatever reason mix and match end of line terminators (eg: all CRLF's with one line having only a CR).  You can use this simple utility to quickly spot these issues, and fix them.<br>
* **How**: Download and run .accdb file.  From there, click open and pick the text file of interest and wait for it to load and parse out.  It will popup with a row count as well as a count of each end-of-line terminator encountered.  Select the new end-of-line you want from the drop-down, and click the convert button.<br>
* **Who**: Built as a standalone tool for individual data analysts, software test engineers, or similar folks.<br>
* **Where**: On a desktop or laptop.  **Requires Microsoft Access 365**.  Yep, it is a VBA application, [read here for why](https://github.com/DataResearchLabs/my_task_time_tracker/blob/main/src/SOURCE_CODE.md#whyMicrosoftAccess)<br>
* **License**: Creative Commons Zero, effectively public domain.  Free to use.  Free to copy.  Free to alter.  Free to distribute.<br>

## Download
Click here to **[download the application](https://github.com/DataResearchLabs/data_analysts_toolbox/tree/main/text_files_end_of_line_editor/download)**.  This package contains an .accde file that is locked so source code is inaccessible and can be safely used in your organization.<br><br>

Click here to **[download the source code](https://github.com/DataResearchLabs/data_analysts_toolbox/blob/main/text_files_end_of_line_editor/src/eol_editor.accdb)**.  This is an .accdb file that is open-source. Either (a) close all forms and press F11, **OR** (b) hold down the Shift-key when you open the application to access ALL source code.

***If you like this tool, be sure to click the "Star" button above in GitHub.*** <br>
<br>
***Also, be sure to visit or subscribe to our YouTube channel*** www.DataResearchLabs.com!<br>
<br>


## Training Videos
<table><tr>
<td>
  
 ***Video #1 "Overview Tutorial"***<br>
  <kbd>
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=Azh5NyW1Yp8" target="_blank">
   <img src="http://img.youtube.com/vi/Azh5NyW1Yp8/0.jpg" alt="Overview Video" width="200" />
  </a>
  </kbd>
</td>
<td>
  
 ***Video #2 "Download & Deploy"***<br>
  <kbd>
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=3l__kMmxFqI" target="_blank">
   <img src="http://img.youtube.com/vi/3l__kMmxFqI/0.jpg" alt="Overview Video" width="200" />
  </a>
  </kbd>
</td>
 </tr></table> 
<br>
<br>


## Screenshot
<kbd>
  <img src="img/main_screen_x.png" width="1123">
</kbd>



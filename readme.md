# RDTXT
A simple text file viewer for Organiser II model CM, XP, LA, LZ & POS models

This <a href="https://en.wikipedia.org/wiki/Psion_Organiser"> Organiser II</a> <a href="https://en.wikipedia.org/wiki/Open_Programming_Language">OPL program</a> allows viewing of a text file held on any of the Organiser II data packs. .  

<div align="center">
  <div style="display: flex; align-items: flex-start;">
    <img src="https://github.com/nofitnessforpurpose/rdtxt/blob/main/images/MAN01.jpg?raw=true" height="400px" alt="NotFitForPurpose Image copyright (c) 20 August 2025 nofitnessforpurpose All Rights Reserved">
  </div>
</div>
<BR>

[![Organiser](https://img.shields.io/badge/gadget-Organiser_II-blueviolet.svg?%3D&style=flat-square)](https://en.wikipedia.org/wiki/Psion_Organiser)
[![GitHub License](https://img.shields.io/github/license/nofitnessforpurpose/rdtxt?style=flat-square)](https://github.com/nofitnessforpurpose/rdtxt/blob/main/LICENSE)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg?style=flat-square)](https://github.com/nofitnessforpurpose/rdtxt/graphs/commit-activity)
![GitHub repo size](https://img.shields.io/github/repo-size/nofitnessforpurpose/rdtxt?style=flat-square)

## Using
The code will prompt for a filename (which will have no extension on the Organiser II). The default filename is A:README.  
The arrow keys allow scrolling left, right, up or down through the file.  
The program turns off keyboard clicks, speeds up key repeat rate and scroll rates. Default settings are re-established when viewing is terminated.  
When white space is being viewed in the 'viewing frame' i.e. the Organsisers display, a custom character down right arrow is displayed in the top left corner.  
Exiting viewing is selected by presing ESC, q, Q, or EXE.  

### File specification
The file type viewable is a text file:

 ~~~ 
<text-file>   ::= <lines> | ε

<lines>       ::= <line>
               |  <line> <newline> <lines>

<line>        ::= <characters>                (* a line is any sequence of characters, possibly empty *)

<characters>  ::= ε
               |  <character> <characters>

<character>   ::= <printable>                 (* any character except CR or LF *)

<newline>     ::= <lf>
               |  <cr> <lf>

<cr>          ::= "\r"
<lf>          ::= "\n"

<printable>   ::= <unicode-scalar-except-CR-or-LF>
 ~~~ 


## Use Case
A standalone viewer for viewing of text files. The text files might for example have been created locally on the device or downloaded.  

Note  
Organiser II program files are not text files. Attempting to open a program file may lock the device!  

<BR>

## Installation
<a href="https://www.jaapsch.net/psion/connect.htm">Download</a> the source POPL code into the target Organsier device and Translate it on the target machine. If the defualt filename rdtxt was used to save the received program file. Following translation, RUN the program rdtxt and enter the desired data pack and selected text file name.  

<BR>

## Questions / Discussion
See <a target="_blank" rel="noopener noreferrer" href="https://www.organiser2.com/"> Organiser 2 Software </a> forum, though see note below first.

<BR>

## Please note:  
All information is For Indication only.
No association, affiliation, recommendation, suitability, fitness for purpose should be assumed or is implied.
Registered trademarks are owned by their respective registrants.


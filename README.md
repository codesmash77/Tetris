Introduction

What is Tetris? It was invented in Russia and the main aim of the
game is to bring down blocks from the top of the screen. The blocks
fall at a certain rate, but you can make them fall faster manually and
you can move the blocks around as well. Your objective is to get all the
blocks to fill all the empty space in a line at the bottom of the screen
and as you do that, the blocks will vanish and hence reward you
points.
On paper it never looked like an idea that will be so popular beyond
the year 1975 but due to its goals and rules, participating will become
voluntary and there are unnecessary obstacles that keep the game
challenging.

Proposed System Design

We are using Assembly language to implement the game and we are
using Computer x86. We have tested the game on DOSBOX and
NASM.
DOSBOX is an emulator program which is used to run old games and
even used to run other MS-DOS applications. It's a free, open-source
cross platform that uses the SDL library. Many IBM PC compatible
graphics and sound cards are also emulated. DOSBOX is the standard
way to play DOS games on modern computers.

The code is written for Computer x86 architecture and tested on
DOSBOX and NASM

How to Run

1- Download this code and move the 'tetris' folder to C: directory or Desktop.

2- Install DOSBOX from this link:
Download DOSBOX Emulator - https://www.dosbox.com/download.php?main=1

3- After complete installation, go to DOSBOX installation
directory and run "DOSBox 0.74 Options.bat". This will save you
from the pain of searching the configuration file yourself and will
open that file for you.
Copy these lines at the end of that file:

mount c: c:\Desktop\Tetris
c:

4- Now to run/compile the code, run DOSBOX 0.74 and type:

nasm tetris.asm -o tetris.com

5- To run the Tertris game, type:

tetris.com

6- To examine step by step working of the code, type:

afd tetris.com

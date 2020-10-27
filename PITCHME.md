#### INCOMPATIBLE TIMESHARING SYSTEM

History, Development, and Restoration

Lars Brinkhoff

---

### OVERVIEW

- What is ITS?
- History
- Values
- Features
- Today

---

### WHAT IS ITS?

- ITS is an operating system for PDP-10 computers.
- Created at MIT in 1967, kept running until 1990.
- Known for its openness and lack of security.

<img src="pics/MIT.jpg" width="30%"></img>
<img src="pics/TechSquare.jpg" width="20%"></img>

---

### WHY DO THIS?

- Started with BASIC, then 68000 assembler
- Read about hackers as a kid
- Binutils PDP-11 support, GCC PDP-10 support
- Historical importance
- More fun than playing games

<img src="pics/vic20.jpg" width="60%"></img>
<img src="pics/dict.jpg" width="20%"></img>

---

### PDP-10 FAMILY

- Made by Digital Equipment Corporation
- Lifespan 1964-1988
- Generations: PDP-6, KA10, KI10, KL10, KS10
- Designed with Lisp in mind
- 36-bit word length, 18-bit address space
- Large orthogonal instruction set
- Pleasant assembly language
- Popular on the ARPANET

<img src="pics/PDP-1040.jpg" width="45%"></img>

---

### BEFORE ITS

- AI group 1959
- CTSS 1961-1963
- Project MAC 1963
- Multics 1964-1967

<img src="pics/CTSS.jpeg" width="40%"></img>
<img src="pics/GE645.jpg" width="43%"></img>

---

### BEGINNINGS

- At the Project MAC AI group
- For their PDP-6 computer
- Grew from singe-user tools
- First version 1967
- Alternative to CTSS and Multics

<img src="pics/PDP-6.jpg" width="31%"></img>
<img src="pics/Multics.jpg" width="25%"></img>

---

### HACKER ETHIC

<div style="float: left; width: 60%;">
<ul>
<li>ITS was written by "hackers"</li>
<li>Designed to get work done, not an academic exercise</li>
<li>Highly interactive</li>
<li>No passwords (until later)</li>
<li>No file permissions</li>
<li>Source code for everything</li>
<li>Guests allowed</li>
</ul>
</div>

<div style="float: right; width: 40%;">
<img src="pics/RMS.jpg" width="100%"></img>
</div>

---

### EARLY DEVELOPMENT

- AI PDP-10 1968
- Virtual memory 1970
- ARPANET 1971
- Two more machines: DM and ML

<img src="pics/MIT-AI.png" width="25%"></img>
<img src="pics/MIT-DMS.jpg" width="30%"></img>
<img src="pics/MIT-ML.jpg" width="28%"></img>

---

### RESEARCH

<div style="float: left; width: 60%;">
<ul>
<li>AI</li>
<li>Robotics</li>
<li>Computer Vision</li>
<li>Logo</li>
<li>Lisp, Scheme</li>
<li>Lisp Machine</li>
<li>Muddle</li>
<li>CLU</li>
<li>Macsyma</li>
<li>Networking</li>
</ul>
</div>

<div style="float: right; width: 40%;">
<img src="pics/robot.jpg" width="45%"></img>
<img src="pics/Turtle.jpg" width="45%"></img>
<img src="pics/IMP.jpg" width="40%"></img>
</div>

+++

### LISP

<div style="float: left; width: 85%;">
<ul>
<li>Invented 1958 by John McCarthy</li>
<li>Initially for IBM 704 by Steve Russell</li>
<li>Ported to PDP-6</li>
<li>Maclisp for ITS</li>
<li>Compiler competetive with Fortran</li>
<li>Lisp machine by Greenblatt and Knight</li>
<li>Scheme by Steele and Sussman</li>
</ul>
</div>

<div style="float: right; width: 15%;">
<img src="pics/McCarthy.png" width="100%"></img>
<img src="pics/CADR.jpg" width="100%"></img>
<img src="pics/GLS.png" width="100%"></img>
</div>

+++

### MACSYMA

- Joel Moses
- Used by researchers over the ARPANET
- Funded Maclisp development
- Two ITS machines

<img src="pics/Moses.jpg" width="50%"></img>

+++

### SHRDLU

- Robot simulation
- Natural language understanding
- Planning and solving problems

<img src="pics/shrdlu.jpg" width="50%">

+++

### LOGO

<div style="float: left; width: 75%;">
<font size="6.5">
<ul>
<li>BBN 1967 by Feurzeig, Papert, Solomon</li>
<li>Moved to MIT 1970</li>
<li>PDP-10 version ported to ITS</li>
<li>New versions for PDP-11, Maclisp, Apple II...<br></li>
<li>Developed on ITS</li>
<li>General Turtle, Logo machine</li>
</ul>
</font>
</div>

<div style="float: right; width: 25%;">
<img src="pics/Papert.jpg" width="100%"></img>
<img src="pics/Minsky.png" width="100%"></img>
</div>

+++

### MUDDLE

- Intended as an update of Lisp.
- Used exclusively by the Dynamic Modeling group.
- Zork was written in Muddle.
- Infocom, text adventure boom.
- Bootstrap CLU.

+++

### CLU

- Cluster
- Data abstraction
- Exceptions
- Iterators
- Parametric types
- Influenced C++, Perl, Java, Ruby, ...

<img src="pics/Liskov.jpg" width="25%"></img>

---

### HEYDAYS

- Network file system
- Memory mapped raster displays
- Space cadet-like keyboards
- MC KL10 1975
- Emacs 1976
- TCP/IP 1982

<img src="pics/knight-console.jpg" width="25%"></img>
<img src="pics/MIT-MC.jpg" width="21%"></img>

---

### GAMES

<div style="float: left; width: 50%;">
<ul>
<li>Spacewar!</li>
<li>MacHack VI</li>
<li>Flight simulator</li>
<li>Adventure</li>
</ul>
</div>

<div style="float: right; width: 50%;">
<ul>
<li>Maze War</li>
<li>Dazzle Dart</li>
<li>Moonlander</li>
<li>Zork</li>
</ul>
</div>

<img src="pics/machack.jpeg" width="15%"></img>
<img src="pics/flight.png" width="16%"></img>
<img src="pics/MazeWar.jpg" width="12%"></img>
<img src="pics/dazzle.png" width="16%"></img>
<img src="pics/Zork.jpg" width="25%"></img>

<!--

### IMPORTED SOFTWARE

- Emulator for TOPS-10 and WAITS system calls.
- Collaboration between PDP-10 sites.
- DEC: MACRO, LINK, CROSS, Fortran.
- SAIL: FAIL, SPELL, SUDS, TeX, PUB, GEOMED.
- CMU: Scribe.

<img src="pics/geomed.png" width="27%"></img>
<img src="pics/advent.png" width="30%"></img>
-->

---

### MULTIPROCESSING

<div style="float: left; width: 60%;">
<ul>
<li>PDP-10, timesharing</li>
<li>PDP-6, stand alone</li>
<li>PDP-11, perpiherals</li>
<li>CONS, Lisp machine</li>
<li>CHEOPS, chess machine</li>
<li>GT40, vector display</li>
<li>Imlac, vector display</li>
<li>TT2500, Logo display</li>
<li>Tools and software</li>
</ul>
</div>

<div style="float: right; width: 40%;">
<img src="pics/PDP-11.jpg" width="45%"></img>
<img src="pics/GT40.jpg" width="45%"></img>
<img src="pics/Imlac.jpg" width="45%"></img>
<img src="pics/TT2500.png" width="45%"></img>
</div>

---

### FEATURES AND LIMITATIONS

- PCLSR, PC lusering
- Processes & processors available as files
- The debugger is the user interface
- Application command sets are similar to Emacs
- User-space device drivers
- Real-time scheduling
- Terminal-independent text output
- Just one level of directories
- File names 6+6 characters

---

### DECLINE

- PDP-6s and KA10s scrapped
- KS10 1985
- KL10 shipped to Sweden 1988
- Shut down 1990

<img src="pics/AI-KS10.jpg" width="23%">

+++

### TIMESTAMPS

<img src="pics/timestamps.png">

+++

### VERSIONS

<img src="pics/versions.png">

---

### LEGACY

<div style="float: left; width: 60%;">
<ul>
<li>GNU project</li>
<li>Emacs</li>
<li>Info</li>
<li>WHOIS</li>
<li>Emacs Lisp, Common Lisp</li>
<li>Meta key (from SAIL)</li>
<li>Unix job control</li>
<li>And --More--</li>
</ul>
</div>

<div style="float: right; width: 40%;">
<img src="pics/GNU.jpg" width="40%"><br>
<img src="pics/Emacs.png" width="40%"><br>
<img src="pics/Meta.jpg" width="40%"><br>
</div>

+++

### GNU PROJECT

- Richard Stallman
- Inspired by ITS values
- Free software
- Dover printer

<img src="pics/Dover.jpg" width="40%">

---

### IN THE MEDIA

<div style="float: left; width: 60%;">
<ul>
<li><i>Hackers</i>,<br>book by Steven Levy<br>&nbsp;</li>
<li><i>Hacker's Dictionary</i>,<br>book by Guy Steele<br>&nbsp;</li>
<li><i>Swordfish</i>,<br>movie by Skip Woods<br>&nbsp;</li>
</ul>
</div>

<div style="float: right; width: 40%;">
<img src="pics/Swordfish1.png" width="90%"><br>
<img src="pics/Swordfish2.png" width="90%"><br>
</div>

---

### A NEW HOPE

- ITS running on an emulator 1992
- Put on Internet 2001
- Public ITS distribution
- Unix tools for ITS files and networking
- Restoration 2016

<img src="pics/pdp10x.jpg" width="25%">

---

### REBUILD

- Boot off magtape
- Make file system on disk
- Load ITS and a few binary programs
- Reboot into ITS
- Build system and >300 programs
- Many bug fixes
- Issue tracking
- Continuous integration
- http://github.com/PDP-10/its

+++

### RESTORE

- Search through files on tapes
- Find interesting programs 
- Build from source code
- Debug

<img src="pics/label.jpg" width="30%"></img>

+++

### TODO

- PDP-6 version of ITS
- SHRDLU
- Small ITS
- Emulate more hardware

+++

### LIVING COMPUTERS

- Made a disk image for their KS10
- Installed remotely on a disk emulator
- It's now running at the museum
- Available from Internet

---

### MORE INFORMATION

- <a href="http://github.com/PDP-10/its">github.com/PDP-10/its</a>
- <a href="http://its.victor.se">its.victor.se</a>
- <a href="http://its.pdp10.se">its.pdp10.se</a>
- "Hackers" book

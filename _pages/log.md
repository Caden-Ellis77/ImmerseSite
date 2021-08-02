---
layout: default
title: IMMERSE Log
---

### This Week's Goals (Aug 2)
* **Create other python executables**:
* **Run Valgrind on the basic executables**:
* **Get the C code up to Swig standards, (xilinx libraries)**:
* **Add README's to some pages**:
* **Continue Documenting swig process**:
* **JTAG Bootcamp Page**:
* **Doxygen Documentation Generation**: 


### Week 15: Aug 2, 2021

* **Monday**: 
* **Tuesday**: 
* **Wednesday**: 
* **Thursday**: 
* **Friday**: 

### Week 14: July 26, 2021

* **Monday**: Installed valgrind and worked on some memory leaks and segfaults
* **Tuesday**: Fixed one of the segfaults, working on reading a register again. Still all 1's
* **Wednesday**: Finally read the register and id code
* **Thursday**: Added all options to the jtag_read_reg.py
* **Friday**: Working on other executables, starting with full config


### Week 13: July 19, 2021

* **Monday**: Troubleshooting the _jcm.so
* **Tuesday**: Fixing a few more files so they are up to swig stantards. 
* **Wednesday**: Figured out the dependency trees to wrap everything in swig to read a register. SWIG finally compiled.
* **Thursday**: Trying to get the read register to work, got back all 1's but the rest of the steps before it seemed to work. I maybe figured out a shorter way to compile
* **Friday**: Out for the Holiday

### Week 12: July 12, 2021

* **Monday**: Travel
* **Tuesday**: Travel
* **Wednesday**: Still working on the .i files. I cannot get GenericJTAGDevice to work when "jcm" is imported. The only thing I have gotten to work so far is the JCMJTAGHardware. 
* **Thursday**: Catching up on a class
* **Friday**: Got the GenericJTAGDevice working after running a make clean and rewriting the _jcm.so, but then the JCMHardware didn't work. Still figuring out why.

### Week 11: July 05, 2021

* **Monday**: Holiday
* **Tuesday**: Travel
* **Wednesday**: Travel
* **Thursday**: Vacation
* **Friday**: Vacation

### Week 10: June 28, 2021

* **Monday**: Finished the setup.py generation, working on fixing the xilinx library so that it is SWIG worthy
* **Tuesday**: Chip Camp
* **Wednesday**: Chip Camp
* **Thursday**: Chip Camp
* **Friday**: Worked on .i file problems

### Week 9: June 21, 2021

* **Monday**: Continued working in getting the JTAGDevice error to go away, removing JTAGDevice on my own branch to see if it will fix it
* **Tuesday**: Did not come in
* **Wednesday**: Got Swig to make a JTAG Hardware object
* **Thursday**: Working on "build_swig_importer.py" Script
* **Friday**: Finished the "jcm.i" file, wrapping up the setup.py file

### Week 8: June 14, 2021

* **Monday**: Vacation
* **Tuesday**: For the life of me I cannot get ssh working again.
* **Wednesday**: Full Config, Immerse Meeting, Broader Impacts Meeting, Bootcamp Training
* **Thursday**: FINALLY figured out the ssh problem and documented it. Started working on the Swig build
* **Friday**: Compiled the apps and jtag directories on the JCM to make sure they work after the git pull. Fixed the warnings in the swig build but getting the "no delete_JTAGDevice" error still. Started reading SWIG documentation. 

### Week 7: June 7, 2021

* **Monday**: Working on Pull request
* **Tuesday**: Refactored Clock scanner to work with shifts
* **Wednesday**: Full Config, Immerse Meeting, Broader Impacts Meeting, Bootcamp Training
* **Thursday**: Submitted pull request, ssh problems :(
* **Friday**: Vacation

### Week 6: May 31, 2021

* **Monday**: Holiday
* **Tuesday**: Working on full config 
* **Wednesday**: Full Config, Immerse Meeting, Broader Impacts Meeting, Bootcamp Training
* **Thursday**: Got the full config and Clock rate scanner to FINALLY work. 
* **Friday**: Testing the clock scanner and full config for pull request

### Week 5: May 24, 2021

* **Monday**: Did not get to come in
* **Tuesday**: Significant progress on the clock scanner: however ran into the issue where the board would not configure at clock rates between 65-85 MHz so that is hindering progress.
* **Wednesday**: Immerse Meeting, Broader Impacts Meeting, Bootcamp Training
* **Thursday**: Going through the JTAG Library, making questions and cleaning the code
* **Friday**: Going over my questions with Dr. Wirthlin, Debugging the full configure and clock rate hanging issue


### Week 4: May 17, 2021

* **Monday**: Bootcamp meeting. Had a bigger assignment due for my class and had to get taxes done.
* **Tuesday**: Work with fclk. Found more issues with prog. Started documenting code in doxygen in JCMClockControl
* **Wednesday**: Immerse Meeting and Bootcamp
* **Thursday**: Updated the issues with the prog, and got it working with the Nexys board. More progress with clk rate scanner, making it have arguments. JTAG Webpage started. Pathways example requested from Badgr.
* **Friday**: Bootcamp meeting

### Week 3: May 10, 2021

* **Monday**: Sick
* **Tuesday**: Clock Scanner Debugging. Studying the code. Stuggling with extentions and VScode
* **Wednesday**: Mostly meetings. Getting the Bootcamp page set up with student summaries and my outreach presentation.
* **Thursday**: Worked on understanding some of the Xilinx directory, figuring out JPROGRAM and fixing the DONE high issue.
* **Friday**: Learning how the clock rate file works, learning more of the code layout

### Week 2: May 3, 2021

* **Monday**: Working around some bugs for config and prog, trying to figure out how the JCM is getting wedged
* **Tuesday**: Adding issues to the Github and trying to fix them. Setting up new computer
* **Wednesday**: Mostly occupied by the meetings of the day. Setting up new computer
* **Thursday**: Real Progress finally starting on Clock Scanner, getting the init of the program down
* **Friday**: Sick


### Week 1: April 26, 2021

* **Monday**: Introductory meetings, Bootcamp
* **Tuesday**: Presentation Preparation, JTAG Research
* **Wednesday**: Presentation Preparation, JTAG Research
* **Thursday**: Clock Scanner Work, Website Work
* **Friday**: Clock Scanner Work, finding bugs in it


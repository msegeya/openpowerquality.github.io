---
layout: userguide
title: Roadmap
---

# Introduction

We develop OPQ hardware and software technology as a series of "generations", each named by an Oahu surf spot. 

# G1: Pipeline

Our first generation system named after the famous north shore surf break [Banzai Pipeline](http://en.wikipedia.org/wiki/Banzai_Pipeline).

Please see the [G1 Pilot Study](g1-pilot-study.html) for information about this generation of our technology.

# G2: Bowls

Our second generation system is named after the famous south shore surf break [Ala Moana Bowls](http://www.surf-oahu.com/surf_breaks/south_shore/bowls_kaisers.php).

As of July, 2014, we are in the early stages of requirements development and design for Bowls.
 
## OPQBox

Proposed enhancements for OPQBox include:

  1. Upgrade sampling to support IEEE PQ standards, including 256 samples per waveform and locking to 60Hz input.
  2. Internally fused UL listed dual secondary transformer.
  3. Improvements to enclosure design, including: add "Open Power Quality" to box top; provide screws to secure box; provide gasket through box for AC wire.
  4. Incorporate Li-Po battery and update firmware/software to write out waveform when power to device is cut.
  5. Measure THD
  6. Replace Raspberry PI by TI CC3200 (dev kit)
  7. Add 64K EEPROM for nonvolatile memory
  8. Use [KiCad](http://www.kicad-pcb.org/display/KICAD/KiCad+EDA+Software+Suite) for design
  
## OPQHub

Proposed enhancements for OPQHub include:

  1. Update to Bootstrap 3.x.
  2. Update to Play 2.3.
  3. API for external access to public data
  4. Remodularize to separate acquisition from analysis from storage. 
  
## Communication protocol

Proposed enhancements for the communication protocol include:

  1. Support bi-directional communication so that OPQHub can control data sent from OPQBox based upon characteristics of alert.
  
  
  


 
 









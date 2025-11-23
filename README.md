# Posner Cueing Task (MATLAB / Psychtoolbox)

This repository contains a custom implementation of the Posner spatial cueing task.

## 🔍 Task Overview
- Implements standard Posner cueing paradigm with **valid**, **invalid**, and **neutral** cues.
- Includes full experiment flow: instructions, fixation, cue, target, response collection.
- Timing accuracy ensured using Psychtoolbox.
- Data are automatically logged for **RT** and **accuracy** analysis.

## 📁 Repository Contents
- `PosnerCreative.m` — main MATLAB/Psychtoolbox experiment script.
- `ExampleParticipantPosnerData.xlsx` — sample participant dataset (RT + accuracy).
- `.gitignore` — excludes large temp files (MATLAB autosave, `.mat`, `.asv`, etc.)

## 📊 Analysis Compatibility
The output dataset works seamlessly with:
- **JASP** (for raincloud plots, diffusion modeling pre-processing)
- **Python** (pandas, seaborn, EZ-diffusion scripts)
- **MATLAB** (visualization and post-analysis)

## 🧠 Purpose
This experiment was developed as part of Cognitive Science coursework at **IIT Gandhinagar**, demonstrating skills in:
- Experimental design  
- MATLAB scripting  
- Psychtoolbox  
- Reaction-time data analysis  
- EZ-diffusion modelling  


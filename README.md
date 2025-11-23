# Posner Cueing Task (MATLAB / Psychtoolbox)

My implementation of the Posner spatial cueing task.

## Task
- Valid, invalid and neutral cues.
- Each trial: instructions, fixation, cue, target, response.
- Timing handled with Psychtoolbox.
- RT and accuracy are logged for every trial.

## Files
- `PosnerCreative.m`: saved MATLAB data from the task (it is a MAT-file despite the `.m` extension; load it with `load('PosnerCreative.m', '-mat')`).

## Analysis
The RT and accuracy data can be analysed in JASP, Python or MATLAB.

## Context
Made for Cognitive Science coursework at IIT Gandhinagar.

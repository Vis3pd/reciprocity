reciprocity
===========

COMPOSITOR SOFTWARE MOBILE DEVELOPMENT PLATFORM

GOAL: The dedicated Compositor version for three major platforms such as iOS, Android and Windows Phone

Repositories: 

C++ DSP exported code of application from Cycling '74 Gen~ exportcode feature, original Compositor Lite application version 1.0.7 for Windows and Mac, preset files

DEAD LINE:

06.06.2015

Version history:

exportcode v1.7

- Stochastic algorithm of multiplier selector
- Automatic selection of main channel parameters
- Angular frequency connected with multiplier

exportcode v1.6:

- Master antialiasing filter
- Automatic Waveguides tuning

TASKS:

The Android application should be developed first. It is important to consider that a process is NativeActivity with GUI Activity on top of that via JNI.
Technically speaking there should be a communication of Java user interface via JNI to main NativeActivity .cpp file. The user design is important and should be as close to Lite version as possible.
It is two windows: one is main window with Time, Constellation and Planet selectors and the other window is Waveshaping and Window function parameters.
The DSP code changes are minimum to include Activity states of NativeActivity. No changes to the sound generation or processing is intended as it is well developed and programmed.

Please e-mail me at ruslan.yusipov@gmail.com for more details on the project.

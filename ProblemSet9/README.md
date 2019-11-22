# Problem Set 9

Start Date and Time| Due Date and Time | Cut-off Date and Time |
---|---|---|
10:50:00 AM on November 8, 2019 | 11:59:59 PM on November 21, 2019 | 12:00:00 AM on November 29, 2019 |

## Problem 9.1 - Waveform Generation
- Create a file named `ProblemSet9.1.c`.
- Starting with the program `1.SineWave.c` or `2.SawtoothWave.c`, modify the program to generate a triangle wave. 
- Make sure to plot the resulting waveform to see it is indeed a triangle shaped.

## Problem 9.2: Bit Quantization/Reduction Effect
- Implement the bit quantization/reduction effect documented [here](https://www.musicdsp.org/en/latest/Effects/96-bit-quantization-reduction-effect.html).
- You should be using libsndfile to open an existing audio file, copy the audio content to a buffer, and then apply the audio effect.
- After the effect is applied, save the audio buffer to a sound file using libsndfile.

## Problem 9.3: Bass Booster
- Implement the bass booster documented [here](https://www.musicdsp.org/en/latest/Filters/235-bass-booster.html).
- You should be using libsndfile to open an existing audio file, copy the audio content to a buffer, and then apply the audio effect.
- After the effect is applied, save the audio buffer to a sound file using libsndfile.

## Grading Rubric
Description|Grade
---|---:|
All problem sets submitted | 10%
No compilation warning or error| 10%
Clean, understandable, commented, and organized | 10%
Thoroughly documented in README.md | 20%
Correctly implemented | 50%
**Total** | **100%**

## Submission Guideline
- Make sure you have a folder with your name at the root directory of the repository.
- Create a folder name with the right problem set number (i.e. `Problem Set 1`) within the folder that has your name.
- Please follow the example `README.md` file in `Akito van Troyer/Problem Set 1/` for documenting your problem set.
- Commit and push C files and README.md for this problem set into the newly created folder to complete the problem set.

## Submission policy:
- All problem must be submitted to: https://github.com/navreyort/EP-353-FA2019
- Late projects will incur a penalty of 10% for each day it is late.
- Problem sets and projects are due by 11:59:59pm on the date specified
- After 12:00:00am (the next day after the due day), your problem sets/projects is one day late (-10%).
- After the next 12:00:00am cycle (two days after the due day), your problem sets/projects is two days late (-20%).
- Problem sets and projects will not be accepted after 12:00:00am at one week after the deadline

--- 
**Berklee College of Music**  
Electronic Production and Design  
EP-353: Audio Programming in C  
Fall 2019
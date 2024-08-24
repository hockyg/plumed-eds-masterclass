# Masterclass 22.6: EDS module + Coarse-Grained directed simulations

This lesson was given as part of the PLUMED masterclass series in 2022.  It includes:

* Two videos that describe the theory. 
* A series of exercises for you to complete.
* A python notebook that contains a full solution to the exercises.

The flow chart shown below indicates the order in which you should consult the resources.  You can click on the nodes to access the various resources.  Follow the thick black lines for the best results.  The resources that are connected by dashed lines are supplmentary resources that you may find useful when completing the exercise.

This lesson was the sixth masterclass in the 2022 series.

```mermaid
flowchart TB;
  A[ref1] -.-> B[Lecture I];
  B ==> C[instructions];
  C ==> D[Lecture II];
  D --> E[pesmd solutions];
  D --> F[ala2 solutions];
  click A "ref1" "A previous tutorial that introduces the basics of PLUMED syntax";
  click B "video1" "A lecture that was given on April 26th 2022 as part of the plumed masterclass series that introduces you to the exercises in this lesson";
  click C "INSTRUCTIONS.md" "Instructions for the exercise that you are supposed to complete";
  click D "video2" "A lecture that was given on May 2nd 2022 as part of the plumed masterclass series that goes through the solutions to the exercises in the lesson";
  click E "pes_md/pesmd_analysis.ipynb" "A python notebook that contains solutions to the first set of exercises that use pesmd";
  click F "plain_md/ala2_analysis.ipynb" "A python notebook where that contains solutions to the second set of exercises that involve alanine dipeptide";
```

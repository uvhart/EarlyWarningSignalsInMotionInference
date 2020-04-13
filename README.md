# EarlyWarningSignalsInMotionInference
# This project holds the data for the 3 experiments described in the MS "Early Warning Signals in Motion Inference". It has three folders:
1. Exp 1 - under Exp1 folder there is the data of experiment 1.
           Each GS_pair_X folder (where X is the number of the pair) there are the experimental data for each trial in a csv format.
           Each such csv file has the following data for each column: 
           Attacker and Blocker data is on columns containing "As" in the title
           "xAs1": is x axis data of Attacker sensor 1
           "yAs1": is y axis data of Attacker sensor 1
           "zAs1": is z axis data of Attacker sensor 1
           trial -> trial number
           timeA -> time
           SensorRules = {1 -> "Attacker Right Finger",
                          2 -> "Blocker Right Finger", 
                          3 -> "Attacker Right Wrist",
                          4 -> "Attacker Right elbow crease", 
                          5 -> "Attacker Right Shoulder",
                          6 -> "Attacker Left Shoulder", 
                          7 -> "Attacker Torso",
                          8 -> "Attacker Head"}

2. Exp 2 - under DotExperiment there is the data of experiment 2.
           Each folder has separate subject data in 3 subfolders: "FullPath_Block1/", "FullPath_Block2/", "FullPath_Block3/" 
           Each such csv file has the following data for each column:
           trial -> trial number
           time -> time
           DotSensorRules = {" XA " -> "Striker Finger X",
                             " YA " -> "Striker Finger Y", 
                             " ZA " -> "Striker Finger Z",
                             " xB " -> "Blocker Finger X", 
                             " yB " -> "Blocker Finger Y",
                             " zB " -> "Blocker Finger Z" ,
                             " XAsc " -> "Striker Screen Finger X",
                             " YAsc " -> "Striker Screen Finger Y",
                             " ZAsc " -> "Striker Screen Finger Z"};
                             
3. Exp 3 - under Results there is the data of experiment 3.
           The aggregated RT data is stored in a "allRTData.mat" and "allRTData.csv"
           Each folder SX has the data per subject.
           The file "FoldBifurcationModel.mat" has the RT for the dot simulation of the fold transition.
           The file "UncorrelatedTransition.mat" has the RT for the dot simulation of the uncorrelated transition.

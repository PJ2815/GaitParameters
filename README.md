# GaitParameters
A database containing parameters related to the gait of individuals with visual impairments.
Description of Database Organization

This database comprises a total of 32 consolidated databases, distributed into 8 datasets for each of the parameters. Additionally, it includes specific databases for each experiment conducted by each subject, resulting in a total of 35 experiment databases in the set. Each subject has participated in a range of 4 to 5 experiments, including slow walking, fast walking, outdoor walking, and return walking. Therefore, there are a total of 68 databases.

Abbreviations Breakdown: S: Subject V: Velocity SL: Step Length SC: Step Count

The distribution in the "Subjects" commits is organized as follows: Each subject has their commit in which experiments conducted are recorded, categorized as "slow," "fast," "return,". "external", "Outdoor".

The organization of the parameter commit is as follows: Each consolidated file contains data from all subjects, along with their respective experiments and labels corresponding to the parameter in question. However, the information of the subject being evaluated is excluded. For example, if we have a file named "S9V," it encompasses data from all subjects except for subject 9, who is under evaluation.

In the LSTM-based models commit, the LSTM + FCN, LSTM + CNN, & Seq2One models are included.

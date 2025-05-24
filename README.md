Causal Inference Analysis: Estimating the Effect of Growth Mindset Intervention on Student Achievement

The project explores the contrasting beliefs of fixed and growth mindsets. The traditional belief is that intelligence is acquired at birth and cannot be substantially improved over time; referred to as fixed mindset, while the growth mindset proposes that students can acquire knowledge and develop intelligence over time.
Our aim is to assess the causal impact of a “nudge-like intervention designed to promote a growth mindset among high school students, using a synthetic dataset modeled on the National Study of Learning Mindsets (NSLM).

Data Based On: National Study of Learning Mindsets experiment (NSLM) (Yeager et al,2019)

Sample: 10,391 students from U.S. public high schools.

Variables:
y: Student Achievement (Outcome)

z: Growth mindset intervention (Treatment)

Covariates: Student & school-level features (selfrpt, race, gender, fgen, urban ,mindset, test, sch_race, pov, size)

Goal: Estimate the Average Treatment Effect of a growth mindset intervention (z) on student achievement (y).

Results: Based on our results for estimated Average Treatment Effect (ATE) and the associated 95% confidence interval [0.387205 , 0.442271] by
AIPW, we conclude that students who received the growth mindset intervention (z = 1) experienced a statistically significant and positive impact on their academic achievement (y). These findings challenge the traditional fixed mindset belief that intelligence is static by showing that a brief, nudge-like intervention can enhance student performance, consistent with the principles of a growth mindset.

Project summary can be found here:
https://dikshaphuloria.github.io/Causal-Inference/Causal_Inference.nb.html

STEPS TO ACCESS AND RUN THE FILE:

NOTE : Prerequisite - RSTUDIO AS PLATFORM TO RUN THE FILE

1) Download the Causal_Inference.RMD file.
   
2) Download the  data.csv file, make sure both the files are in same directory.
   
3) Launch RSTUDIO and Run Causal_Inference.RMD (make sure to download all necessary libraries)
   
4) Click preview to view the file in HTML format.

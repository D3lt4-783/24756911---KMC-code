# 24756911---KMC-code

This repository contains all code files, directories and analysed datasets used in this project. Namely:
1. RadialDisplacement.mlx
2. RespirationLinearDisplacement_02.mlx
3. mattressControl-v4
 - 3.1 mattressControl-v4.ino
4. RespirationModelAnalysis
 - 4.1 IRSensorData-03.xlsx
 - 4.2 RespirationModelAnalysis-01.R
5. PulseDataAnalysis
 - 5.1 PulseData(1234)-01.xlsx
 - 5.2 PulseDataAnalysis-01.R
6. IndividualPulseData
 - 6.1 PulseData-Pos1-02.csv
 - 6.2 PulseData-Pos2-02.csv
 - 6.3 PulseData-Pos3-01.csv
 - 6.4 PulseData-Pos4-01.csv
 - 6.5 IndivPulseDataAnalysis-02.R
7. IRStartupPlotCode
 - 7.1 IRStartUp(01).xlsx
 - 7.2 StartUp-01.R
8. IRDataCol
 - 8.1 IRDataCol.ino
9. DataColCode
 - 9.1 DataColCode.ino
-------------------------------------------------
1. Is responsible for the calculation of the radial displacement produced using an internal pressure and Lame's thick wall solution. Where the result is found in Section 4.1.2.
2. Is responsible for producing Figure 19: Simulated chest wall displacement vs time graph. which is the general path the stepper motors are programmed to follow.
3. Is the full control loop of the project as seen in Figure 27. Responsible for the control of the motor drivers of the pump and stepper motors. As well as the User interface.
4. Is used to analyse data gathered in Section 5.3 to find the goodness-of-fit metrics and to produce Figures 23 and 24.
5. Is responsible for the exploratory data analysis seen in Section 5.2.1. Analysing the data from all 4 piezo sensors, producing Figures 20 and 21. As well as Table 9.
6. Is responsible for the exploratory data analysis seen in Section 5.2.2. Analysing the data gathered from a single piezo sensor at different positions on the mattress. To produce Figure 22 and Table 10.
7. Is responsible for producing the plot that shows the mattresses start up and shut down procedure during treatment in Figure 24.
8. The code used to collect data from the infrared sensor under the mattress for Section 5.3.
9. The code used to collect data from the piezoelectric sensors on the mattress for Section 5.2.

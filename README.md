# 24756911---KMC-code

This repository contains all code files, directories and analysed datasets used in this project. Namely:
1. RadialDisplacement.mlx
2. RespirationLinearDisplacement_02.mlx
3. ShaftDesign_02.mlx
4. mattressControl-v4
 - 4.1 mattressControl-v4.ino
5. RespirationModelAnalysis
 - 5.1 IRSensorData-03.xlsx
 - 5.2 RespirationModelAnalysis-01.R
6. PulseDataAnalysis
 - 6.1 PulseData(1234)-01.xlsx
 - 6.2 PulseDataAnalysis-01.R
7. IndividualPulseData
 - 7.1 PulseData-Pos1-02.csv
 - 7.2 PulseData-Pos2-02.csv
 - 7.3 PulseData-Pos3-01.csv
 - 7.4 PulseData-Pos4-01.csv
 - 7.5 IndivPulseDataAnalysis-02.R
8. IRStartupPlotCode
 - 8.1 IRStartUp(01).xlsx
 - 8.2 StartUp-01.R
9. IRDataCol
 - 9.1 IRDataCol.ino
10. DataColCode
 - 10.1 DataColCode.ino
-------------------------------------------------
1. Is responsible for the calculation of the radial displacement produced using an internal pressure and Lame's thick wall solution. Where the result is found in Section 4.1.2.
2. Is responsible for producing Figure 19: Simulated chest wall displacement vs time graph. which is the general path the stepper motors are programmed to follow.
3. Is responsible for the calculation of all measurements and saftey factors used for the Shaft Design.
4. Is the full control loop of the project as seen in Figure 27. Responsible for the control of the motor drivers of the pump and stepper motors. As well as the User interface.
5. Is used to analyse data gathered in Section 5.3 to find the goodness-of-fit metrics and to produce Figures 23 and 24.
6. Is responsible for the exploratory data analysis seen in Section 5.2.1. Analysing the data from all 4 piezo sensors, producing Figures 20 and 21. As well as Table 9.
7. Is responsible for the exploratory data analysis seen in Section 5.2.2. Analysing the data gathered from a single piezo sensor at different positions on the mattress. To produce Figure 22 and Table 10.
8. Is responsible for producing the plot that shows the mattresses start up and shut down procedure during treatment in Figure 24.
9. The code used to collect data from the infrared sensor under the mattress for Section 5.3.
10. The code used to collect data from the piezoelectric sensors on the mattress for Section 5.2.

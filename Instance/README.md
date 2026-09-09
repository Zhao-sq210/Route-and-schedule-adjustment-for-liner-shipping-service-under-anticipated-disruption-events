This folder contains the input data for all computational instances used in the paper.
The experiments include four cases (Case 1–Case 4). For each case, 50 stochastic scenarios are generated based on the random parameter Random delay time, with each scenario defining one computational instance together with the corresponding common input parameters. Case 1 also includes additional instances generated for the sensitivity analyses with different parameter settings.

File organization.
The instance files are organized into subfolders according to the case and parameter settings. For example: "C1_0.5_0.4_350_21000" denotes a Case 1 setting with:
0.5 = Unit freight revenue for shipping demand;
0.4 = Unit penalty rate for unserved demand;
350 = Bunker fuel price;
21000 = Vessel capacity.
The corresponding coefficients of the bunker consumption function are provided in the Excel files.

Each parameter-setting folder contains 51 Excel files. For example: Case1.xlsx contains the parameters common to the 50 instances;
C1_0.5_0.4_350_21000_w1.xlsx–C1_0.5_0.4_350_21000_w50.xlsx contain the input data for the 50 instances, where w1–w50 identify the corresponding stochastic scenarios.

Thus, each instance is defined by the common parameters in Case1.xlsx and the corresponding Random delay time in the w-specific Excel file.

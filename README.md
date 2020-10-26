# electrical_regression

Electrical Grid Stability Simulated Data Data Set 


Attribute Information:

11 predictive attributes, 1 non-predictive(p1), 2 goal fields: 
1. tau[x]: reaction time of participant (real from the range [0.5,10]s). Tau1 - the value for electricity producer. 
2. p[x]: nominal power consumed(negative)/produced(positive)(real). For consumers from the range [-0.5,-2]s^-2; p1 = abs(p2 + p3 + p4) 
3. g[x]: coefficient (gamma) proportional to price elasticity (real from the range [0.05,1]s^-1). g1 - the value for electricity producer. 
4. stab: the maximal real part of the characteristic equation root (if positive - the system is linearly unstable)(real) 
5. stabf: the stability label of the system (categorical: stable/unstable) 




Relevant Papers:

Arzamasov, Vadim, Klemens BÃ¶hm, and Patrick Jochem. 'Towards Concise Models of Grid Stability.' Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm), 2018 IEEE International Conference on. IEEE, 2018
(Section V-A) 



dataset link:'https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+'






Electrical Grid Stability Simulated Data Data Set 
Download: Data Folder, Data Set Description

Abstract: The local stability analysis of the 4-node star system (electricity producer is in the center) implementing Decentral Smart Grid Control concept.

Data Set Characteristics:  

Multivariate

Number of Instances:

10000

Area:

Physical

Attribute Characteristics:

Real

Number of Attributes:

14

Date Donated

2018-11-16

Associated Tasks:

Classification, Regression

Missing Values?

N/A

Number of Web Hits:

49086


Source:

-- Creator and donor: Vadim Arzamasov (vadim.arzamasov '@' kit.edu), 
Department of computer science, 
Karlsruhe Institute of Technology; 
Karlsruhe, 76131; Germany 
-- Date: November, 2018 

taken from uci ml repository




# Automation-of-Reserving

Reserving is a fundamental aspect of actuarial science, allowing insurers to accurately estimate future claims liabilities, ensuring financial stability and regulatory compliance. Over time, various reserving techniques have been developed, including the Chain Ladder, Bornhuetter-Ferguson, Cape Cod, Frequency-Severity, and Case Outstanding methods. Each technique is tailored to specific business lines and claims characteristics.

This research examines the Case Outstanding Reserving technique, particularly in short-tailed business lines, where claims are settled quickly with less uncertainty. The study evaluates how well the Case Outstanding method aligns with actual claims outcomes and identifies any inherent limitations in its application.

Data from 151 insurance companies was collected and analyzed, with reserve estimates calculated using the Case Outstanding method. These estimates were then compared to real claims data observed over a designated period. The analysis provided insights into the method's accuracy and reliability across various short-tailed business lines, highlighting potential areas where adjustments could improve its predictive power.

Given the time-consuming nature of manual reserving processes in Excel, the research also introduced an automated solution. A Python class was developed to perform reserve calculations, validate estimates against actual claims, and generate detailed Excel reports for all 150 companies. This automation significantly reduced the time and effort involved, offering a streamlined and reproducible workflow for actuaries and insurance analysts.

The results showed that while the Case Outstanding technique is generally effective for short-tailed business lines, its accuracy depends on factors like case reserve quality, claim reporting patterns, and portfolio homogeneity. The automation framework also demonstrated potential for scaling analysis across larger datasets, contributing to the improvement of actuarial reserving practices. Future work may focus on expanding the framework to incorporate additional reserving methods and integrate machine learning techniques for more accurate predictions.




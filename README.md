## Software for  LCA using IO analysis
This site explains how to use the MLCArel package and the IOtable module.

#### Shinsuke Sakai   
 Emeritus Professor, The University of Tokyo, Japan   
 Visiting Professor, Yokohama National University, Japan

 ### Overview
The package MLArel provides the function for general-purpose matrix-based LCA analysis and LCA based on IO analysis. Algorithm for sensitivity analysis using perturbation method is based on the theory shown by Sakai and Yokoyama[1]. Should any required packages be missing during execution, please install them accordingly.

[1][Shinsuke Sakai and Koji Yokoyama. Formulation of sensitivity analysis in life cycle assessment using a
perturbation method. Clean technologies and environmental policy, Vol. 4, No. 2, pp. 72–78, 2002.](https://link.springer.com/article/10.1007/s10098-002-0150-2) 

### Procedure
1. Install package "MLCArel" using pip command.
1. Create a folder to store inventory data. As an example, the folder named 'IOexam' is already created.
1. Save the related data in csv format to be analyzed in that folder.
1. Import PyMLCA module using 'from MLCArel import IOtable as iot' command.
1. Create an instance to manage the analysis using 'iot=pm.IOtreat()' command.
1. From here on, use the created instance to perform the intended analysis.

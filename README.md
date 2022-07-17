# Analysis of Gradient Descent and BCGD methods
This repository contains the implementation of the _Optimization for DataScience_ @ UniPD first homework, about the efficiency of block coordinates gradient descent methods.
## Introduction
Gradient descent is a method to find the minimum of a function, however during the course multiple version of it are being shown.  
In this analysis, multiple version will be compared, to check the convergence rate of them both in time and in iterations.
## Implementation
In order to implement the project, it's been created a Python Jupyter notebook, containing all the code to recreate any result reported.  
Everything can be found inside the `project` folder
## Report
The essay contains the details of the homework, all the calculations needed to develop the project, and all the explanation on why things are being chosen to be done in this way.
## Animations
In order to visually see what the algorithms actually do, in the notebook there is the code to generate some GIF at each iteration of all the methods, and the HTML file given is supposed to help to see the difference between them.  

Following are some examples:

| Current label                                                                     | Current classification                                                                   | Current loss                                                                           |
|-----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| ![Gradient descent](project/gif/gd.gif?raw=true)                                  | ![Gradient descent](project/gif/gd_binary.gif?raw=true)                                  | ![Gradient descent](project/gif/loss_gd.gif?raw=true)                                  |
| ![Gradient descent improved](project/gif/gd_improved.gif?raw=true)                | ![Gradient descent improved](project/gif/gd_improved_binary.gif?raw=true)                | ![Gradient descent improved](project/gif/loss_gd_improved.gif?raw=true)                |
| ![Gradient descent heavy ball](project/gif/gd_hb.gif?raw=true)                    | ![Gradient descent heavy ball](project/gif/gd_hb_binary.gif?raw=true)                    | ![Gradient descent heavy ball](project/gif/loss_gd_hb.gif?raw=true)                    |
| ![Gradient descent accelerated](project/gif/gd_accelerated.gif?raw=true)          | ![Gradient descent accelerated](project/gif/gd_accelerated_binary.gif?raw=true)          | ![Gradient descent accelerated](project/gif/loss_gd_accelerated.gif?raw=true)          |
| ![Gradient descent exact line search](project/gif/gd_exact.gif?raw=true)          | ![Gradient descent exact line search](project/gif/gd_exact_binary.gif?raw=true)          | ![Gradient descent exact line search ](project/gif/loss_gd_exact.gif?raw=true)         |
| ![BCGM Cyclic](project/gif/bcgd_cyclic.gif?raw=true)                              | ![BCGM Cyclic](project/gif/bcgd_cyclic_binary.gif?raw=true)                              | ![BCGM Cyclic](project/gif/loss_bcgd_cyclic.gif?raw=true)                              |
| ![BCGM Random](project/gif/bcgd_random.gif?raw=true)                              | ![BCGM Random](project/gif/bcgd_random_binary.gif?raw=true)                              | ![BCGM Random](project/gif/loss_bcgd_random.gif?raw=true)                              |
| ![BCGM Gauss-Southwell](project/gif/bcgd_gs.gif?raw=true)                         | ![BCGM Gauss-Southwell](project/gif/bcgd_gs_binary.gif?raw=true)                         | ![BCGM Gauss-Southwell](project/gif/loss_bcgd_gs.gif?raw=true)                         |
| ![BCGM Gauss-Southwell exact line search](project/gif/bcgd_gs_exact.gif?raw=true) | ![BCGM Gauss-Southwell exact line search](project/gif/bcgd_gs_exact_binary.gif?raw=true) | ![BCGM Gauss-Southwell exact line search](project/gif/loss_bcgd_gs_exact.gif?raw=true) |
|                                                                                   |                                                                                          |                                                                                        |


If you clone/download the repository and open the README file, you will be able to compare the animations since they will be synchronized, this might not happen if you are watching this from Github
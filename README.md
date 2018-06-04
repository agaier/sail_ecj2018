# sail
Source code for the Surrogate-Assisted Illumination (SAIL) algorithm, as
described in: 

"Data-Efficient Design Exploration through Surrogate-Assisted Illumination"
to be published in Evolutionary Computation.


This repository will not be updated and is only here in the interest of reproducibility and transparency. For the latest SAIL code, checkout: https://github.com/agaier/sail


Produced using

    Matlab R2017b


Required MATLAB Toolboxes:

* Parallel Computing (for parallel speed ups)

* Statistics and Machine Learning (for Sobol sequence)


Includes:
    GMPL  Version 4.1, Rasmussen & Nickisch (help gpml)


Required Software:

    Airfoil domain:

         XFOIL low Rn airfoil design and analysis code 
        
        (raphael.mit.edu/xfoil/)
        
        
    Velo domain:
        
        OpenFOAM computation fluid dynamics simulator (version 2.4.0)
        
        (https://openfoam.org/download/2-4-0-ubuntu/)

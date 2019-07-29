# Automated method for segmentation of four posterior white matter pathways
This code allows to segment the Posterior Arcuate, the Middle Longitudinal Fasciculus, the Vertical Occipital Fascicuclus and the Temporo-Parietal Connection. See Bullock et al. (2019) Brain Strcutre and Function for more details. 


### Authors
- Dan Bullock (iisdanbul@gmail.com)

### Funding associated with this project 
[![NSF-BCS-1636893](https://img.shields.io/badge/NSF_BCS-1636893-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1636893)
[![NSF-BCS-1734853](https://img.shields.io/badge/NSF_BCS-1734853-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1734853)
[![NSF-AOC-1916518](https://img.shields.io/badge/NSF-AOC-1916518-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1916518)
[![NIH-NIMH-5T32MH103213](https://img.shields.io/badge/NIH-NIMH-5T32MH103213-blue.svg)](http://grantome.com/grant/NIH/T32-MH103213-04)

### References
If you sue this code please cite the following articles.
- Bullock, D., Takemura, H., Caiafa, C. F., Kitchell, L., McPherson, B., Caron, B., and Pestilli, F. (2019) Associative white matter tracts in the posterior human brain with different degrees of investigative attention. Brain Structure and Function. DOI:10.1007/s00429-019-01907-8
- Caiafa C. and Pestilli, F. (2017) Multidimensional encoding of brain connectomes.  Scientific Reports. DOI: 10.1038/s41598-017-09250-w
- Yeatman J.D., Dougherty R.F., Myall N.J., Wandell B.A., Feldman H.M. (2012). Tract Profiles of White Matter Properties: Automating Fiber-Tract Quantification. PLoS One.
- Pestilli, F., Yeatman, J. Rokem, A., Kay, K. and Wandell, B. (2014) Evaluation and statistical inference in living connectomes. Nature Methods. DOI:10.1038/nmeth.3098.

### Dependencies
- Matlab 2018 or later: https://www.mathworks.com/products/matlab.html
  - VISTASOFT: https://github.com/vistalab/vistasoft
  - ENCODE: https://github.com/brain-life/encode
  - MBA: https://github.com/francopestilli/mba
  - AFQ: https://github.com/yeatmanlab/AFQ

### Sample Datasets
Sample datasets can be downloaded from Brainlife.io using [Brainlife's CLI](https://github.com/brain-life/cli).

```
npm install -g brainlife
bl login
mkdir input
bl dataset download 5a0e604116e499548135de87 && mv 5a0e604116e499548135de87 input/track
bl dataset download 5a0dcb1216e499548135dd27 && mv 5a0dcb1216e499548135dd27 input/dtiinit
```

## Getting started
TO use this code in MatLab open the <function name> and ...

## Inputs
<INPUTS FILES>

## Output

All output files will be generated under the current working directory (pwd). The main output of this code is a file called `TBA.mat`. This file contains following object.

```
fg = 

    field1: 'name'
    field2: 'name'
```

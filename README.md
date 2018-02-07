# IRS_normalization
An exploration of internal reference scaling (IRS) normalization in isobaric tagging proteomics experiments.

The method was first described here:
> Plubell, D.L., Wilmarth, P.A., Zhao, Y., Fenton, A.M., Minnier, J., Reddy, A.P., Klimek, J., Yang, X., David, L.L. and Pamir, N., 2017. Extended multiplexing of tandem mass tags (TMT) labeling reveals age and high fat diet specific proteome changes in mouse epididymal adipose tissue. Molecular & Cellular Proteomics, 16(5), pp.873-890. 

## Contents:
three jupyter notebook files (R kernel)
* understanding_IRS.ipynb is Part 1 (normalizations)
* statistical_testing.ipynb is Part 2 (edgeR testing)
* statistical_testing_ratios.ipynb is Part 3 (taking ratios and using limma)
* [statistical_testing_ratios_v2.ipynb has modified limma calls]

Data from Kahn, et al.
* iovs_58-13-55-s01.csv

R scripts used in exploration of data analysis steps with RStudio

Added HTML renderings of the notebooks for those who just want to see the analysis steps and figures:
* understanding_IRS.html is Part 1 (needs the png file)
* irs_diagram.png is an image for the understanding_IRS.html script
* statistical_testing.html is Part 2
* statistical_testing_ratios.html is Part 3
* [statistical_testing_ratios_v2.html has modified limma calls]

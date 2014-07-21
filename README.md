Python-Kstest2
==============

Pythonic implementation of MATLAB's kstest2

This script performs the KS-Test and is derived from Matlab's kstest2. It returns the H value, P value and the KS-test statistic. As input it requires two unsorted vectors, the alpha value and the type of test i.e. smaller, larger or unequal. The script is invoked with the following:

$ python pyKstest.py <vec1> <vec2> <alpha>, <test type: smaller, larger, unequal>

It can also be called from an another Python script by first placing this script in your project directory and then importing it from your wrapper script:

import pyKstest as kstest2

[H1,P1,KS1] = kstest.main(vec1,vec2,alpha, 'larger')

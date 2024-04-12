# Critical-Node-Problem
We provide instances on the critical node problem in in the QLP file format for a multistage setting. 

The instances originate from the paper
[*A. Baggio, M. Carvalho, A. Lodi, A. Tramontani, "Multilevel Approaches for the Critical Node Problem", Operations Research, 2021*](https://pubsonline.informs.org/doi/abs/10.1287/opre.2020.2014)

The authors of that paper already provided the raw data of their instances here: https://github.com/mxmmargarida/Critical-Node-Problem

For more details we refer to: 
* a preprint of our paper [LINK](https://arxiv.org/abs/2210.11132)
* information regarding the file format [LINK](https://yasolqipsolver.github.io/yasol.github.io/About_Yasol/#the-qlp-file-format)
* our solver [LINK](https://github.com/MichaelHartisch/Yasol)

## Instances
In the folder MCN_raw/, you find the raw data of the original instances, as they also can be found here: https://github.com/mxmmargarida/Critical-Node-Problem

The folders MCN_Poly/ and MCN_DecisionDependent/ contain instances in the QLP-file format. They are dividided into the basic (two-stage) instances, and the multistage instances. The instances in the Basic/ folder are the same problem as solved in the oroginal paper. The instances in the Multistage/ folder are adapted versions of the basic instances.

## Solver
To run the instances given in the QLP-file format you can use our solver Yasol: https://github.com/MichaelHartisch/Yasol

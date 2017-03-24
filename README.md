# WannierTools [![Build Status](https://travis-ci.org/quanshengwu/wannier_tools.svg?branch=master)](https://travis-ci.org/quanshengwu/wannier_tools)  [![codecov](https://codecov.io/gh/quanshengwu/wannier_tools/branch/master/graph/badge.svg)](https://codecov.io/gh/quanshengwu/wannier_tools)

[**More examples in Wiki for WannierTools**](https://github.com/quanshengwu/wannier_tools/wiki)

[**Full documentation for WannierTools**](http://quanshengwu.github.io/wannier_tools/)

![](https://lh3.googleusercontent.com/-NGkPcF7iUDY/Vy-34BbICBI/AAAAAAAAASY/e2YiWSnQJD4jpHh-kDWceThf2jKKSGAxwCCo/s526/wannier_tools-logo-purple.jpg)

**Authorship**
-------------

Written by QuanSheng Wu in Fortran 90 (wuquansheng@gmail.com  wuq@phys.ethz.ch)

Copyright (c) 2016 QuanSheng Wu and ShengNan Zhang. All rights reserved.

**Pull down the package**
-------------------------

git clone https://github.com/quanshengwu/wannier_tools.git

**Brief introductions**
-------------------------
We present an open-source software package WannierTools, a tool for investigation of novel topological materials. This code works in the tight-binding framework, which can be generated by another software package Wannier90 . It can help to classify the topological phase of a given materials by calculating the Wilson loop, and can get the surface state spectrum which is detected by angle resolved photoemission (ARPES) and in scanning tunneling microscopy (STM) experiments . It also identifies positions of Weyl/Dirac points and nodal line structures, calculates the Berry phase around a closed momentum loop and Berry curvature in a part of the Brillouin zone(BZ).

**License and Citation**
-------------------------
WannierTools was released under GPL V3. If you use our code for your research, please cite it properly, 
like  “ The surface spectrums or Berry curvature, Wilson loop, Weyl/Dirac points, Nodal line,  Chirality et al.
are calculated by the software package WannierTools~\cite{WannierTools}. "

For the surface state calculation, please also cite {Sancho1985}. 

For the Wilson loop calculation, please also cite PhysRevB.84.075119 and PhysRevB.83.035108.

Reference 

```
@article{Wu2017,
archivePrefix = {arXiv},
arxivId = {1703.07789},
author = {Wu, QuanSheng and Zhang, ShengNan and Song, Hai-Feng and Troyer, Matthias and Soluyanov, Alexey A.},
eprint = {1703.07789},
title = {{WannierTools: An open-source software package for novel topological materials}},
url = {http://arxiv.org/abs/1703.07789},
year = {2017}
}
```

Sancho1985: [Highly convergent schemes for the calculation of bulk and surface Green functions, M P Lopez Sancho, J M Lopez Sancho, J M L Sancho and J Rubio, J.Phys.F.Met.Phys.15(1985)851-858](http://iopscience.iop.org/article/10.1088/0305-4608/15/4/009/meta;jsessionid=A349A81FE38B2B55DB42032F6792B275.c1)

**Publications**
----------------
* Phonon-Induced Topological Transition to a Type-II Weyl Semimetal, Lin-Lin Wang, Na Hyun Jo, Yun Wu, QuanSheng Wu, Adam Kaminski, Paul C. Canfield, Duane D. Johnson, [arXiv:1703.07292] (https://128.84.21.199/abs/1703.07292)
* Unique topological surface states of full-Heusler topological crystalline insulators, Anh Pham and Sean Li, [Phys. Rev. B 95, 115124 (2017)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.95.115124)
* Weyl and Line Nodes in Topological Superconductor: CaSn , Sunny Gupta, Rinkle Juneja, Ravindra Shinde, Abhishek K. Singh, [arXiv:1612.03610](https://arxiv.org/abs/1612.03610)
* Saddle-like topological surface states on the TT'X family of compounds (T, T' = Transition metal, X= Si, Ge) Bahadur Singh, Xiaoting Zhou, Hsin Lin, Arun Bansil, [arXiv:1703.04048] (https://arxiv.org/abs/1703.04048)
* Hidden Weyl points in centrosymmetric paramagnetic metals, Dominik Gresch, **QuanSheng Wu**, Georg W Winkler and Alexey A Soluyanov, [New J. Phys. 19 (2017) 035001](https://doi.org/10.1088/1367-2630/aa5de7)
* Topological semimetal to insulator quantum phase transition in the Zintl compounds Ba2X(X=Si,Ge), Ziming Zhu, Mingda Li, and Ju Li, [Phys. Rev. B 94, 155121](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.155121), (2016)
* Heavy Weyl fermion state in CeRu4Sn6, Yuanfeng Xu, Changming Yue, Hongming Weng, Xi Dai, [arXiv:1608.04602](http://arxiv.org/abs/1608.04602),Phys. Rev. X 7, 011027 (2017) 
* Triple Point Topological Metals Ziming Zhu, Georg W. Winkler, **QuanSheng Wu**, Ju Li, Alexey A. Soluyanov  [arXiv:1605.04653](http://arxiv.org/abs/1605.04653) Phys. Rev. X 6, 031003 – Published 7 July 2016.
* Fermi arcs and their topological character in the candidate type-II Weyl semimetal MoTe2, A. Tamai, **Q. S. Wu**, I. Cucchi, F. Y. Bruno, S. Ricco, T.K. Kim, M. Hoesch, C. Barreteau, E. Giannini, C. Bernard, A. A. Soluyanov, F. Baumberger  [arXiv:1604.08228](http://arxiv.org/abs/1604.08228)   [Phys. Rev. X 6, 031021 (2016)](http://journals.aps.org/prx/abstract/10.1103/PhysRevX.6.031021)
* Nodal-chain metals, Tomáš Bzdušek, **QuanSheng Wu**, Andreas Rüegg, Manfred Sigrist, Alexey A. Soluyanov [arXiv:1604.03112, 2016 ](https://arxiv.org/abs/1604.03112) [Nature (2016) doi:10.1038/nature19099](http://www.nature.com/nature/journal/vaop/ncurrent/full/nature19099.html).
* Surface states and bulk electronic structure in the candidate type-II Weyl semimetal WTe2, F. Y. Bruno, A. Tamai, **Q. S. Wu**, I. Cucchi, C. Barreteau, A. de la Torre, S. McKeown Walker, S. Riccò, Z. Wang, T. K. Kim, M. Hoesch, M. Shi, N. C. Plumb, E. Giannini, A. A. Soluyanov, F. Baumberger [arXiv:1604.02411, 2016](https://arxiv.org/abs/1604.02411)
* Topological Phases in InAs1−xSbx: From Novel Topological Semimetal to Majorana Wire, Georg W. Winkler, **QuanSheng Wu**, Matthias Troyer, Peter Krogstrup, Alexey A. Soluyanov [arxiv:1602.07001, 2016](https://arxiv.org/abs/1602.07001)
* Type-II Weyl semimetals, Alexey A. Soluyanov,	Dominik Gresch,	Zhijun Wang,	**QuanSheng Wu**,	Matthias Troyer,	Xi Dai	& B. Andrei Bernevig, [Nature 527, 495–498 (26 November 2015)](http://www.nature.com/nature/journal/v527/n7579/full/nature15768.html) 

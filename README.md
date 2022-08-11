# vector_leptoquark

The repository contains several vector leptoquark models for collider studies. We have uploaded both Universal FeynRules Output (UFO) files for MC simulators and the generating FeynRules files (\*.fr) for the models. 

The model [vleptoquark_tta_UFO](./vleptoquark_tta_UFO) contains a vector leptoquark (vul) couples to top and taus. The Standard Model quantum number (SU(3), SU(2), Y) for the vector leptoquark is (3, 1, 5/3). Its decay channel is vul > t ta+. The model [vleptoquark_te_tmu_UFO](./vleptoquark_te_tmu_UFO) contains a vector leptoquark with the same Standard Model quantum number. But instead, it couples to top and electrons, and top and muons. The decay channel is vul > t e+ and t mu+. 
The coupling ``tkappa`` and ``xkappa`` <sup>1</sup> is the coupling between the vector leptoquark and gluons and gluon-primes, respectively. We set both parameters to be 0 by considering unitarity of the leptoquark production. More details on the physics of these vector leptoquark models can be found in [JHEP 10 (2017) 097](https://link.springer.com/article/10.1007/JHEP10(2017)097) and [JHEP 01 (2019) 132](https://link.springer.com/article/10.1007%2FJHEP01%282019%29132).

The model [vleptoquark_QL_triplet_UFO](./vleptoquark_QL_triplet_UFO) contains a triplet of vector leptoquarks (V1, V2, V3) that couples to Q^dag (3rd generation) and L (1st/2nd/3rd generation). Its Standard Model quantum number is (3 bar, 3, -2/3). The parameter y13/y23/y33 controls the coupling between the leptoquark triplet and the 1st/2nd/3rd generation leptons and the 3rd generation quarks.

The model [sleptoquark_UE_UFO](./sleptoquark_UE_UFO) contains a scalar leptoquark (S1) that couples to U^c (1st/2nd/3rd generation) and E^c (1st/2nd/3rd generation). Its Standard Model quantum number is (3 bar, 1, 1/3). The parameter yue/yumu/yuta/yce/ycmu/ycta/yte/ytmu/ytta controls the coupling between the leptoquark and the 1st/2nd/3rd generation leptons and the 1st/2nd/3rd generation quarks.

Please acknowledge [JHEP 10 (2017) 097](https://link.springer.com/article/10.1007/JHEP10(2017)097) and [JHEP 01 (2019) 132](https://link.springer.com/article/10.1007%2FJHEP01%282019%29132) if you used the repository models.

For any questions on the models, please contact Martin Schmaltz (schmaltz@bu.edu) or Yiming Zhong (ymzhong@kicp.uchicago.edu).

<a>[1]</a>: ``xkappa`` is denoted as ``kappa_s`` in equation C.5 of [JHEP 10 (2017) 097](https://link.springer.com/article/10.1007/JHEP10(2017)097).

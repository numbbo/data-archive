---
layout: default
permalink: /bbob-mixint/
nav_order: 6
title: bbob-mixint
dataDir: "https://numbbo.github.io/data-archive/data-archive/bbob-mixint/"
---

# Algorithm data sets for the bbob-mixint test suite  #
---


<!-- Make tables sortable -->
<script type="text/javascript" src="{{site.baseurl}}/sort-table.js"></script>

In the table below, you will find all official algorithm data sets on the bbob-mixint test suite, 
together with their year of publication, the authors, and related PDFs for each data set. Links to the 
source code to run the corresponding experiments/algorithms are provided whenever available.

To sort the table, simply click on the table header of the corresponding column.


{:.js-sort-table}
|     Number      |                       Algorithm Name                         | Year |   Author(s)    |                        link to data                                    | related PDFs, source code, and remarks                                                                                                                                                                                 |
|:---------------:|:-------------------------------------------------------------|:----:|:--------------:|:----------------------------------------------------------------------:|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| mixint-000      | CMA-ES-pycma                                                 | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/CMA-ES-pycma.tgz)       | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                                                                                                                                     |
| mixint-001      | DE-scipy                                                     | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/DE-scipy.tgz)           | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                                                                                                                                     |
| mixint-002      | RANDOMSEARCH                                                 | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/RANDOMSEARCH.tgz)       | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                                                                                                                                     |
| mixint-003      | TPE-hyperopt                                                 | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/TPE-hyperopt.tgz)       | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                                                                                                                                     |
| mixint-004      | CMA-ESwM                                                     | 2022 | Hamano et al.  | [data]({{ page.dataDir }}/2022/CMA-ESwM_Hamano.tgz)                    | CMA-ES with Margins as presented in [BBOB-2022 paper](https://dl.acm.org/doi/pdf/10.1145/3520304.3534043)                                                                                                              |
| mixint-005      | [DE-CoBi-r1-L](https://github.com/ryojitanabe/de_bbobmixint) | 2024 | Tanabe         | [data]({{ page.dataDir }}/2024/DE-CoBi-r1-L_Tanabe.zip)                | DE with parameter control method in CoBiDE, rand/1 strategy, and Lamarckian repair as benchmarked in [GECCO-2024 paper](https://arxiv.org/abs/2404.03303), [source code](https://github.com/ryojitanabe/de_bbobmixint) |
| mixint-006      | [DE-j-r2-B](https://github.com/ryojitanabe/de_bbobmixint)    | 2024 | Tanabe         | [data]({{ page.dataDir }}/2024/DE-j-r2-B_Tanabe.zip)                   | DE with parameter control method in jDE, rand/2 strategy, and Baldwinian repair as benchmarked in [GECCO-2024 paper](https://arxiv.org/abs/2404.03303), [source code](https://github.com/ryojitanabe/de_bbobmixint)    |
| mixint-007      | [DE-NO-r1-B](https://github.com/ryojitanabe/de_bbobmixint)   | 2024 | Tanabe         | [data]({{ page.dataDir }}/2024/DE-NO-r1-B_Tanabe.zip)                  | DE with no parameter control method, rand/1 strategy, and Baldwinian repair as benchmarked in [GECCO-2024 paper](https://arxiv.org/abs/2404.03303), [source code](https://github.com/ryojitanabe/de_bbobmixint)        |



<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}"/>

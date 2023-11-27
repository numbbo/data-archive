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
|     Number      |   Algorithm Name  | Year |   Author(s)    |                        link to data                                    | related PDFs, source code, and remarks                                                                         |
|:---------------:|:------------------|:----:|:--------------:|:----------------------------------------------------------------------:|----------------------------------------------------------------------------------------------------------------|
| mixint-000      | CMA-ES-pycma      | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/CMA-ES-pycma.tgz)       | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                             |
| mixint-001      | DE-scipy          | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/DE-scipy.tgz)           | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                             |
| mixint-002      | RANDOMSEARCH      | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/RANDOMSEARCH.tgz)       | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                             |
| mixint-003      | TPE-hyperopt      | 2019 | Tušar et al.   | [data]({{ page.dataDir }}/2019-gecco-benchmark/TPE-hyperopt.tgz)       | [GECCO paper](https://hal.inria.fr/hal-02067932/file/2019_GECCO_Mixint_Suites.pdf)                             |
| mixint-004      | CMA-ESwM          | 2022 | Hamano et al.  | [data]({{ page.dataDir }}/2022/CMA-ESwM_Hamano.tgz)                    | CMA-ES with Margins as submitted to BBOB-2022                                                                  |


<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}"/>

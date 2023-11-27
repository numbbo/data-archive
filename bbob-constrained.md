---
layout: default
permalink: /bbob-constrained/
nav_order: 7
title: bbob-constrained
dataDir: "https://numbbo.github.io/data-archive/data-archive/bbob-constrained/"
---

# Algorithm data sets for the bbob-constrained test suite  #
---

<!-- Make tables sortable -->
<script type="text/javascript" src="{{site.baseurl}}/sort-table.js"></script>

In the table below, you will find all official algorithm data sets on the bbob-constrained test suite, 
together with their year of publication, the authors, and related PDFs for each data set. Links to the 
source code to run the corresponding experiments/algorithms are provided whenever available.

To sort the table, simply click on the table header of the corresponding column.


{:.js-sort-table}
|     Number      |   Algorithm Name  | Year |      Author(s)       |                        link to data                                    | related PDFs, source code, and remarks                                                                                                                                                       |
|:---------------:|:------------------|:----:|:---------------------|:----------------------------------------------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| constrained-000 | RandomSearch-5    | 2022 | Dufossé              | [data]({{ page.dataDir }}/2022/RandomSearch-5_Dufosse.tgz)             | [source code](https://github.com/numbbo/coco/blob/master/code-experiments/build/python/example_experiment2.py)                                                                               |
| constrained-001 | AL1-CMA-ES        | 2022 | Dufossé and Atamna   | [data]({{ page.dataDir }}/2022/AL1-CMA-ES_Dufosse.tgz)                 | CMA-ES with Augmented Lagrangian fitness, pycma version, parameter setting 1 as compared by Dufosse and Atamna for BBOB-2022                                                                 |
| constrained-002 | AL2-CMA-ES        | 2022 | Dufossé and Atamna   | [data]({{ page.dataDir }}/2022/AL2-CMA-ES_Dufosse.tgz)                 | CMA-ES with Augmented Lagrangian fitness, pycma version, parameter setting 2 as compared by Dufosse and Atamna for BBOB-2022                                                                 |
| constrained-003 | AL3-CMA-ES        | 2022 | Dufossé and Atamna   | [data]({{ page.dataDir }}/2022/AL3-CMA-ES_Dufosse.tgz)                 | CMA-ES with Augmented Lagrangian fitness, pycma version, parameter setting 3 (default) as compared by Dufosse and Atamna for BBOB-2022                                                       |
| constrained-004 | AL4-CMA-ES        | 2022 | Dufossé and Atamna   | [data]({{ page.dataDir }}/2022/AL4-CMA-ES_Dufosse.tgz)                 | CMA-ES with Augmented Lagrangian fitness, pycma version, parameter setting 4 as compared by Dufosse and Atamna for BBOB-2022                                                                 |
| constrained-005 | BPepsMAg          | 2022 | Hellwig and Beyer    | [data]({{ page.dataDir }}/2022/BPepsMAg_Hellwig.tgz)                   | Matrix Adaptation Evolution Strategy with restarts and BIPOP strategy, using up to three different constraint handling techniques, as compared by Hellwig and Beyer for BBOB-2022            |
| constrained-006 | COBYLA            | 2022 | Dufossé and Atamna   | [data]({{ page.dataDir }}/2022/COBYLA_Dufosse.tgz)                     | Constrained Optimization BY Linear Approximation (implemented in SciPy as a wrapper around Powell's fortran code) compared by Dufosse and Atamna for BBOB-2022                               |
| constrained-007 | epsMAg            | 2022 | Hellwig and Beyer    | [data]({{ page.dataDir }}/2022/epsMAg_Hellwig.tgz)                     | Matrix Adaptation Evolution Strategy, using up to three different constraint handling techniques, as compared by Hellwig and Beyer for BBOB-2022                                             |
| constrained-008 | fmincon           | 2022 | Hellwig and Beyer    | [data]({{ page.dataDir }}/2022/fmincon_Hellwig.tgz)                    | default fmincon from Matlab2021b, as compared by Hellwig and Beyer for BBOB-2022                                                                                                             |




<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}"/>

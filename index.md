---
layout: default
permalink: /
nav_order: 1
title: Home
---

# COCO data archives  #
---
Welcome to the website of the benchmarking data archives of the [COCO](https://numbbo.github.io/coco/) (Comparing Continuous Optimizers) platform. 

This website provides the official benchmarking data archives from numerical benchmarking experiments run on the COCO platform. For each test suite we provide a listing of the official data sets with additional information like authors, links to papers, source code etc. Data sets for the following test suites are available: 

* [bbob]({{ site.baseurl }}{% link bbob.md %}): 24 single-objective noiseless functions, 250+ data sets
* [bbob-noisy]({{ site.baseurl }}{% link bbob-noisy.md %}): 24 single-objective noisy functions, 40+ data sets
* [bbob-biobj]({{ site.baseurl }}{% link bbob-biobj.md %}): 55 bi-objective functions, 30+ data sets
* [bbob-largescale]({{ site.baseurl }}{% link bbob-largescale.md %}): large-scale version of the 24 bbob functions (dimension up to 640), 10+ data sets
* [bbob-mixint]({{ site.baseurl }}{% link bbob-mixint.md %}): mixed-integer versions of the 24 bbob functions, 8 data sets
* [bbob-constrained]({{ site.baseurl }}{% link bbob-constrained.md %}): 54 constrained functions with varying number of (non-linear) constraints, 9 data sets
* [sbox-cost]({{ site.baseurl }}{% link sbox-cost.md %}): box-constrained version of 24 bbob functions, 2 data sets

These data can be directly used "by name" through the [cocopp Python module](https://pypi.org/project/cocopp).

<h2>Related links</h2>
<ul><li><a href="https://numbbo.github.io/ppdata-archive">
    postprocessed data of these archives for browsing</a>
</li><li><a href="https://github.com/numbbo/coco/blob/master/howtos/publish-a-dataset-howto.md">
  how to submit a data set</a>
</li><li>
  <a href="https://github.com/numbbo/coco/blob/master/code-postprocessing/cocopp/archiving.py">
  how to create and use COCO data archives with the <tt>cocopp.archiving</tt> Python module</a>
</li></ul>

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}"/>

---
layout: default
permalink: /
nav_order: 1
title: Home
---

# COCO data archives  #
---
Welcome to the website of the benchmarking data archives of the [COCO](https://github.com/numbbo/coco) (Comparing Continuous Optimizers) platform. 

Besides providing the official archives from numerical benchmarking experiments, run on the COCO platform and available through its [cocopp Python module](https://pypi.org/project/cocopp), this website also provides lists of these official data sets with additional information like authors, links to papers, source code etc. Right now, data sets for the following test suites are available:

* [bbob]({{ site.baseurl }}{% link bbob.md %}): 24 single-objective noiseless functions
* [bbob-noisy]({{ site.baseurl }}{% link bbob-noisy.md %}): 24 single-objective noisy functions
* [bbob-biobj]({{ site.baseurl }}{% link bbob-biobj.md %}): 55 bi-objective functions
* [bbob-largescale]({{ site.baseurl }}{% link bbob-largescale.md %}): large-scale version of the 24 bbob functions (dimension up to 640)
* [bbob-mixint]({{ site.baseurl }}{% link bbob-mixint.md %}): mixed-integer versions of the 24 bbob functions
* [bbob-constrained]({{ site.baseurl }}{% link bbob-constrained.md %}): 54 constrained functions with varying number of (non-linear) constraints


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

---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b><code> UQpy</code> : Uncertainty Quantification with python</b></h4>
<a href="https://github.com/SURGroup/UQpy" target="_blank"><button class="btn btn-primary btn-sm">GITHUB</button></a>
<a href="https://doi.org/10.1016/j.jocs.2020.101204" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>
<a href="https://uqpyproject.readthedocs.io/en/latest/" target="_blank"><button class="btn btn-danger btn-sm">DOCUMENTATION</button></a>

<code><b>UQpy</b></code> is an _open_ _source_ general-purpose Python toolbox developed by members of the <a href="https://github.com/SURGroup" target="_blank">SURG</a> group in the <a href="https://engineering.jhu.edu/case/" target="_blank">Department of Civil and Systems Engineering</a> at the Johns Hopkins University for modeling uncertainty in the simulation of physical and mathematical systems.  The code is organized as a set of modules centered around core capabilities in Uncertainty Quantification (UQ). The modules are distinct, but are designed to be easily extensible (new capabilities can be easily added and integrated into the code) and to easily call one another. Version <code><b>4.0</b></code> was released on <strong>April 2022</strong> and contains the following modules:
- <code>Dimension Reduction</code>
- <code>Distributions</code>
- <code>Inference</code>
- <code>Reliability</code>
- <code>RunModel</code>
- <code>Sampling</code>
- <code>Sensitivity</code>
- <code>Stochastic process</code>
- <code>Surrogates</code>
- <code>Transformations</code>
- <code>Utilities</code>
</div>
<div class="col-md-3 col-sm-12">
  <img src="{{site.url}}{{site.baseurl}}/images/respic/UQpy_logo.jpg" width="175px "/>
</div>
</div>
</div>

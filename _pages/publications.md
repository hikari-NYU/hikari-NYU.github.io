---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Selected papers
{% bibliography --query @selected %}
{: .no-index}
</div>

<div class="jumbotron">
### Refereed conference proceedings
{% bibliography --query @inproceedings[author~=^Ma. W] %} 
{: .no-index}  
{% bibliography --query @inproceedings[author~=^.+Ma. W] %} 
{: .no-index}
</div>

<div class="jumbotron">
### Refereed journal articles
{% bibliography --query @article %}
{: .no-index}
</div>

<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
{: .no-index}
</div>

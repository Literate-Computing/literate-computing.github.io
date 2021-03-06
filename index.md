---
title: <span class="text-info">L</span>iterate <span class="text-info">C</span>omputing <span class="text-info">for R</span>eproducible <span class="text-info">I</span>nfrastructure
description: <small><small><b><span class="text-danger">Jupyter</span> based Toolset for an Infrastructure Engineer - <span class="text-danger">文芸的機械化</span>のススメ</b></small></small>
link_ja: index-ja.html
layout: home
---

## What is <span class="text-info">LC4RI</span>?
It is as essential as to share and communicate about infrastructure design and elaborated workflows with participants as to actually automate complex operations. 
<span class="text-info">Literate Computing for Reproducible Infrastructure</span> is an approach both to describe automated operations as live code and to share predicted and reproducible outcomes among technical and non-technical alike in the form of narrative stories.  We utilize <span class="text-info">Jupyter Notebook</span> for sharing the reproducible experience. 
Operational engineering and DevOps should be one of the distinctive application areas for Jupyter.

#### "Automated Operation" [機械化] ≠ "Automation" [自働化]
<small>
We want to accomplish traceability and reproducibility in engineering operations. For those primary purposes, we utilize computational narrative tools, i.e., Jupyter Notebook. Every operation is described with no doubt and can be automated. Automated operation is always along with humans in the loop and bound up with a situation. It is something different from distilled automation, which tends to result in an anesthetizing effect 
<i><small><small><span class="text-muted">([Nicholas InCarr. The Glass Cage](https://image.slidesharecdn.com/jupytercon-masatani-170825211000/95/jupytercon-2017-collaboration-and-automated-operation-as-literate-computing-for-reproducible-infrastructure-26-638.jpg))
</span></small></small></i>
.
Automated operation is a partnership between humans and machines and augments our ability to learn and expertise.
</small>


#### Collaboration and Communication 
<small>
For reproducibility and resilience for long-term sustainability, it is crucial not only to share knowledge but also to share reproducible experience participating in both tech and non-tech alike. Narrative stories allow collaborative communication between experts and novices to accumulate infrastructure knowledge and operational experience within an operation team. Moreover, it is efficient to share an understanding of how infrastructure is usable and really works between tech ops and non-tech users. Narrative stories also help communicate with users about how services are delivered and customized, considering reproducibility.
</small>

## Literate Computing tools
Literate Computing Tools are our enhancements to Jupyter for achieving the following goals:
- <small>
Giving awareness where you are; the cells are colored depending on their statuses. You can see how an operation is in progress and whether it has been succeeded. Light Cyan, Linen, and Pink represent “running”, “finished successfully” and “finished with errors” respectively.
</small>
- <small>
Preventing miss-operation; once a cell has been executed, it “freezes” against unintended execution. Frozen cells will not be executed nor edited until those will be unfrozen.
</small>
- <small>
A good operational outlook; as an enhancement for collapsible headings, collapsed code cells underneath are represented as bricks. The number of bricks represents operational complexities. Plus, you can run through whole bricks (collapsed code cells) with one click as a routine procedure. Color changes of bricks also represent the progress.
</small>
- <small>
Assure traceability; infrastructure operation can generate massive output lines. LC_wrapper kernel summarizes output lines, and simultaneously all original output lines are saved into an individual file with a timestamp at each execution. You can investigate the total output and compare it with previous results for reviewing.
</small>

## Try the Demo

You can start the Notebook server on port 8888 with the following command.

```
docker run -it --rm -p 8888:8888 niicloudoperation/notebook:latest
```

<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_docker" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

You can login the Notebook server with the authentication token in the startup message.

## Jupyter Extensions

{% capture run_through %}

[LC_run_through Extension](https://github.com/NII-cloud-operation/Jupyter-LC_run_through)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_run_through" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

{% include youtube.html id='pkzE_nwtEKQ' %}
{% endcapture %}
{% include topic.html content=run_through %}

{% capture lc_wrapper %}

[LC_wrapper Kernel](https://github.com/NII-cloud-operation/Jupyter-LC_wrapper)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_wrapper" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

{% include youtube.html id='-28XG7aHYY8' %}
{% endcapture %}
{% include topic.html content=lc_wrapper %}

## Other Extensions

- [multi_outputs](https://github.com/NII-cloud-operation/Jupyter-multi_outputs)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-multi_outputs" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [nblineage](https://github.com/NII-cloud-operation/Jupyter-LC_nblineage)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_nblineage" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [Jupyter-LC_index](https://github.com/NII-cloud-operation/Jupyter-LC_index)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-LC_index" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [i18n_cells](https://github.com/NII-cloud-operation/Jupyter-i18n_cells)
<a class="github-button" href="https://github.com/NII-cloud-operation/Jupyter-i18n_cells" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

<dl class="dl-horizontal">
  <dt>...</dt>
  <dd>...</dd>
</dl>
## Notebooks for Reproducible Infrastructure

- [Literate-computing-Basics](https://github.com/NII-cloud-operation/Literate-computing-Basics)
<a class="github-button" href="https://github.com/NII-cloud-operation/Literate-computing-Basics" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [Literate-computing-Hadoop](https://github.com/NII-cloud-operation/Literate-computing-Hadoop)
<a class="github-button" href="https://github.com/NII-cloud-operation/Literate-computing-Hadoop" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>
- [Literate-computing-Elasticsearch](https://github.com/NII-cloud-operation/Literate-computing-Elasticsearch)
<a class="github-button" href="https://github.com/NII-cloud-operation/Literate-computing-Elasticsearch" data-icon="octicon-star" data-show-count="true" aria-label="Star on GitHub">Star</a>

{% raw %}
<font color="MidnightBlue">
<h2><i>Memo</i></h2>
</font>
{% endraw %}

The following video presents early practices back to late 2015 and 2016Q1.  Since then, we have been developed *Literate Computing Tools* as enhancement of [Jupyter](https://jupyter.org/).

{% capture the_beginning %}
{% include youtube-w.html id='T309jbgdaqI' %}
{% endcapture %}

{% include topic.html content=the_beginning %}


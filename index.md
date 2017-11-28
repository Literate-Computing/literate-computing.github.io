---
title: Literate Computing for Reproducible Infrastructure
description: LC4RI - Toolset for an Infrastructure Engineer
link_ja: index-ja.html
layout: home
---

## What is LC4RI?
It is as important to share infrastructure design and elaborated workflows with participants as to actually automate complex operations. Literate Computing for Reproducible Infrastructure is an approach both to describe automated operations as live code and to share predicted and reproducible outcomes among technical and non-technical alike in the form of narrative stories.  We utilize Jupyter Notebook for shareing reproducible experience.

## Literate Computing tools
The goals for Literate Computing tools are:

- Preventing miss-operation; once a cell has been executed, it “freezes” against unintended execution. Also you can “lock” cells for unintended modification.
- Adding a perspective into a notebook; markdown’s hierarchy is collapsible as document according to your focus. However, embedded cells underneath are represented as dots and run through with a click as a routine procedure.


## Try the Demo

You can start the Notebook server on port 8888 with the following command.

```
docker run -it --rm -p 8888:8888 niicloudoperation/notebook:latest
```

You can login the Notebook server with the authentication token in the startup message.

## Jupyter Extensions

{% capture lc_wrapper %}
### LC_wrapper kernel

[Python2/Python3 kernel with LC_wrapper](https://github.com/NII-cloud-operation/Jupyter-LC_wrapper)

{% include youtube.html id='-28XG7aHYY8' %}
{% endcapture %}
{% include topic.html content=lc_wrapper %}


{% capture run_through %}
### LC_run_through

[LC_run_through](https://github.com/NII-cloud-operation/Jupyter-LC_run_through)

{% include youtube.html id='pkzE_nwtEKQ' %}
{% endcapture %}
{% include topic.html content=run_through %}


### Other Extensions

- [multi_outputs](https://github.com/NII-cloud-operation/Jupyter-multi_outputs)
- [nblineage](https://github.com/NII-cloud-operation/Jupyter-LC_nblineage)
- [i18n_cells](https://github.com/NII-cloud-operation/Jupyter-i18n_cells)

## Notebooks

- [Literate-computing-Basics](https://github.com/NII-cloud-operation/Literate-computing-Basics)
- [Literate-computing-Hadoop](https://github.com/NII-cloud-operation/Literate-computing-Hadoop)
- [Literate-computing-Elasticsearch](https://github.com/NII-cloud-operation/Literate-computing-Elasticsearch)

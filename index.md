---
title: Literate Computing for Reproducible Infrastructure
description: LC4RI - Toolset for an Infrastructure Engineer
link_ja: index-ja.html
layout: home
---

## What is LC4RI?

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

- [Python2/Python3 kernel with LC_wrapper](https://github.com/NII-cloud-operation/Jupyter-LC_wrapper)
- [multi_outputs](https://github.com/NII-cloud-operation/Jupyter-multi_outputs)
- [run_through](https://github.com/NII-cloud-operation/Jupyter-LC_run_through)
- [nblineage](https://github.com/NII-cloud-operation/Jupyter-LC_nblineage)
- [i18n_cells](https://github.com/NII-cloud-operation/Jupyter-i18n_cells)

## Notebooks

- [Literate-computing-Basics](https://github.com/NII-cloud-operation/Literate-computing-Basics)
- [Literate-computing-Hadoop](https://github.com/NII-cloud-operation/Literate-computing-Hadoop)
- [Literate-computing-Elasticsearch](https://github.com/NII-cloud-operation/Literate-computing-Elasticsearch)

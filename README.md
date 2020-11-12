# 2020_AJP_Tang_et_al_panc_tissue_char

This repository contains [Jupyter Notebooks](http://jupyter.org/) and their dependencies to allow recreation of our results. 
The data was analyzed using [SAS](http://www.sas.com/en_us/home.html). We also provide a html version of the notebook.
Jupyter Notebooks support a growing number of [languages](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels)


## Getting started

LINUX users with SAS licence can follow these [instructions](https://github.com/sassoftware/sas_kernel). 

Windows or Mac users who do not have a SAS license can install the free [SAS University Edition](www.sas.com/en_us/software/university-edition.html#), which is a virtual machine that can be run with [VirtualBox](https://www.virtualbox.org/), which is available for free as well. Both run on all operating systems.
Once SAS University Edition is added to VirtualBox a shared folder can be setup. This folder must be named pancreas_size! The repository has the correct file structure already. So cloning this repository to any place in your file system and then pointing to pancreas_size will allow SAS to access the necessary files. 
After starting the SAS University Edition a browser can be pointed to http://localhost:18888 which should look like this: ![Alt](localhost18888.png)

Windows users who have a SAS license can install the SAS kernal [https://github.com/sassoftware/sas_kernel] and use the notebook directly.  

## Using this repository

For those who don't want to install SAS University Edition but still want to have a look at the code and its output we provided an html version of the notebook. Github does not render html though, hence we recommend to download the html files and to open them in a browser.



# Refugee
Raw Data and rough python code for Migration Crisis in EU  
All the code, and a reproducible environment file to quckly set up on other systems.  
Code is till 3rd June,2021   

**Prerequisites**\
Miniconda (https://docs.conda.io/en/latest/miniconda.html)   
or   
Anaconda (https://docs.anaconda.com/anaconda/install/)

**Install**

     git clone https://github.com/TheCount11/Refugee.git   
     cd Refugee  
     conda env create --name envname --file=refugee.yml  

Alternate **Install** in case of issues:

     git clone https://gitlab.vgiscience.de/ad/mobile_cart_workshop2020.git \
     cd mobile_cart_workshop2020\
     #not necessary, but recommended :\
     conda config --env --set channel_priority strict\
     conda env create -f environment_default.yml  

And then 

    conda activate workshop_env\
    conda install -c conda-forge 'ipywidgets=7.6.*' \
              jupyter_contrib_nbextensions \
              jupyter_nbextensions_configurator \
              jupyterlab \
              jupytext \
              'nbconvert=5.6.1'   
Install packages as and when required  
*Use ^ instead of / in Windows*

    


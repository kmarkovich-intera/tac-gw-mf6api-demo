# INTERA Groundwater Modeling TAC
# MODFLOW6 API Demo
 
The USGS recently developed groundbreaking MODFLOW6 functionality with the MODFLOW6 Application Programming Interface (API). In essence, the API allows other programs (such as a python script) to control MODFLOW and interactively change variables without having to modify the source code. This has implications for building or modfying new boundary condition packages when the existing packages are not sufficient, as well as coupling MODFLOW6 to other models. See Hughes et al. (2022) in the repository for more information on how the API was developed as well as some use cases.

This tutorial aims to give a basic introduction and provide a few example uses, but it is undoubtedly the tip of the iceberg. It assumes a basic understanding of python, jupyter notebooks, and MODFLOW6. Git is also a plus, but not necessary. 

## Installation Instructions

**Download the tutorial repository:**

You can do this in one of two ways. 
 - (1) (easier) Download the repo as a zip file from here: [tac-gw-mf6api-demo](https://github.com/kmarkovich-intera/tac-gw-mf6api-demo/). Unzip the folder and work from there.
 - (2) (recommended; requires familiarity with git). Install git following directions here: [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). Sign into your INTERA GitHub account, then clone the repo [tac-gw-mf6api-demo](https://github.com/kmarkovich-intera/tac-gw-mf6api-demo/).

**Install Python and dependencies:**
 - If you have already installed Python using Anaconda, you can skip this step. If not, install [Anaconda](https://www.anaconda.com/products/individual) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html), if you prefer )
 - If you are using __Windows__: go to the start menu and open "Anaconda prompt". An anaconda command line window will open. On __Linux__ or __MacOS__, just use the standard terminal. Navigate to the course repo folder on your machine. You can accomplish this by typing "cd *your folder path*" and pressing < enter >. Replace *your folder path* with the path to the course material folder on your computer.
 - Next, type `conda env create -f environment.yml`. This will create an anaconda environment called "gmdsitut" and install the python dependencies required for this course. It may take a while. Should you wish, you can inspect the *environment.yml* file in the repo folder to see what dependecies are being installed.

**Start jupyter notebook**
You will need to do this step any time you wish to open one of the course notebooks.
To start up the jupyter notebook:
- Windows: open the Anaconda prompt and type `conda activate gmdsitut`
- Mac/Linux: open a termainal and type `conda activate gmdsitut`
- Then navigate to folder where you downloaded the course materials repo and type `jupyter notebook`
A jupyter notebook instance should start within the course repo flder. Using the browser, you can now navigate to the "notebooks" folder and open one.
 


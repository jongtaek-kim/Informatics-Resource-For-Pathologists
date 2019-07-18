## THESE LESSONS ARE ENCOURAGED AND WILL BE PROVIDED TO THE CEDARS-SINAI PATHOLOGY TRAINEES.  THE LESSONS ARE FLEXIBLE AND CAN BE TAYLORED TO THE TRAINEES' NEEDS.


## 1. Pathology Informatics Essentials for Residents [(PIER)](https://www.apcprods.org/m-pier)  

Usually taken during the pathology residency/fellowship. PIER is a research-based instructional resource developed by the Association of Pathology Chairs, Association for Pathology Informatics, and College of American Pathologists that presents training topics, implementation strategies and resource options for PRODS and faculty to effectively provide informatics training to their residents and meet ACGME informatics milestone requirements. PIER is also an effective resource for aspiring specialists to develop [prerequisite pathology informatics knowledge and skills](https://www.pathologyinformatics.org/pier_and_api.php) prior to advanced training or fellowships. The lecture pdf files for Essential 1 to Essential 4 are available above. The videos that accompany these lectures will be available in the shared drive. 


## 2. Introduction to Linux Command Line 
### Setting Up Your Computer for Programming Tutorials
#### Install Miniconda which contains the conda package manager and comes with Jupyter Notebook and several other tools that are useful for working in Python with scientific data. Once Miniconda is installed, you can use the conda command to install any other packages. For example:
```bash
$ conda install pandas
```
&nbsp; 
#### A) If you have Windows Operating System, download the Miniconda installer for Windows [(here)](https://docs.conda.io/en/latest/miniconda.html). Instructions are [(here)](https://conda.io/projects/conda/en/latest/user-guide/install/windows.html). Be sure to download the Python 3.7 version!
&nbsp;  
#### B) If you have Mac OS, download the Miniconda installer for Mac [(here)](https://docs.conda.io/en/latest/miniconda.html). Instructions are [(here)](https://conda.io/projects/conda/en/latest/user-guide/install/macos.html). Be sure to download the Python 3.7 version! After downloading, run the following in your terminal:
```bash
$ bash Miniconda3-latest-MacOSX-x86_64.sh
```
&nbsp;  
#### C) If you have Linux OS such as Ubuntu or Debian, download the Miniconda installer for Linux [(here)](https://docs.conda.io/en/latest/miniconda.html). Instructions are [(here)](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html#install-linux-silent). Be sure to download the Python 3.7 version! After downloading, run the following in your terminal:
```bash
$ bash Miniconda3-latest-Linux-x86_64.sh
```
&nbsp;  
## 3. Introduction to NGS Variant Calling Tutorial

<p align="center">
  <img width="600" height="400" src="https://github.com/jongtaek-kim/Informatics-Resource-For-Pathologists/blob/master/docs/images/variant.calling.png">
</p>

We will use a Docker container for this tutorial.  A Docker container is a standalone, executable package of software that includes all the tools needed to run an application code.  


<p align="center">
  <img width="300" height="200" src="https://github.com/jongtaek-kim/Informatics-Resource-For-Pathologists/blob/master/docs/images/Docker-logo-011.png">
</p>


A Docker container was created for this tutorial. Instruction for installing Docker is [(here)](https://docs.docker.com/v17.12/install/). Make sure to install the right one (either Windows or Mac). 

For Linux OS, Docker can be installed from the terminal.
```bash
$ sudo apt-get update
$ sudo apt-get install docker-ce docker-ce-cli containerd.io
```



After installing Docker, pull the container we'll use for this tutorial. 


```bash
$ docker pull jtk622/intro_ngs:1
```

&nbsp;  


&nbsp;  







## 4. RNA-Seq Gene Expression Analysis with R Programming

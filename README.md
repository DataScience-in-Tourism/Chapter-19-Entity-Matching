# Chapter 19: Entity Matching
## http://www.datascience-in-tourism.com/

***Ivan Bilan***
* Ivan Bilan - TrustYou

**Abstract**
Entity matching is the approach of finding different records of the same real-world entity across single or multiple databases or data sources. In this chapter, the theoretical foundations of this approach and how it is applied in various data science tasks will be presented. The chapter will also focus on a specific task that many data science companies in the tourism branch have to face, namely, to correctly map hotel entities across different sources such as review websites or client and internal databases. 

## Setup
To automatically create a conda environment (using Anaconda3) with Python 3.7, run the following command:
```
make build_venv
```

If you are having issues with Anaconda, you can setup the requirements into a Python environment management system of your choice by using:
```
pip install -r requirements.txt
```

In order to be able to use some dependencies of this demo, you have to install additional requirements described under: 
https://github.com/openvenues/pypostal. 

To start the demo, open Jupyter Lab:
```
conda activate entity_matching_demo
jupyter lab
```
and navigate to `Entity_Matching_Tutorial.ipynb`

## Data Overview
This tutorial includes a small sample dataset that will allow to run the tutorial in this repository. The hotels contained 
in the dataset are generated automatically and do not refer to real-world hotels.

The dataset includes 84 sample hotel record pairs already annotated:
* 55 record pairs are true matches
* 29 record pairs are negative matches

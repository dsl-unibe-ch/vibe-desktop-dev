# vibe-desktop
Repository for the VIBE Desktop

## About VIBE
VIBE is a joined collaboration between the Microscopy Imaging Center (MIC) and Data Science Lab (DSL) at the university of Bern. Our goal is to provide a virtual desktop for image analysis which runs on UBELIX [https://www.id.unibe.ch/hpc], university of Bern's HPC based on SLURM[https://slurm.schedmd.com/], Open OnDemand[https://openondemand.org/] and Apptainer[https://apptainer.org/].

## The vibe-desktop Repository
This repository contains all information required to build the VIBE desktop, a virtual desktop environment based on Rocky Linux [https://rockylinux.org] and the XFCE desktop environment [https://xfce.org/]. It is containerized using the Apptainer [https://apptainer.org/] container environment.

## Repository Structure
This repsoitory holds the Apptainer Definition Files for building the desktop container inside the 'apptainer-build' folder.
The configuration to deploy the VIBE Desktop as Open OnDemand application is located inside the 'ood-vibe' folder. There are multiple versions based on different base systems.

## Building the Apptainer container
Build the container using the provided Apptainer Definition File (.def)

## Deploying the Open OnDemand App
The configuration files for Open OnDemand make the VIBE desktop container available to users.

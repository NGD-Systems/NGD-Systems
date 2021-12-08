NGD Systems is a company of Southern California that is responsible for the first commercial Computational Storage Device.
The Newport family of nvme based SSDs are the first to deliver a fully functional, autonomous, embedded Computational System integrated to the Storage device.

NGD Systems' family of Computational Storage Devices are also the highest capacity SSDs of the Industry and offers the 
most efficient Watts/TB Storage device.

Web Site: www.NGDSystems.com
*****************************

This repository contains SW images and Applications for the NGD Systems' Computational Storage Device family.

If you have any questions about the products or need to contact us, send an e-nmail to:
hermes.costa@ngdsystems.com

* Table of contents:
*********************
* NGD-Systems/NGD-Systems

    Brief introduction and description
    
*******************************************  
* NGD-Systems/imageanalizer

    Computer Vision Demo Application based on Microsoft Azure.
    The demo runs on the Newport CSD and searches for image files inside the storage space.
    When found, the image is analized using Microsoft's Computer Vision library and the image description is sent to the Cloud.
    
********************************************************************************************************************************  
* NGD-Systems/install-docker

    The Docker installation script for the Newport CSD. Contains the scripts and needed files that will install the Docker run-time and Cli on the 
    Newport OS.
    
********************************************************************************************************************************
* NGD-Systems/In-Situ_Control

    The Newport control script.
    The script starts the TCP-over-NVMe driver and sets the network configuration that will enable the CSD to comunicate with the Host machine and
    to the internet.
    The script also set's up the configuration for the OCFS2 cluster and starts the services mounting the shared partitions.
    
*********************************************************************************************************************************

.. CCEP Lab user documentation documentation master file, created by
   sphinx-quickstart on Tue Feb 15 17:05:36 2022.

.. include:: glob_header_msg.rst

.. figure:: /art/logo_cceplab.png
   :align: center	
   :width: 80%
	
|
	
CCEP Lab is a toolbox dedicated to the processing and analysis of Cortico-Cortical Evoked Potentials (CCEPs).
It is a standalone implementation of the processing pipeline developed during the course of the `Functional Brain Tractography project <https://f-tract.eu/>`_ (F-TRACT) (2014 - 2023),
which has been further enhanced and expanded by adding new features and processing capabilities.

.. admonition:: The Functional Brain Tractography project
	
   The F-TRACT project studied large-scale human brain connectivity by collecting and analyzing a large amount of low-frequency stimulation SEEG data obtained from clinical centers across Europe,
   leading to the development of probabilistic atlases. 
	
CCEP Lab enables the extraction, visualization and characterization of CCEPs. Although it was developed for processing SEEG recordings, it may also be used to analyze any type of electrically induced iEEG responses.
CCEP Lab is currently available on Windows and Linux based operating systems. 


.. raw:: html

   <center>	
   <video width="680"  poster="_static/art/video_placeholder.png" controls>
   <source type="video/mp4">
   Your browser does not support the video tag.
   </video>
   </center>

|
	
User documentation
**********************

CCEP Lab documentation encompasses all aspects of the toolbox, including installation, data processing, visualizations, and external tools that can be utilized to explore and further analyze the data.

All user documentation is accessible from the table of contents.
It contains the following sections:

   * **Quick Start**: A brief introduction to the software's overall purpose and usage, for those looking to get started quickly.
   * **Before you start**: Covers the installation procedure and essential information to be aware of before using CCEP Lab to help you avoid potential issues. 
   * **Basics**: Provides an overview of the toolbox, including all its features and how to use them. 
   * **Advanced**: Addresses specific aspects of the toolbox, usually when you have particular questions you need to resolve.
   * **Tutorials**: Tutorials that illustrate common use cases.
	  
.. toctree::
   :hidden:   
   
   > > > > > > > Quick Start < < < < < < <<glob_empty_page>  

.. toctree::
   :caption: Before you start 
   :hidden:   
   
   Requirements and installation<glob_empty_page>
   BIDS datasets and data curation<glob_empty_page>
   
.. toctree::
   :caption: Basics 
   :hidden:   
   
   Overview<glob_empty_page>
   Processing data<glob_empty_page>
   Results and visualizations<glob_empty_page>
   
.. toctree::
   :caption: Advanced 
   :hidden:   
   
   Atlases<glob_empty_page>
   Processing pipeline<glob_empty_page>
   File location<glob_empty_page>
   Table filtering<glob_empty_page>
   API<glob_empty_page>
   Third-party apps<advanced/ADVANCED_third_party_apps.rst>
    
.. toctree::
   :caption: Tutorials 
   :hidden:   
   
   Process a subject from start to finish<glob_empty_page>
   Export CCEP features into Excel tables<glob_empty_page>
   Generate connectivity atlases<glob_empty_page>
   Define and use sets of parameters<glob_empty_page>
   Visualize CCEPs using HiBoP<glob_empty_page>
   Visualize timeseries using AnyWave<glob_empty_page>
   
.. toctree::
   :caption: Extras 
   :hidden:   
   
   Downloads<glob_empty_page>
   References<extras/EXTRAS_references>   

.. include:: glob_acknowledgement.rst

.. raw:: html

   <div style="text-align: center;">
      <img src="_static/art/logo_ftract.png" alt="Logo 1" style="display: inline-block; margin: 0 10px;width: 20%; height: auto;">
      <img src="_static/art/logo_inserm.png" alt="Logo 2" style="display: inline-block; margin: 0 10px;width: 30%; height: auto;">
      <img src="_static/art/logo_amu.png" alt="Logo 3" style="display: inline-block; margin: 0 10px;width: 30%; height: auto;">
   </div>


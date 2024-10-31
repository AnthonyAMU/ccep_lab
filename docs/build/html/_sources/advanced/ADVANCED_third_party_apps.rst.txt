.. include:: ../glob_header_msg.rst

Third-party apps
****************

CCEP Lab makes use of external software and libraries which are described on this page.
Notably, the :ref:`MatLab 2015b Runtime <ref_matlab_2015b_runtime>` is essential for data processing, while :ref:`AnyWave <ref_anywave>` and :ref:`HiBoP <ref_hibop>` software 
are optional but highly recommended for data visualization and review.

.. _ref_anywave:

AnyWave
--------------

AnyWave ([Colombet_2015]_) is a software designed to easily open and view data recorded by EEG or MEG acquisition
systems. It can be associated with CCEP Lab for the visualization of time series as well as the
specification of bad channels. It is available on Windows OS, macOS and Linux, and is free to use.
It can be downloaded from the `Marseille MEG platform wiki <https://meg.univ-amu.fr/wiki/AnyWave:Download>`_.

.. _ref_hibop:

HiBoP
------

HiBoP is a software dedicated to the visualization of intracranial brain recordings such as intracranial
electroencephalography (iEEG), Cortico-Cortical Evoked Potentials (CCEP) and functional magnetic resonance imaging (fMRI).
HiBoP can be associated with CCEP Lab for the 3D visualization of CCEPs.
It is freely available on Windows OS, macOS and Linux, and can be downloaded from the dedicated
`GitHub webpage <https://github.com/hbp-HiBoP/HiBoP>`_, with associated documentation.

.. _ref_intranat:

IntrAnat
---------

IntrAnat ([Deman_2018]_) is a software used to perform virtual electrode implantation in patients’ neuroanatomy
and to overlay results of epileptic and functional mapping as well as resection masks from the surgery.
IntrAnat can be used to generate implantation files compatible with CCEP Lab.
It is available on Linux for free and can be downloaded from the dedicated
`IntrAnat GitHub webpage <https://github.com/IntrAnatSEEGSoftware/IntrAnat>`_, with associated installation instructions
and documentation. IntrAnat now proposes accessibility options to ease the importation of imaging data from a BIDS dataset
and a feature to export generated implantation files in suitable BIDS derivative folders.

.. _ref_matlab_2015b_runtime:

MATLAB Runtime
--------------

CCEP Lab requires the MATLAB Runtime R2015b (9.0) to be installed ([MATLAB_2015]_), 
which can be downloaded from the `MathWorks website <https://mathworks.com/products/compiler/matlab-runtime.html>`_.

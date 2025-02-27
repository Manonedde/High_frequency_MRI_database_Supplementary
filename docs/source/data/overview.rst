Overview
========

The high-frequency MRI database is a repeated-measure study that collects
multiple microstructural MRI data:

* anatomical (3DT1 and FLAIR)
* multi-shell diffusion weighted images (DWI)
* inhomogeneous MT images (ihMT - MTI)
    
with a high number of MRI acquisitions over a short period of time in healthy
subjects. This high-frequency dataset was designed to generate enough data per
subject to optimize a relevant assessment of the consistency of different brain
MRI measurements. The two aspects of consistency, reliability and variability,
were evaluated using the Intraclass Coefficient correlation (ICC) value and
within- and between-subject coefficient of variation (CV).


Acquisition scheme
------------------
Twenty healthy adults were scanned 5 times over 6 months at the Centre
Hospitalier Universitaire of Sherbrooke (CHUS) using a clinical 3T MRI scanner
(Ingenia, Philips Healthcare, Best, Netherlands).


Pipeline summary
----------------
The main steps of the analysis are summarized in the figure below.

.. image:: ../pipeline/pipeline_summary.png
   :align: center
   :width: 700


MTI : Magnetization Transfer Imaging, DTI: Diffusion Tensor Imaging, NODDI: Neurite Orientation Density and Dispersion Imaging, HARDI : High Angular Resolution Imaging. For a list of metrics see Table of Metrics generated in Pipeline description. 


Consistency summary
-------------------
The main coherence results are summarized in the following figure :


.. figure:: summary_consistency.png
   :align: center
   :width: 900

   Classification of bundles and measures into four groups according to ICC values and within-variability (CVw). The x-axis represents CVw values (i.e., reproducibility), and the y-axis represents ICC values (i.e., reliability). High consistency group represents low CVw value < 0.05 (5%) and high ICC value > 0.75 (high reliability); Good consistency - ICC: high ICC value > 0.75 but high CVw value > 0.05 (>5%); Good consistency - CVw: low CVw value < 0.05 but low ICC value < 0.75 and finally, Moderate consistency: high CVw value > 0.05 (>5%) and low ICC value < 0.75.



Tools
------
The tools described and used are developed by the Sherbrooke Connectivity Imaging Lab (`SCIL`_), see the `SCIL Github`_ page for all available nextflows and tools.

 .. _SCIL: http://scil.usherbrooke.ca/en/
 
 .. _SCIL Github: https://github.com/scilus

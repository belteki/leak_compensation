# Leak compensation

This repository contains the code used for data processing, statistical analysis and visualization described in the following paper: **"Leak Compensation During Volume Guarantee With the Dräger Babylog VN500 Neonatal Ventilator"** *Pediatric Critical Care Medicine*, 2018 Jun 21. doi: 10.1097/PCC.0000000000001638.

Authors: Eniko Szakmar MD, Colin Morley MD, FRCPCH & Gusztav Belteki MD, PhD, FRCPCH

Link to the paper: https://journals.lww.com/pccmjournal/Abstract/onlinefirst/Leak_Compensation_During_Volume_Guarantee_With_the.98424.aspx

Contact: gbelteki@aol.com


The outputs (numbers, tables, graphs) of the IPython Notebooks have been suppressed to comply with copyrights. The corresponding data and graphs can be found in the paper.

This code can be viewed in any web browser. To run it, use the Jupyter Notebook. 


Packages required to run this Notebook:

- Python version: 3.5.3 | packaged by conda-forge | (default, Feb 10 2017, 07:09:50)
- IPython version: 5.3.0
- pandas version: 0.20.1
- matplotlib version: 2.0.2
- NumPy version: 1.12.1
- SciPy version: 0.19.0


I recommend downloading these packages using the freely availably Anaconda built: https://www.continuum.io/downloads


The Notebook also depends on the supplied helper files which should be in the same directory as the .ipynb notebook files

- gb_loader.py
- gb_stats.py
- gb_transform.py
- gb_visualizer.py

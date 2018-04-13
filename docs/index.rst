.. PDFRW documentation master file, created by
   sphinx-quickstart on Fri Apr 13 12:15:27 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

###################################
pdfrw - Low-level PDF Manipulation
###################################

 .. toctree::
   :hidden:
   :maxdepth: 2
   :caption: Contents:

   Home <self>
   README <readme>
   API Reference <api>
   Contributing <contributing>
   Testing Reference <testing>
   Glossary <glossary>

**pdfrw** is a Python library and utility that reads and writes PDF files:

* Version 0.4 is tested and works on Python 2.6, 2.7, 3.3, 3.4, 3.5, and 3.6
* Operations include subsetting, merging, rotating, modifying metadata, etc.
* The fastest pure Python PDF parser available
* Has been used for years by a printer in pre-press production
* Can be used with rst2pdf to faithfully reproduce vector images
* Can be used either standalone, or in conjunction with `reportlab`__
 to reuse existing PDFs in new ones
* Permissively licensed

__ http://www.reportlab.org/


pdfrw will faithfully reproduce vector formats without
rasterization, so the rst2pdf package has used pdfrw
for PDF and SVG images by default since March 2010.

pdfrw can also be used in conjunction with reportlab, in order
to re-use portions of existing PDFs in new PDFs created with
reportlab.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

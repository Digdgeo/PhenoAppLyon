==========================
PhenoApp
==========================

PhenoApp is a python script to show and check phenometrics derived from satellite imagery to some eLTER sites. It also allows the upload of phenological ground data since we are interested in the validation of these satellite datasets. 
This is one of the 3 buttons that conform the future Python Package GeeLterMap. A Geemap based tool that uses `Google Earth Engine
API <https://github.com/google/earthengine-api>`_ to show phenological satellite data in some eLTER sites. The other buttons will be focused in
flooding and Land Surface temperature.

This repo is kind of a prelease of that future GeeLterMap package to present PhenoApp tool in the eLTER software tools Workshop helded at Lyon from 7-9 febraury 2023.

.. image:: https://i.imgur.com/adxf9l6.png

Available datasets are:

* High Resolution Vegetation Phenology and Productivity Parameters. Copernicus Land Monitoring Service (CLMS) | 2017 - present
* MODIS MCD12Q2.006. Land Cover Dynamics Yearly Global 500m | 20011 - Present
* Sentinel 2 L2A Phenopy | 2017 - Present 

MODIS is the only product availabe as a collection in GEE. HRVPP products are downloaded viw HDA python through `Wekeo web site <https://www.wekeo.eu/data?view=catalogue&initial=1>`_.
Phenopy collection is self generated with Phenopy and ndvi2gif python packages.


Prerequisites
============


Please, register an account (free and very fast creation process) in the next links:

Wekeo: https://my.wekeo.eu/web/guest/user-registration

QField Cloud: https://app.qfield.cloud/accounts/signup

Googe Earth Engine: https://signup.earthengine.google.com/#!

 

Installation
============


To install this package right now use: 

.. code:: python

  pip install "git+https://github.com/Digdgeo/PhenoAppLyon.git"

and later install ndvi2gif in that environment via pip:

.. code:: python

  pip install ndvi2gif
 


Contributions
=============


Yes, please! git pulls will be welcome.


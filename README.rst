kml2geojson - Stripped down for Python/Django
************
    
`kml2geojson <https://github.com/mrcagney/kml2geojson>`_ is a Python 3.4+ package to convert KML files to GeoJSON files.
Most of its code is a translation into Python of the Node.js package `togeojson <https://github.com/mapbox/togeojson>`_.
This version, however, is a stripped down one, intended for Django (any version that works with Python 3.4+) kml converting, turned into a single script file.

Installation
=============
Download and drop kml2geojson.py file inside your project.

Usage
======
.. code-block:: python
    from .kml2geojson import convert
    converted_kml_json = convert('path/to/kml/file')

Maintaining
=============
I won't update and won't make any improvements to this script, since this repo was created with the sole intent to help me in a project.

Authors
========
- Original author: Alex Raichev (2015-10-03)
- Stripped down by Éber Peretto
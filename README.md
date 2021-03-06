
# CityJSON

This repository is where the specifications and the schemas of CityJSON are kept.

For all the details, see the official CityJSON website: [https://cityjson.org](https://cityjson.org)


## What is CityJSON?

CityJSON is a [JSON-based](http://json.org) encoding for a subset of the [OGC CityGML](http://www.opengeospatial.org/standards/citygml) data model (version 2.0.0), which is an open standardised data model and exchange format (in [GML](http://www.opengeospatial.org/standards/gml)) to store digital 3D models of cities and landscapes. 

The aim of CityJSON is to offer an alternative to the GML encoding of CityGML, which can be verbose and complex (and thus rather frustrating to work with). 
CityJSON aims at being easy-to-use, both for reading datasets, and for creating them.
It was designed with programmers in mind, so that tools and APIs supporting it can be quickly built, and [several]({{ "/software/" | prepend: site.baseurl }}) have been created already.

We believe that you should use CityJSON because: 

  1. its simplicity means that it is already supported by several software
  2. you can in one-click convert CityGML files to CityJSON files, and vice versa, with the open-source tool [citygml-tools](https://github.com/citygml4j/citygml-tools)
  3. files are on average [6X more compact](https://github.com/tudelft3d/cityjson/wiki/Compression-factor-for-a-few-open-CityGML-datasets) than their CityGML equivalent
  4. there is a [web-viewer](https://tudelft3d.github.io/CityJSON-viewer) where you can drag-and-drop a file
  5. you can easily manipulate files with [cjio](https://github.com/tudelft3d/cjio), you can for instance merge files, remove/filter objects, change the CRS, manage the textures, etc.
  6. you can *easily* define Extensions to the core model (akin to ADEs) 
  7. its development is [open on GitHub](https://github.com/tudelft3d/cityjson/issues/), it is supported by a vibrant community, and everyone is welcome to contribute


## Contributing to the project 

We invite anyone to contribute to the development and improvement of CityJSON, all discussions, issues, and developments are open to everyone.


## If you use CityJSON in an academic context, please cite this preprint

Ledoux H, Arroyo Ohori K, Kumar K, Dukai B, Labetski A, Vitalis A (2019). CityJSON: A compact and easy-to-use encoding of the CityGML data model. **Open Geospatial Data, Software and Standards**, 4:4 [<i class="fas fa-bookmark"></i>](http://dx.doi.org/10.1186/s40965-019-0064-0) [<i class="fas fa-file-pdf"></i>](https://opengeospatialdata.springeropen.com/track/pdf/10.1186/s40965-019-0064-0)


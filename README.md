# ArcGIS Earth Automation API
ArcGIS Earth Automation API provides a standard interface for 3rd party applications that support .NET to automate and communicate with ArcGIS Earth. The Automation API is based on [.NET WCF NamedPipe](https://msdn.microsoft.com/en-us/library/system.servicemodel.netnamedpipebinding(v=vs.110).aspx). It provides a fast and reliable way for on-machine communications. 

#### [API reference](http://doc.arcgis.com/en/arcgis-earth/automation-api/wcfnamedpipeipc.htm)


## Requirements
ArcGIS Earth Automation API requires [.NET 4.5.2](https://www.microsoft.com/en-us/download/details.aspx?id=42642).

## Features
* Get or set camera positions. 
* Add layers to ArcGIS Earth workspace from online or local folders. See table below.
* Delete layers from ArcGIS Earth workspace.
* Take snapshot of the scene view and share.
See [Release notes](http://docstg.arcgis.com/en/arcgis-earth/automation-api/release-notes.htm) for details.

Value | OperationalLayers | BasemapLayers |ElevationLayers
----| ---- | ---- | ----
FeatureService | Yes | Yes |
MapService | Yes | Yes |
ImageService | Yes | Yes |
Shapefile | Yes | Yes |
OGCWMS | Yes | Yes |
KML | Yes | Yes |
SceneLayerPackage | Yes | Yes |
SceneService | Yes | Yes |
Raster | Yes | Yes | Yes
TileLayerPackage | Yes | Yes |
ElevationService | | Yes

## Resources

* [ArcGIS Earth Documentation](http://docs.arcgis.com/en/arcgis-earth/automation-api/get-started.htm)
* [ArcGIS for Developers](https://developers.arcgis.com/documentation/#extend)
* [Forum](https://geonet.esri.com/groups/arcgis-earth)
* [Twitter@ArcGIS Earth](https://twitter.com/arcgisearth?lang=en)
* [Support](support.esri.com)

## Instructions
1. Fork and then clone the repo. 
2. Run and try the samples.
3. Recommend: Use [Visual Studio 2015](https://msdn.microsoft.com/en-us/library/dd831853.aspx) as your development environment.


## Examples

1. How to set up the Automation API to connect with ArcGIS Earth.
2. How to use the capabilities and methods of the Automation API.
3. View synchrinzation: Build a sample add-in for ArcGIS Pro 2.0.

## Issues
Find a bug or want to request a new feature? Please let us know by submitting an issue.

## Contributing
Anyone is welcome to contribute, and to extend and improve the examples by sending us pull requests. Please see [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2016 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://github.com/xiao8579/arcgisearth-automation-api/blob/master/LICENSE) file.

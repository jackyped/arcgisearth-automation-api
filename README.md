# ArcGIS Earth Automation API
The ArcGIS Earth Automation API provides a standard interface for 3rd party applications that support .NET to automate and communicate with ArcGIS Earth. The Automation API is based on [.NET WCF NamedPipe](https://msdn.microsoft.com/en-us/library/system.servicemodel.netnamedpipebinding(v=vs.110).aspx). It provides a fast and reliable way for on-machine communications. 

<div  align="center">
   
[![Introduction](images/1_Intro.png "Introduction")](http://doc.arcgis.com/en/arcgis-earth/automation-api/get-started.htm) 
[![How To Use](images/2_Use.png "How To Use")](http://doc.arcgis.com/en/arcgis-earth/automation-api/use-api.htm)

</div> 
<div  align="center">
   
[![API Reference](images/3_Reference.png "API Reference")](http://doc.arcgis.com/en/arcgis-earth/automation-api/wcfnamedpipeipc-namespace.htm)
[![Samples](images/4_Samples.png "API Samples")](../../wiki)

</div>

## Requirements
The ArcGIS Earth Automation API requires .NET Framework 3.0 or later.

## Features
* Get or set camera positions and flying animations. 
* Add layers to the ArcGIS Earth workspace from online or local folders. See table below.
* Delete layers from the ArcGIS Earth workspace.
* Take snapshot of the scene view and share.

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
ElevationService | | | Yes

## Resources

* [ArcGIS Earth Documentation](http://doc.arcgis.com/en/arcgis-earth/)
* [ArcGIS for Developers](https://developers.arcgis.com/documentation/#extend)
* Share your ideas or post questions via [GeoNet](https://geonet.esri.com/groups/arcgis-earth)
* [Twitter@ArcGISEarth](https://twitter.com/arcgisearth?lang=en)
* For assistance, please refer to [Support](http://support.esri.com/en/)

## Examples

1. [Connect to ArcGIS Earth with the Automation API](../../wiki/Connect-to-ArcGIS-Earth)
2. [Usage example of the Automation API](../../wiki/Usage-example-of-the-Automation-API)
3. [View synchrinzation: build a simple add-in for ArcGIS Pro 2.0](../../wiki/View-synchronization)

## Issues
Find a bug or want to request a new feature? Please let us know by submitting an issue.

## Contributing
Anyone is welcome to contribute and to extend and improve the examples by sending us pull requests. Please see [guidelines for contributing](https://github.com/esri/contributing) and [repository wiki](../../wiki).

## Licensing
Copyright 2017 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the [License](../../blob/master/LICENSE).

---
layout: detail
fullpreview: true
order-of-appearance: 5
draft: false

name: CityEngineSDK
platform: C++
logo: sdk.png
github: https://github.com/Esri/cityengine-sdk

hero-title: CityEngine SDK
hero-subtitle: Procedural Runtime for C++
hero-content:
  - type: image
    name: cityengine_teaser_image.png

teaser-image: cityengine_teaser_image.png

description: This is the official site for the SDK of CityEngine, a 3D city modeling software for urban design, visual effects, and VR/AR production.

gallery:
- image: cityengine_gallery_1.png
- image: cityengine_gallery_2.png
- image: cityengine_gallery_3.png

introduction: The CityEngine SDK can be used for the development of custom importers and exporters for CityEngine, or for 3D apps which need a procedural geometry engine.</br>For the usecase of custom importers and exporters for CityEngine, this means the SDK enables you to develop CityEngine plugins to read or write additional 3D and image formats or your own proprietary 3D data format. A simple use case example is 3D printing where the STL geometry format is often needed. STL support is not provided out-of-the-box in CityEngine, but you can develop your own STL exporter as described below.</br>For the other usecase, the core of CityEngine is its unique geometry generation engine, called Procedural Runtime (PRT). PRT takes as input an initial geometry and then applies a given rule package (= CGA rules authored in CityEngine) to generate more detailed 3D geometry as output. For example, PRT can generate - based on given rules - a 3D model of a building out of a parcel polygon. With the SDK you can integrate PRT in your own 3D applications taking full advantage of the procedural geometry generation without running CityEngine. An interesting use case example is Palladio, a plugin for SideFX’s Houdini software. Palladio includes PRT and therefore extends Houdini with the procedural geometry engine of CityEngine. Another use case example could be a specific cultural heritage 3D application which automatically generates detailed 3D models of temples based on input attributes.</br>The CityEngine SDK is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Please refer to the licensing section below for more detailed licensing information.

ressource-1-title: Downloads
ressource-1-text: Download the latest version of CityEngine SDK here.
ressource-1-link-text: → Go to downloads
ressource-1-link-url: https://github.com/esri/cityengine-sdk/releases

ressource-2-title: Documentation
ressource-2-text: A full documentation of Palladio is available on our github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/Esri/palladio/blob/master/README.md#documentation

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/esri/cityengine-sdk


legal: <ul><li>Copyright (c) 2020 Esri</li><li>You may not use the content of this repository except in compliance with the following Licenses&colon;</li><li>All content in the "examples" directory tree is licensed under the APACHE 2.0 license. You may obtain a copy of this license at http://www.apache.org/licenses/LICENSE-2.0.</li><li>All other content is licensed under the Esri Terms of Use (also see Product-Specific Terms of Use).</li></ul>
---

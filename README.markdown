#Examples using Away3D for OpenFL

##Introduction
Away3D for OpenFl is a port of the Flash Away3D engine, enabling OpenFL C++ native 
builds for OSX, Windows, iOS, Android and maybe others.

##Installation
Simply download the source files and ensure you have away3d-core-openfl and openfl-stage3d 
haxe libraries avialable either as haxelib installations or directly with the github source.

A typical project.xml file would look like

    <?xml version="1.0" encoding="utf-8"?>
    <project>
        <meta title="Basic View Away3D OpenFL" package="example.away3d" version="1.0.0" />
        <app main="Basic_View" file="Basic_View" path="Export" />
        <window width="1024" height="700" if="desktop" />
        <window orientation="landscape" fps="60" />
        <window depth-buffer="true" />
        <source path="src" />
        <classpath path="away3d-core-openfl" />
        <haxelib name="openfl" />
        <assets path="Assets" exclude="nme.svg" />
        <icon path="Assets/nme.svg" />
    </project>

##Dependencies
Requires [away3d-core-openfl](https://github.com/away3d/away3d-core-openfl) & 
[openfl-stage3d](https://github.com/wighawag/openfl-stage3d) to be installed.

    haxelib install openfl-stage3d
    
##License

Copyright 2014 The Away3D Team

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

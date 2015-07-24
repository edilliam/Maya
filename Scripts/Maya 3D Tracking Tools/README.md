# Maya 3D Tracking Tools

A collection of scripts to automate tasks related to importing externaly 3D tracked locators into Maya.

01: Creates a new layer called "GroundPlane".
02: Creates a polygon Tri from 3 selected locators and sends to "GroundPlane" layer.
03: Creates a polygon Quad from 4 selected locators and sends to "GroundPlane" layer.
04: Selects all objects in layer "GroundPlane" and merges all vertices to create a single object.
05: Creates a new red lambert material
06: Creates single cone, assigns the red material and moves it to a single locator.
07: Creates multiple cones, assigns the red material and moves them to multiple locators.
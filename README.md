# Point Cloud Skinner for Blender 4.2

This script is an adaptation of the original "Point Cloud Skinner" tool created by **Hans.P.G.**. It has been updated and restructured to work seamlessly with Blender 4.2.

## Overview

The script is designed to create a "skin" over a point cloud by generating mesh faces around the points. It uses advanced algorithms to manage vertices, edges, and faces, ensuring efficient and robust mesh generation.

## Features
- Supports both selected vertices or the entire point cloud.
- Advanced algorithms for face creation around vertices.
- Integrated error logging for debugging.
- Compatibility with the latest Blender Python API.

## Changes from the Original
- Updated API calls to align with Blender 4.2 standards.
- Improved error handling and debugging capabilities.
- Enhanced performance and modularity for better usability.

## How to Use
_You can describe here how to access and use the script within Blender. For example:_

1. Add the script to Blender by navigating to `Scripting > New Script`.
2. Run the script to register the "Point Cloud Skinner" tool.
3. Access the tool from `Properties > Scene > Point Cloud Skinner`.

## Installation
1. Download the script file (`t26_PointCloudSkinner1_Umbrella.py`).
2. Open Blender, go to the `Scripting` workspace, and load the script.
3. Run the script by pressing `Run Script`.
4. The tool will now be available in the **Scene Properties** tab.

## Interface
The tool appears under the `Properties > Scene` panel as **Point Cloud Skinner**. The interface provides the following options:
- **Target Object**: Specify the object to process.
- **Distance for Skin**: Define the maximum distance for vertex connections.
- **Ratio for Axis**: Set the ratio used for axis calculations.
- **Ratio for Grid**: Configure the size of the spatial grid used for vertex management.
- **Skin Only Selected Vertices**: Enable to process only selected vertices.
- **Ignore Errors**: Toggle to allow processing to continue despite errors.

## Author Credits
- **Original Author**: Hans.P.G.
- **Adaptation and Updates**: Paolo Colombo

---

# openxr-tracking-layer

## Goal of Layer

In this project, we will create a new API layer for OpenXR applications. This layer will intercept commands by other VR applications and will log position. Logging position will allow users to see data about what the VR user does in terms of position. 

## Specifics

This will be a explicit layer, which means that users will have to specify whether they want to use the layer. The layer will not be automatically enabled because some OpenXR applications may not need to log position.

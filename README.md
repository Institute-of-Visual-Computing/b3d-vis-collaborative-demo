Collaborative VR demo viewer for b3d-vis renderer. Can also be used in single user mode.

This project targets VR-HMDs and is developed with a Meta Quest 3. Other devices should work too.

# Setup
## Unity
1. Clone the project
2. Use the [Mixed Reality Feature Tool for Unity](https://learn.microsoft.com/de-de/windows/mixed-reality/develop/unity/welcome-to-mr-feature-tool) to add the following dependencies to the unity project:
  - com.microsoft.mrtk.graphicstools.unity-0.7.1
  - MRTK3
    - MRTK Graphics Tools 0.7.1
    - MRTK Audio Effects 3.0.4
    - MRTK Core Definitions 3.2.2
    - MRTK Input 3.2.2
    - MRTK Spatial Manipulation 3.3.1
    - MRTK Standard Assets 3.2.0
    - MRTK Tools 3.0.4
    - MRTK UX Components 3.3.0
    - MRTK UX Components (Non Canvas) 3.1.4
    - MRTK UX Core Scripts 3.2.2
  - Spatial Audio 
    - Microsoft Spatializer 2.0.55
3. Open the project with Unity 6.0+
4. Enable Unity Multiplayer Support
  - Navigate to Project Settings / Services
  - Link the project to a cloud project or create a new cloud link by clicking "New Link"

## Renderer
1. Clone and Setup the main project [b3d-vis](https://github.com/Institute-of-Visual-Computing/b3d-vis)
2. Enable the cmake option variable `BUILD_UNITY_EXTENSION`
3. Set the cmake variable `UNITY_PROJECT_ROOT_DIR` to the directory of the cloned repository
4. Install b3d-vis


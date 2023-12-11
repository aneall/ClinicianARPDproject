# ClinicianARPD
 Ashleyv's COMP 590 (3D Graphics + VR) Final Project Prototype

## About ClinicianARPD
#### ClinicianARPD is a sandbox prototype for implementing MR manipulation of humanoid models for clinical users. This is the first prototype of my project, using OVR.
#### I've since pivoted to using OpenXR, so I'm no longer working in this repo :)

### Development Tools Used
- Unity Editor 2022.3.11f1
    - Android build support (for Quest 2, 3, and Pro)
- Oculus Interaction SDK (OVR)
- Blender
- Mixamo

## Get Started - Unity XR Development Setup:
### Unity
1. Create a Unity account
2. Activate a Unity license
3. Download Unity Hub
4. Download Unity Editor 2022.3.11f1 with Android build support

### Git
1. Install Git
2. Install Git LFS (not required, but recommended for large asset version control)
3. Install GitHub Desktop (not required, but recommended if you're unfamiliar with CLIs)

### IDE
1. Install Visual Studio (our top pick, but you can use any IDE!)


## Clone and Develop Your Own Version:
1. **Clone the Repository**
   1. **with CLI**:
      1. Open the terminal → navigate to the root directory of your project with: `cd </path/to/repository>`
      2. Run `git clone <GitHub_repository_URL>`
   2. **with GitHub Desktop**: _make sure you’ve already installed Git LFS!_
      1. Open GitHub Desktop → navigate to **File** → **Clone Repository**
      2. Choose the repository from the list _or_ specify the URL
      3. Choose the local path where you want the repository to be cloned

2. **Install Git LFS**
   1. **with CLI:**
      1. In the project (repository)'s root directory, run `git lfs install`
         1. _If there are specific large file types tracked, they should be automatically handled by the `.gitattributes` file in the repository_
   2. **with GitHub Desktop**:
      1. When prompted with _“This repository uses Git LFS. To contribute to it, Git LFS must first be initialized. Would you like to do so now?”_ → select **Initialize Git LFS**

3. **Open the Project in Unity**
   1. Open Unity Hub → **Add** → select the project clone repository → **Add Project**
      1. _It’s recommended that all collaborators use the **same version of Unity**!_

## Acknowledgments
[Original 'Human skeleton' Mesh, Texture, and Annotations](https://sketchfab.com/3d-models/human-skeleton-23a06a148f9145769e822e74fe6b72fc)
- We altered this model to fit our project needs. Alterations include:
    - decimating polycount
    - reducing texture resolution
    - rigging with [Mixamo](https://www.mixamo.com/#/)

## Contact Information
### Ashley Neall
- aneall@unc.edu
# Instance Segmentation


## Project assumptions

- real-time work using RGBD RealSense D435 camera; 
- static objects detection; 
- objects size limited from 0.1[m]x0.01[m]x0.01[m] to 1[m]x1[m]x1[m]; 


## Expected final accuracy

- segmentation accuracy > 80% 
- IoU > 60%. 


## Tech stack

- **language:** Python 3.7
- **libraries:**
    - PyTorch - neural network building
    - OpenCV - vision processing
    - Intel RealSense SDK 2.0 -  connection with RealSense
    - PCL, Open3D - voxelisation
    - NumPy, scikit-learn - 3D bounding boxes


## Project schedule

| Tydzień | Wydarzenia | Założenia |
|:---:|:---:|---|
| 1 | Project assumptions | Preparation of a .md file and a Trello card with project assumptions, presentation of assumptions and a preliminary plan. Organisational activities. |
| 2 |  | Review of similar solutions, research, review of architectures, refinement of assumptions after initial consultation with the lecturer and familiarisation with the hardware. Distribution of tasks, dividing the team into sub-teams for the implementation of individual parts of the project. |
| 3 | Seminar | Start of work on the program. Presentation of a detailed plan. Choosing a network architecture. |
| 4-5 |  | Developing a dataset for fine training. Implementation of a segmentation model using pre-trained models.  |
| 6 | Milestone 1 | Instance Segmentation 2D: Accuracy > 80%, IoU > 60%.  |
| 7-8 |  | Working voxelization, review of algorithms for creating bounding boxes based on the instances map and the depth map. |
| 9 | Seminar | Start work on bounding boxes.  |
| 10 |  | End work on bounding boxes.  |
| 11 | Milestone 2 | Ready functionality for creating bounding boxes based on the map from the IS and the depth map. |
| 12 |  | Tests and debugging, work on improving the accuracy of the network. |
| 13 | Seminar | The finished project, consultation with the teacher. Tweaks before milestone 3. |
| 14 |  | Preparation of the installer for the program and initial development of documentation. |
| 15 | Milestone 3 | Ready real-time application. Preparing project documentation. |
| 16 | Deadline | Presentation of the completed project. Development documentation. Bugfixes. |

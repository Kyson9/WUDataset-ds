# WUDataset-ds

**WUDataset** is a neural pedestrian inertial navigation corpus collected with smartphone IMU (200 Hz), a Vicon optical system (100 Hz), and a LiDAR-SLAM rig (200 Hz), synchronized via a custom Android app.

The dataset spans an 8 m×20 m Vicon-tracked indoor space and diverse outdoor campus scenes reconstructed by SLAM. **WUDataset** contains 120 trajectories from 28 participants (total distance >40 km), covering slow walk, normal walk, and running, with varied device placements (hand-held, shoulder/arm, front/back pockets, backpack, handbag, swinging arm, chest pocket, etc.). This dataset provides realistic, multi-scene, multi-carry conditions for assessing any-scale sequence modeling and uncertainty-aware inertial localization. 

Due to privacy considerations and institutional data sharing policies, we are only releasing a subset of the **WUDataset**. The released portion still spans all movement types, device placements, and both indoor and outdoor scenes, ensuring it is representative and sufficient for benchmarking and reproduction.

## Data License

The **WUDataset** is released under the [MIT License](https://opensource.org/licenses/MIT).

## Google Drive Link

You can access the dataset here: [WUDataset on Google Drive](https://drive.google.com/file/d/19ZmFYXffd9uNU4un0gZBnqNpNPXr3nFt/view?usp=sharing)

## Code and Pre-trained Models

The code and pre-trained models will be released soon...

## Arxiv Preprint Version

https://arxiv.org/abs/2508.06053

## Usage

1. Clone or download the dataset files.
2. Follow the instructions in the provided documentation for data access and use.
3. If you use this dataset in your work, please cite the following:

   ```bibtex
   @misc{Wu2025WUDataset,
     author = {Wu, Kaixuan and others},
     title = {WUDataset: A Neural Pedestrian Inertial Navigation Corpus},
     year = {2025},
     note = {MIT License},
     url = {https://drive.google.com/file/d/19ZmFYXffd9uNU4un0gZBnqNpNPXr3nFt/view?usp=sharing}
   }

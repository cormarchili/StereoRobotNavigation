# Stereo Robot Navigation

## Overview

Given a video sequence taken by a stereo camera mounted on a moving vehicle, project’s objective is to sense information concerning the space in front of the vehicle which may be deployed by the vehicle navigation system to automatically avoid obstacles.

Parameters for distance estimation from stereo images are:
- focale f = 567.2 pixels
- baseline b = 92.226 mm

## Installation

Clone the repository and install dependencies in a dedicated environment:

```bash
$ cd StereoRobotNavigation/
$ pip install -r requirements.txt
```

## Project Structure

```bash
StereoRobotNavigation/
├── README.md
├── Stereo Robot Navigation.ipynb
├── requirements.txt
└── robot-navigation-video/
    ├── robotL.avi
    └── robotR.avi
```

The robot-navigation-video/ folder contains a pair of synchronized videos taken from a stereo camera, with one video capturing the left and the other the right view.

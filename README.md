# RatTracker

## Introduction

This project aims to collect data on various types of rats through video recordings. In the initial phase, I connected to a cluster that housed rat archives, allowing me to export or download videos of 15 different rat types. Overall, the data collection process involved retrieving a total of 100 videos.

## Data Collection Process

To collect the rat data, I followed these steps:

1. Established a connection with the cluster containing the rat archives.
2. Identified the different types of rats available for data collection.
3. Exported or downloaded videos for each rat type.
4. Ensured a comprehensive collection by gathering a total of 100 videos.

## Data Format

The collected rat data is in video format, providing a rich visual representation of the different rat types. Each video file is named according to the corresponding rat type for easy identification and organization.

## Directory Structure

The following is the directory structure for the collected rat videos:

![Capture_1](https://github.com/ouarzazi/RatTracker/assets/134293350/623075b5-bd84-4406-bf34-1409ec289183)

## Data Labeling and Tracking

To analyze the collected rat videos, we utilized DeepLabCut, a popular tool for markerless pose estimation. The following steps were performed for labeling and tracking:

1. Set up DeepLabCut environment and dependencies.
2. Defined a project for each rat type and configured the desired number of points to track (e.g., 10 points).
3. Manually labeled a subset of frames in each video to train the DeepLabCut model.
4. Performed model training and refined the network for accurate tracking.
5. Applied the trained model to automatically track the chosen points of interest on the rats throughout the videos.



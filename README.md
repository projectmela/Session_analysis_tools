

# Srt analyzer of drone flight
This code helps you in analyzing your drone session using the SRT files created. The code analyses the SRT files of the flight session and gives you output, identifying errors and other unique data from each session.

1)It creates a CSV file combining all the data. The information in the CSV file is:
Flight number, Global start/end time, max/min-height, drift status, height variation, frame drop, miss clicks, start/end frame, relay video.

2)It produces a text file that contains details of sessions that have passed above the threshold.

3)It creates a graph which shows the overlap between drone flights


# Video corruption checker

Check if the videos recorded in each session are corrupted by going through the folders. A data frame is created that provides details about each video's viability


# Renaming the files

This code renames the video and SRT files in a format that includes the date_session_drone_id_filename.

For example 20230212_SM_LEK1_P2D2_DJI0123
## Installation

These codes can be directly run using Python once you have downloaded and installed the required files.


dependencies:
  - python=3.10.9 
  - numpy=1.23.5
  - pandas=1.5.3
  - matplotlib=3.7.2
  - geopy=2.3.0 
  - opencv=4.6.0  
```
The codes can take more arguments when called. Type --help to see more options.
srtanalyzer can take:
the location of the session
drift threshold value
height threshold value

Videocorruption can take:
the location of the session
## Appendix

A test dataset is provided to help you in checking if the codes are running as intended. The test dataset contains both the files to be run and their expected outputs.

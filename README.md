
# Srt analyzer of drone flight
This code helps in anlysing you drone session using the srt files created
## Documentation


# **SRT analyzer** 
This code helps in identifies the errors and other unique data from each drone session. It creates a csv file combing all the data. 
The information in the csv file are:
Flight number, Global start/end time, max/min height, drift status, height variation, frame drop, miss clicks, start/end frame, relay video
## Installation

These codes can be directly run using python once you have downloaded and installed the required files.
dependencies:
  - python=3.10.9 
  - numpy=1.23.5
  - pandas=1.5.3
  - matplotlib=3.7.2
  - geopy=2.3.0 
  - opencv=4.6.0  
```
The codes can take more aruguments when called. Type --help to see more options.
srtanalyzer can take
the location of the session
drift threshold value
height threshold value

Annotationanalysis can take
the location of the annotated file
area threshold value
command to not create the graphs
command to display graphs while running the code
## Appendix

A test dataset is provided to help you in checking if the codes are running as intended. The test dataset contains both the files to be run and their expected outputs.

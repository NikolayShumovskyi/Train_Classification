# Case Study: Data Science

## Description

You are tasked with providing a preliminary analysis of a heterogeneous set of vertical
acceleration measurements recorded by KONUX sensors.


## Goal

You will likely need to get familiar with the data first.

The final aim of the analysis is to:

1. Determine the **horizontal speed** of each of the trains, and
2. Classify the signals by **train type**.

There is no assertion that the amount of data provided is sufficient to uniquely
determine these attributes.
What we ask for is your best attempt at doing the above analysis, given the time and data
constraints.
Note that the **speed** requested is the speed of train in the direction of travel, not
the measured vertical speed.


## The data

The `data/` directory that comes with this repo contains the following:

* 20 acceleration traces from a range of train types, train speeds, and locations, i.e.
  different switches;
* 2 kHz sampling rate; and
* binary data files storing G values as 32 bit floats (to make sure you have loaded the data correctly compare with a typical result in `sample.png`)
* A sensor power up phase manifests as a rise in average signal (from large negative G
  values) over the initial few hundred milliseconds.
* The file name format is
  `<yyyymmdd>_<HHMMSS>_<sensor-id>_<deployment-id>_channel<channel-id>.dat`.
* The date-time-stamp reflects the start of data recording.


## How to deliver the results

Estimated time required for the task: 1 day.

We expect the coding part of the analysis to be done in Python, but you can use any
libraries/packages that you would normally use on the actual job. However please do not
use any commercial analysis products or tools.

The submitted solution should contain the following:

* A short report outlining your proposed approach and indicate how much time you have
  taken for the task.
* All Python code

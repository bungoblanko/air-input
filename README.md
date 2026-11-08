# air-input

Benchmarking webcam hand and eye tracking against the mouse using Fitts' law throughput

## Question

How close can webcam-based hand and gaze input get to a mouse for pointing and selecting?

## Status

Work in progress. This project's aim is to strengthen my Python fundamentals along with concept fundamentals while exploring an area of interest. Results come from one participant (me), so they reflect the pipeline working, not a generally applicable finding. 

## Plan

1. Capture webcam video and track hand landmarks.
2. Clean the signal and measure jitter.
3. Run a Fitts-style pointing task and compute throughput.
4. Repeat with eye tracking.

Raw video is never stored in this repo.
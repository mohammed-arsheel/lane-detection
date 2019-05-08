# lane-detection

This repository contains an approach to detect lanes in an image with polynomials and tracks the parameters with an array of Kalman filters. Further explanations can be found in the German text book [Kalman-Filter](http://www.kalman-filter.de/)[1].

## How to use

The repository contains a simulation of artificial images. However, the lane detection approach can also be used with real world images.

### Simulation of artificial images

To generate the artificial images run

    src/main_generateImages.m

Then the images have to be transformed into bird's view with

    src/main_generateBirdViewImages.m

### Execute lane detection algorithm

The lane detection approach works on images in bird's view. To run the lane detection on th artificial images execute

    src/main.m

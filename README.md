# Quack_track
## Overview
This project aims to detect ducks in a video moving in a grid and calculate their movement using computer vision techniques.

## Features
- Detect ducks in frames.
- Calculate the distance traveled by ducks between frames.
- Generate motion statistics for the detected ducks.

## Installation
1. Clone the repository:
git clone https://github.com/your-username/duck-detect-motion-calculator.git

2. Install dependencies:
pip install -r requirements.txt

## Usage
1. Navigate to the project directory.
2. Run the main script:
python detect.py --weights /path/to/weights.pt --source path/to/video.mp4

## Example
Below is an example usage of the script:
python detect.py --weights best.pt --source ducks.mp4

## Demo

<iframe width="560" height="315" src="https://youtu.be/olWXXbzrLfk" frameborder="0" allowfullscreen></iframe>


## Dependencies
- argparse
- os
- platform
- sys
- pathlib
- numpy
- cv2
- matplotlib
- torch

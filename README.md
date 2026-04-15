1. 22EC01056
   22EC01039
   25CL06002
2. Deep SORT Repository
You must have the Deep SORT repository cloned into your working directory alongside the main script:

Bash
git clone [https://github.com/nwojke/deep_sort.git](https://github.com/nwojke/deep_sort.git)
3. Download the Appearance Model
Ensure the mars-small128.pb model file is downloaded and its path is correctly referenced in the script.

How to Run
Open the primary Python script in VS Code.

Locate the configuration variables at the top of the script.

Update VIDEO_INPUT_1 and VIDEO_INPUT_2 with the absolute paths to your local video files.

Update MODEL_PATH with the absolute path to your mars-small128.pb file.

Update WORKING_DIR to the folder where you want the outputs saved.

Run the script.

Expected Outputs
The script will generate the following deliverables in your designated working directory:

Tracked Videos: .mp4 files showing bounding boxes, unique IDs, and trajectory tails.

Trajectory Data: .txt files containing Frame, TrackID, CenterX, CenterY, Width, and Height.

Direction Data: .txt files containing compass direction calculations and coordinate deltas.

Visualizations: .png images showing trajectories mapped over the video background, both before and after K-Means clustering.
"""

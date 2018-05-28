things i need to do
-----

#### 1. Put data in BIDS format
- to use fMRIprep-docker, my data need to be in BIDS format (also probably will be useful for multiple programs/pipelines)
- using dcm2bids / dcm2niix
- (Is it going to be an issue in establishing the config file that my scans are from different scanners? *future noor says: yes. yes it is.*)
- (Also, how do I verify that dcm2bids chose all the right images to convert and move? My dicomdir is very messy and some dirnames match multiple scans that aren't really the same...)

#### 2. Deal with flipped/opposite distortion scans
- I have an issue with some of my images that has been described as "fun"
 by many people more experienced than I. Some scans' raw images (usually GE volumes) are flipped in the A-P direction for every other volume, including the distortion direction. (I have been advised to split the volumes and treat each direction as its own scan and then re-concatenate after the distortion correction.)
 - How to automatically detect flipped vs non-flipped volumes?

#### 3. Correct distortion
-

#### 4. Generate functional connectivity maps
-

#### 5. Analyse Dat!
-

#### 6. Celebrate and be merry

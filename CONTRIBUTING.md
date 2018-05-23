i'm trying to learn how to:
-----

### + preprocess resting-state fMRI data
*using [NIAK](http://niak.simexp-lab.org/pipe_preprocessing.html), [fMRIprep](https://github.com/poldracklab/fmriprep) (& Docker) and/or [CPAC](https://fcp-indi.github.io/)*

My PhD project focuses on multimodal connectivity in development and I would like to include resting-state fMRI data along with my DWI volumes. I have never pre/processed an fMRI scan before and have some extra "fun" issues with some of my scans (orientation/distortion) that need to be resolved. My data come from different scanners and locations which might mean using a different preprocessing pipelines/parameters per scanner.

**| deliverable:** Processed set of test data (20 subjects), preprocessing pipeline/script (if different from basic tools)

### + analyse connectivity data
*structural and functional connectivity using DWI + rsfMRI*

Data reduction, whole-brain vs specific network connectivity, multimodal analysis, definitions of connectivity... plz help.

I know little about either functional or structural connectivity analysis and how to run my own stats on them -- why to choose certain tests over others, what the measures represent, etc -- but it's what I want to do for my PhD project! So would be nice to know at least something about it.

**| deliverable:** Analysis plan + ability to explain it to my grandma

### + batch-processing on Compute Canada
My imaging dataset has nearly 1000 subjects so I need to run a lot of jobs on CC (cedar/graham). I would like to know some of the specific parameters to use with proper batch-processing etiquette so as not to anger the Compute Canada gods.

**| deliverable:** Process 20 jobs without getting a reprimanding email from CC

how to help
-----
Can you run NIAK/fMRIprep/CPAC? Can you tell me what they do? Holla @ ya gurl via slack (at noor on brainhack.slack) or here @nooralsh or in person or email noorbalsharif@gmail.com.

Do you know how to draw nice diagrams explaining connectivity measures? Do you know graph theory metrics of connectivity? What about tractogram-based metrics of connectivity? My attention is all yours.

Can you explain the difference between PCA / ICA / CCA / LSA ?? Please explain it to me like I'm 5 years old and show me how to use it on my data.

Have you processed a million jobs on Compute Canada? Have you done so using custom pipelines or locally installed tools?? Or using a container / singularity image??? Please tell me the best way to do these things!

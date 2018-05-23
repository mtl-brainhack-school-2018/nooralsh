### *nooralsh* | BRAINHACK SCHOOL MTL 2018

background
-----
Currently a PhD student at McGill, studying structural connectivity and cognition in development using DWI metrics. I began my career in neuroscience as an undergraduate student at the University of Manchester, UK where my focus was far more cellular/molecular. I decided the lab bench was not for me and sought out a career in neuroimaging upon graduating. I [worked](https://github.com/mtl-brainhack-school-2018/nooralsh/blob/master/ABOUT_ME.md) for 4 years as a research assistant in two neuroimaging labs at UCLA, firstly in a lab studying heritability of brain structure and then another developing image processing software BrainSuite. I scanned mice on a 7T Bruker Small Animal scanner, created a macaque segmentation atlas from scratch, processed T1s and DWIs from rodents, non-human primates and humans of all kinds, all while managing a bunch of rowdy undergrad volunteer researchers. I was introduced to basic programming, learned how to use a wide range of imaging tools, and acted as a sort of "imaging consultant" for BrainSuite users. But, despite all this growth, I decided it was time to move on to supposedly bigger and better things and so I came to grad school~*

current project
-----
At McGill, my PhD project focuses on stuctural white matter development and how these changes relate to cognition. How does white matter connectivity as measured by imaging (T1, DWI, rsfMRI) underlie changes in behaviour? Do these structural changes have clusterable patterns? Can they be used as biological markers of maturity? Are certain structural networks, if any, better for predicting age or cognitive ability? What white matter features underlie these relationships? Will I ever graduate??? Only time and a lot of grant rejections will tell.

To complete my project, I have employed the sort-of open source PING dataset, detailed below. I have structural data from CIVET 2.1 and DWI connectivity data from ndmg and Maxime Descoteaux's SCILPY pipeline.

brainhack goals
-----
Despite my wide background in imaging methods and tools, I have never processed an fMRI scan of any kind. I'm not even 100% sure how the volumes are structured. As such, I'd like to stick my hands into the rsfMRI volumes available to me through PING, learn about various fMRI processing pipelines and how to turn rsfMRI volumes into data that can be used in a multimodal assessment of developmental connectivity. Kind of like a bootcamp in rsfMRI from A to Z. Any help for any aspect of the processing pipeline from what an rsfMRI volume is to analysis tools is very very welcome.

If you want to know how to help more specifically, please check out how [here](https://github.com/mtl-brainhack-school-2018/nooralsh/blob/master/CONTRIBUTING.md).


### [pediatric imaging neurocognition and genetics (ping)](http://pingstudy.ucsd.edu/)

Collected across 9 US sites, based out of UCSD, PING comprises ~1500 subjects (aged 3-21y) with various imaging, cognitive and genetic data. It is a fairly good quality dataset, especially considering most of the subjects are children who usually have heavy motion artefacts in their scans.

**| imaging**
Subjects were scanned on one of four 3T scanner types (Siemens, GE Discovery, GE Signa, Philips Achieva). Those with imaging data usually have at least one of the following:
+ T1
+ T2
+ DWI (usually two 32-dir scans)
+ rsfMRI

**| cognition**
Cognitive data were collected using the NIH Toolbox: Cognition Battery which consists of a series of computer-based tests used to measure
+ Episodic Memory (Picture Sequence Memory Test)
+ Executive Function & Attention (Flanker Inhibitory Control and Attention Test, Dimensional Change Card Sort Test)
+ Working Memory (List Sorting Working Memory Test)
+ Language (Picture Vocabulary Test, Oral Reading Recognition)
+ Processing Speed (Pattern Comparison Processing Speed Test)

**| genetics**
Collection of ~500k single nucleotide polymorphisms (SNPs) available via [study site](http://pingstudy.ucsd.edu/Data.php) (requires account).

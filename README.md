# 🐔🐑🐁🐿🐳🦀🦚🕷🐝🗣🐦💬 vocal-behavior-resources
## Tools, models, and datasets for researchers studying vocal behavior

Language is perhaps the only behavior unique to humans, 
although several other clades of animals 
similarly learn to vocalize through a process of trail-and-error learning and social interactions. 
An open area of research is whether 
these abilities should be understood as a spectrum, 
or a set of multi-dimensional cognitive functions.
We call this field of study *vocal behavior*, 
meaning "the study of animal vocalizations, especially as it relates to speech".
Researchers ranging from 
[Chomsky, Fitch, Hauser, Jackendoff and Pinker in the early 2000s](https://dash.harvard.edu/bitstream/handle/1/3117935/Hauser_EvolutionLanguageFaculty.pdf?sequen) 
to 
[a broad swath of researchers studying vocal learning today](https://royalsocietypublishing.org/toc/rstb/2021/376/1836)
have argued that the best way to can understand the origins 
of language and related abilities in other animals  
is to take a big team science approach, 
broadly comparative, 
with truly integrative work across disciplines, 
including genetics, physiology, neuroscience, ecology and evolution, to name just a few.
Of course we recognize huge overlap 
with animal communication and bioacoustics, 
but we assert that 
understanding the origin of language requires a specialized approach.
Additionally, 
we propose that the study of vocal behavior 
requires a
[software community](https://zenodo.org/record/6257662),
in the same way that 
astronomy has the [astropy project](https://www.astropy.org/about.html),
high-energy physics has [scikit-HEP](https://scikit-hep.org/),
and bioinformatics has [bioconda](https://bioconda.github.io/),
again to give just a few of many examples.
There has been a recent explosion of software, 
behavioral models, and datasets 
targeted at researchers studying vocal behavior.
This has resulted in a situation 
similar to the beginnings of the 
[astropy ecosystem](https://arxiv.org/abs/1610.03159), 
where there is reduplicatin of effort, 
and multiple tools offering similar 
but not completely overlapping functionality.
To demonstrate that this is an exponentially grouwing software community, 
and to illustrate the need for a more organized and cohesive effort 
among all researchers in that community, 
we provide here a site with software tools,
behavioral models, and publicly-available datasets.
We welcome contributions to this site through the Google Form or GitHub pull requests.
For a proof-of-concept version of 
a core software community designed 
by and for researchers studying vocal behavior,
please see: https://github.com/vocalpy.
Papers in progress describe the need for this software community 
and the design of VocalPy, and we are open to 
contributions to both.

## Code

### general

https://github.com/BirdVox/BirdVox_datasets  
data-wrangling scripts put together by the BirdVox team  

https://github.com/kylebgorman/textgrid  
for working with Praat TextGrid files in Python  

### for accessing websites with APIs

https://github.com/aemarse/xeno-canto-python  

https://github.com/davipatti/birdbrain  
Looks like it has a nice class-based approach to accessing Xeno-Canto through their API  

## Data

### general

https://www.xeno-canto.org/

http://taylor0.biology.ucla.edu/birdDBQuery/

https://wp.nyu.edu/birdvox/codedata/#datasets

http://dcase.community/challenge2018/task-bird-audio-detection#audio-datasets  
Birdsong Audio Detection challenge. Has several datasets recorded 
in diverse conditions to enable testing how well models generalize.

### species-specific repositories

#### Bengalese Finch

"Bengalese Finch song repository"  
https://figshare.com/articles/Bengalese_Finch_song_repository/4805749

"BirdsongRecognition"  
https://figshare.com/articles/BirdsongRecognition/3470165

"Data from: A simple explanation for the evolution of complex song syntax in Bengalese finches"  
https://datadryad.org//resource/doi:10.5061/dryad.6pt8g

#### Zebra Finch

Global Song Library:  
http://songbirdscience.com/resources/behavior/global-song-library

"Data from: Horizontal transmission of the father’s song in the Zebra Finch (Taeniopygia guttata)"  
https://datadryad.org//resource/doi:10.5061/dryad.7137r

Williams, H. (1997) Zebra Finch Song Archive.  
"The songs archived here are the minimal length necessary to show all of the syllables sung by a given bird."  
i.e. there is only one .wav file per bird  
http://web.williams.edu/Biology/Faculty_Staff/hwilliams/ZFsongs/

#### Cassin's Vireo
Hedley, Richard (2016):  
Data used in PLoS One article  
"Complexity, Predictability and Time Homogeneity of Syntax in the Songs of Cassin’s Vireo (Vireo cassini)"
by Hedley (2016). figshare.  
https://doi.org/10.6084/m9.figshare.3081814.v1

## See also
For a much more general site for anyone working in bioacoustics, 
please see the excellent site organized by Tessa Rhinehart: 
https://github.com/rhine3/bioacoustics-software

# A Beginner's Guide to Passive Acoustic Monitoring for Cetaceans

This is a unfinished document currently being edited. 

At the very end of the document, there are tutorial tips (from the macdown help files) on using macdown that may help to add edits/suggestions to this file [Macdown Tips] (#Macdown-Tips).

For any questions, contact Divya Panicker; dpanic@uw.edu

## Contents

1. [Sound and water](#Sound-and-water)
2. [Sound characteristics of cetaceans](#Sound-characteristics-of-cetaceans)
4. [Instrumentation](#instrumentation)
5. [Automated Detection and Classification](#Automated-Detection-and-Classification)
8. [Machine learning](#machine-learning)
10. [Further questions](#further-questions)
11. [Summary of training resources](#summary-of-training-resources)
12. [Summary of key papers](#summary-of-key-papers)
13. [Case studies](#case-studies)
14. [Relevant tools in Data Science] (#Relevant-tools-in-Data-Science)
14. [References](#references)




![PAM's](https://cdn.rawgit.com/divyapanicker/Beginners-tutorial-passive-acoustic-monitoring/ff4e85b0/img/photo.png)





## Sound and water <a id="Sound-and-water"></a>

Sound waves are longitudinal waves proprogating through a medium. Three basic physical characteristics of sound; 

- intensity a.k.a sound pressure or acoustic energy
- frequency i.e no: of times per sec medium vibrates or oscillates
- duration i.e length of time 

Watch the following video on youtube by Khan Academy to understand the [basics of sound waves, frequency, amplitude, period and wavelength.](https://www.khanacademy.org/science/physics/mechanical-waves-and-sound/sound-topic/v/production-of-sound) 

Sound travels faster in water than air ([Sound in water vs air; DOSITS](https://dosits.org/science/sounds-in-the-sea/how-does-sound-in-air-differ-from-sound-in-water/)). Distance that sound travels in water is dependant on water temperature and pressure (incl. image of sound channel). Water properties change with depth and a deep sound channel is formed where sound travels over very large distances. Refer [sound channel in DOSITS] (https://dosits.org/tutorials/science/tutorial-sound-channel/) for more information. 

Sound is often created by a source like a vibrating diaphragm or air sac. In marine mammals sound is created by..

References for basic information on sound can be accessed on;
DOSITS
Khan Academy
Review paper - sound

## Sound characteristics of cetacean species <a id="Sound-characteristics-of-cetaceans"></a>

## Hardware tools

## Instrumentation <a id="instrumentation"></a>

How to choose intrumentation?

1. Fixed or mobile?
2. Frequency range?
3. Amplitude (controlled by gain)


Then compare, to available forms of hydrophones such as
available platform papers

## Software tools

### 1. Software for sound analysis 

Several softwares can be used to analyze passive acoustic monitoring data

#### Raven

Raven pro is a software program developed by the cornell lab for ornithology. The free version is Raven Lite. It helps with acquisition, visualization, measurement and analysis of sounds. Raven was originally built for bird acoustics but has been extensively used for cetaceans. It is For more information, visit the [Raven website] (http://www.birds.cornell.edu/brp/raven/RavenOverview.html) which provides more information on it's uses and downloads. 

Introductory tutorials on raven can be found [here] (https://ravenbioacoustics.wixsite.com/raventutorials). The tutorials cover the basics of how to use the raven interface, how to acccess waveform (amplitude vs time) and spectograms (frequency vs time) from sound files. It also explains how to mark and save selected sounds of interest in a spectogram and other basic features. 

Advantages: 
1. Works on windows, mac and linux
2. A quick way to assess large amounts of data where no programming knowledge is needed
3. User friendly visualizations

Disadvantages:

#### Ishmael

## Automated Detection and Classification <a id="Automated-Detection-and-Classification"></a>

LFDCS Summary

ROCCA Summary

## Machine Learning <a id="machine-learning"></a>

The following website gives a good self starter guide to [machine learning] (https://elitedatascience.com/learn-machine-learning#what)


## Further questions <a id="further-questions"></a>

## Summary of training courses <a id="summary-of-training-resources"></a>

SeaBASS
Denmark course

## Resources from other bioacoustic programs <a id="Sound-characteristics-of-cetaceans"></a>

[Animal Bioacoustics] (http://www.animalbioacoustics.org/links.html)

## Summary of relevant articles <a id="summary-of-key-papers"></a>

## Case Studies <a id="case-studies"></a>

## Relevant tools in Data Science <a id=Relevant-tools-in-Data-Science></a>


#### Python

Python is a programming language that is used by many data scientists and acousticians. It is a 
Tutorial on python (https://elitedatascience.com/learn-python-for-data-science)
[To install python] (https://www.anaconda.com/download/#macos)

## References <a id="references"></a>

1. Bittle, M. and Duncan, A., 2013, November. [A review of current marine mammal detection and classification algorithms for use in automated passive acoustic monitoring] (https://www.acoustics.asn.au/conference_proceedings/AAS2013/papers/p64.pdf). In Proceedings of Acoustics (Vol. 2013). 

2. Mellinger, D.K., Stafford, K.M., Moore, S.E., Dziak, R.P. and Matsumoto, H., 2007. [An overview of fixed passive acoustic observation methods for cetaceans](http://www.jstor.org/stable/24860138). Oceanography, 20(4): 36-45. 

## References with notes

Some summarized notes to add into the documents where relevant

1. Bittle, M. and Duncan, A., 2013, November. [A review of current marine mammal detection and classification algorithms for use in automated passive acoustic monitoring] (https://www.acoustics.asn.au/conference_proceedings/AAS2013/papers/p64.pdf). In Proceedings of Acoustics (Vol. 2013). 



2. Mellinger, D.K., Stafford, K.M., Moore, S.E., Dziak, R.P. and Matsumoto, H., 2007. [An overview of fixed passive acoustic observation methods for cetaceans](http://www.jstor.org/stable/24860138). Oceanography, 20(4): 36-45. 

This article provides an overview of information on methodology including instrumentation and behavioral considerations, detection of vocalizations for PAM. The paper also provides information on PAM applications for studying marine mammals such as determining range and seasonality, and abundance estimation and related analytical methods. A case study of surveying humpback whales, blue whales and right whales from Antarctica is shown. Gaps identified in the paper: •	Lack of understanding of behavioral context of sound production
 •	No standardization of sound reception between near bottom, near surface and deep sound channel. Further steps proposed in the paper:
•	Develop statistical models to account for variability in sound production and reception distance (will need distribution curves, seasonal, sex, age-class bias in sound production, frequency range of species-specific sound characteristics, source sound level variation)




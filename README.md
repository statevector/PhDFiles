# Dissertation and Ph.D. Defense Slides

Here I include my:

1. [dissertation](https://github.com/statevector/PhDThesis/blob/master/willis_thesis.pdf) <br>
2. [defense presentation](https://github.com/statevector/PhDThesis/blob/master/willis_presentation.pdf)

(you might want to right-click save-as, since each of these are pretty large)

## An analysis of Large Hadron Collider (LHC) data, or: Searching for high-mass Dilepton Resonances

For my Ph.D., I analyzed over 100 TB of proton-proton collision data as produced by the 
[LHC](https://home.cern/science/accelerators/large-hadron-collider) and recorded by the 
[ATLAS experiment](https://home.cern/science/experiments/atlas) at [CERN](https://en.wikipedia.org/wiki/CERN) in Geneva, Switzerland. The goal of this analysis was to search for 
"[New Physics](https://en.wikipedia.org/wiki/Physics_beyond_the_Standard_Model)", or evidence of new elementary particles or forces as predicted by various extensions of our current fundamental theory of Particle Physics, the [Standard Model](https://home.cern/science/physics/standard-model).

The topic of my dissertation is "A Search for Resonant Z' Production in the High-Mass Dielectron Final States". Here, the New Physics takes the form of a new, hypothetical elementary particile called the [Z' Boson](https://en.wikipedia.org/wiki/W%E2%80%B2_and_Z%E2%80%B2_bosons), which is somewhat like a massive cousin of the more well-known [Photon](https://en.wikipedia.org/wiki/Photon) of electromagnetism. In this case, the Z' is predicted to quickly decay into an electron and positron pair -- and it is this signature that is searched for in the resulting debris of the LHC proton-proton collisions. The observation of several electron-positron pairs (i.e. the signal) above what the Standard Model nominally predicts (i.e. the background) would count as strong evidence for Z' production, and hence towards Physics Beyond the Standard Model.

The results of the search conducted here showed no significant deviations from the Standard Model prediction, and as a result, multiple models predicting Z' physics at the LHC were able to be excluded. If a Z' Boson does exist, it must have an enormous mass, roughly 4,500 times the mass of the proton.

This project included but was not limited to the following steps:

- obtaining, cleaning, and verifying the integrity of data <br>
- data visualization <br>
- exploratory data analysis <br>
- feature engineering <br>
- maximum likelihood estimation <br>
- bayesian and frequentist hypothesis testing <br>
- model selection/evaluation, and <br>
- monte carlo simulation.

For this analysis, I made heavy use of the standard particle physics data analysis framework developed at CERN ([ROOT](https://root.cern.ch/about-root)) and C++ in a Linux environment.

# Dissertation and Defense Presentation

Here I include my:

1. [dissertation](https://github.com/statevector/PhDThesis/blob/master/willis_thesis.pdf); <br>
2. [defense presentation](https://github.com/statevector/PhDThesis/blob/master/willis_presentation.pdf).

(you might want to right-click save-as, as these are pretty large)

## Explanation of my Ph.D. (An analysis of Large Hadron Collider (LHC) data)

For my Ph.D., I analyzed several terabytes of proton-proton collision data generated by the 
[LHC](https://home.cern/science/accelerators/large-hadron-collider) and recorded by the 
[ATLAS experiment](https://home.cern/science/experiments/atlas). The goal of this analysis was to search for 
"[New Physics](https://en.wikipedia.org/wiki/Physics_beyond_the_Standard_Model)" predicted by various extensions of our 
current fundamental theory of Particle Physics, the [Standard Model](https://home.cern/science/physics/standard-model).

The topic of my dissertation is "A Search for Resonant Z' Production in the High-Mass Dielectron Final States". In this case, 
the hypothetical [Z' particle](https://en.wikipedia.org/wiki/W%E2%80%B2_and_Z%E2%80%B2_bosons) is predicted to decay into an electron 
and positron pair, and it is this signature that is searched for in the resulting debris of the LHC proton-proton collisions. The 
observation of several electron-positron pairs above what the Standard Model nominally predicts would count towards evidence of Z' 
production, and hence towards the possibility of "New Physics".

However, no significant deviations from the Standard Model prediction were observed, and as a result, multiple models predicting Z' 
physics at the LHC were able to be excluded. As this was the first measurement of this process during the upgraded 2nd experimental
run of the LHC, some of the best limits to date were able to be set on Z' production. If a Z' boson does exist, it must have an 
enormous mass, roughly 4,500 times the mass of the proton.

This project included but was not limited to the following steps:

- obtaining and cleaning data; <br>
- data visualization; <br>
- exploratory data analysis; <br>
- feature engineering; <br>
- maximum likelihood fits; <br>
- hypothesis testing; <br>
- model selection/evaluation; <br>
- monte carlo simulation.

For this analysis, I used the particle physics data analysis framework developed at CERN ([ROOT](https://root.cern.ch/about-root)) 
with C++ in Linux.


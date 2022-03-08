@def title = "Jack B. Muir"


![Jack in front of York Minster](/assets/jbmuir_long_compressed.jpeg)

I'm a Marie Skłodowska-Curie Fellow at the Department of Earth Sciences at the University of Oxford, and a Junior Research Fellow at Wolfson College, Oxford. I defended my PhD at the Caltech Seismolab in October 2021. I'm passionate about inverse problems — some of the projects I'm working on now are: imaging the Earth from near surface to the core; improving data captured at seismic arrays; and answering difficult questions about historical data sets. 

*You can contact me at [jack.muir@earth.ox.ac.uk](mailto:jack.muir@earth.ox.ac.uk)*

## Geologically-Informed Tomography

![Basin edge tomography using the community seismic network](/assets/researchfigs/levelset.png)

The creation of models of Earth structure through tomographic imaging is one of the cornerstones of modern geophysics. Typically, the tomographic problem is posed using basis functions or discretizations that are mathematically expedient, rather than that reflect some underlying knowledge of the geological structures present. In Muir & Tsai (2020) we discuss an inversion strategy that implements models defined by a combination of geometric primatives (for things like faults) and more complex boundaries defined by level set functions. We then applied this methodology to image the edge structure of the Los Angeles Basin in Muir et al. 2022, using the high density Community Seismic Network deployed by Caltech. We found a steeper and deeper Northeastern edge of the basin, with significant implications for potential ground motion amplification in that area.

## Wavefield Reconstruction for Displacement and Strain Fields

![Wavefield Reconstruction of the Ridgecrest Mw 7.1 Earthquake](/assets/researchfigs/ridgecrest_cv.jpg)

The bulk properties of the Earth are directly connected to seismic waves through the seismic wave equation, which depends on both time and spatial derivatives of the displacement. While time derivatives are now known accurately, obtaining accurate spatial derivatives is extremely difficult due to the sparse, irregular distribution of seismometers on the Earth's surface. I use a two step wavelet-curvelet analysis with preconditioning that promotes the expected smoothness of the wavefield to optimally interpolate seismic records, allowing for better calculation of spatial derivatives of the wavefield. In Muir & Zhan (2021) we discuss this analysis in the context of the displacement wavefield, and show how it can potentially drastically lower the amount of data required for applying wavefield techniques like eikonal tomography. In Muir & Zhan (2022), we further investigate how we can use the algorithm to combine Distributed Acoustic Sensing (DAS) and displacement sensors into a single data product.

## Bayesian Geophysical Methods

![Posterior for Oldham's P data with a jump](/assets/researchfigs/oldham.jpg)

Almost all geophysical inverse problems are ill-posed, and almost all geophysical data is noisy. Solving ill-posedness requires some *a priori* about the likely structure of the Earth, and accounting for data requires *a priori* knowledge about the distribution of data errors. The Bayesian statistical framework gives us the toolset to formally account for these assumptions, with the useful outcome that we obtain some understanding of the distribution of possible solutions, rather than just the best fitting one. A recent highlight from this line of research is our finding in Muir & Tsai (2020) that the discovery of Earth's core (Oldham, 1906) is robust when only the Primary arrival dataset is included — in this study we present some useful results for handling very noisy historical datasets by marginalizing across multiple sources of error.

## General Interest Writing

I am developing a portfolio of writing and other content aimed at a broader, non-technical audience — principally to highlight the very interesting world of solid Earth geoscience from a practitioner's perspective! The largest output of this is a collaboration with *Caltech Letters*, linked here — [Listening to the heartbeat of our planet](https://caltechletters.org/science/historical-seismology). I recently appeared in a podcast discussing my experiences with the John Monash foundation — [The General Sir John Monash Scholars podcast featuring Jack Muir](https://player.whooshkaa.com/episode?id=842498). I am also working through non-technical summaries for each of my publications, to be found linked on my publications page. 
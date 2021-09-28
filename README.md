# OSeMOSYS_start
This repo collects information and materials on how to get started with OSeMOSYS, for example when getting started with a course project, a Master's thesis or even a research project.

## Recommended literature
Below you can find some article that provide you background information on OSeMOSYS and will ease you start in using the modelling framework. We recommend to read the literature carefully. However, depending on your use case not all articles might be relevant for you.
- [Howells et al. 2011](https://doi.org/10.1016/j.enpol.2011.06.033) this paper discusses the design and development of the Open Source Energy Modeling System (OSeMOSYS)
- [Gardumi et al. 2018](https://doi.org/10.1016/j.esr.2018.03.005) this paper describes the role of an open-source energy modelling tool in the energy planning process and highlights its importance for society.
### Literature on specific models
Here we list some articles that describe or applied models built in OSeMOSYS.
- [Taliotis et al. 2016](https://doi.org/10.1016/j.esd.2015.12.001) TEMBA the OSeMOSYS model of Africa
- [Henke et al. 2021](https://doi.org/10.1016/j.energy.2021.121973) OSeMBE the electricity Model base for Europe

## Tools and interfaces
This section provides you links to tools and interfaces that you probably will need when using OSeMOSYS.
### Solver
- [GLPK](http://www.osemosys.org/uploads/1/8/5/0/18504136/glpk_installation_guide_for_windows10_-_201702.pdf), instructions on how to install the solver you need to run OSeMOSYS models. The instructions are for Windows, however there is also a dowload for Mac OSX and Linux on the same dowload page.
- If you notice that GLPK takes ver long to solve or have been recommended to use a more powerful solver than GLPK than there are the following options:
  - [Gurobi](https://www.gurobi.com/), proivdes free licenses for people in academia
### Version control
When building and in particular testing a model it is easy to loose track of what changes one has done in the data of the model. A good option to prevent a mess of files with names only the author (hopefully)understands, is version control. Initially it might feel like a burden, but on the long-run it pays back. Here a [tutorial how to get going with GitHub](https://coderefinery.github.io/git-intro/).
### Data handling
OSeMOSYS datafiles are simple `txt`files. However, once you start populating your model with technologies, fuels, and boundary constraints `txt`files become quickly unpractical.
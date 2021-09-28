# OSeMOSYS_start
This repo collects information and materials on how to get started with OSeMOSYS, for example when getting started with a course project, a Master's thesis or even a research project.

## Recommended literature
Below you can find some article that provide you background information on OSeMOSYS and will ease you start in using the modelling framework. We recommend to read the literature carefully. However, depending on your use case not all articles might be relevant for you.
- [Howells et al. 2011](https://doi.org/10.1016/j.enpol.2011.06.033) this paper discusses the design and development of the Open Source Energy Modeling System (OSeMOSYS)
- [Gardumi et al. 2018](https://doi.org/10.1016/j.esr.2018.03.005) this paper describes the role of an open-source energy modelling tool in the energy planning process and highlights its importance for society.
- [Niet et al. 2021](https://doi.org/10.1016/j.esr.2021.100650) covers the latest development of OSeMOSYS and the effort of building a community of practice.
### Literature on specific models
Here we list some articles that describe or applied models built in OSeMOSYS.
- **TEMBA** the OSeMOSYS model of Africa is used and described by[Taliotis et al. 2016](https://doi.org/10.1016/j.esd.2015.12.001) 
- **SAMBA** the OSeMOSYS model of South America is used and described by [Pinto de Moura et al.](https://doi.org/10.1016/j.esr.2017.06.002) and [Pinto de Moura et al.](https://doi.org/10.1016/j.enpol.2018.01.045).
- [Henke et al. 2021](https://doi.org/10.1016/j.energy.2021.121973) **OSeMBE** the electricity Model base for Europe

## Tools and interfaces
This section provides you links to tools and interfaces that you probably will need when using OSeMOSYS.
### Solver
- [GLPK](http://www.osemosys.org/uploads/1/8/5/0/18504136/glpk_installation_guide_for_windows10_-_201702.pdf), instructions on how to install the solver you need to run OSeMOSYS models. The instructions are for Windows, however there is also a dowload for Mac OSX and Linux on the same dowload page.
- If you notice that GLPK takes ver long to solve or have been recommended to use a more powerful solver than GLPK than there are the following options:
  - [Gurobi](https://www.gurobi.com/), proivdes free licenses for people in academia
### Version control
When building and in particular testing a model it is easy to loose track of what changes one has done in the data of the model. A good option to prevent a mess of files with names only the author (hopefully)understands, is version control. Initially it might feel like a burden, but on the long-run it pays back. Here a [tutorial how to get going with GitHub](https://coderefinery.github.io/git-intro/).
### Data handling
OSeMOSYS datafiles are simple `txt` files. However, once you start populating your model with technologies, fuels, and boundary constraints `txt` files become quickly unpractical. Therefore the python package **otoole** has been developed to allow the conversion into datapackages (a folder with one csv file per parameter) or excel file and back to datafile. **otoole** also allows to convert the output of different solvers, that are commonly some kind of text-format into a set of csv-files.
The documentation on how to install **otoole** and how to use it can be found [here](https://otoole.readthedocs.io/en/latest/).

## The model code and how to run it
### Model code
The OSeMOSYS code is available on [GitHub](https://github.com/OSeMOSYS/OSeMOSYS_GNU_MathProg/tree/master/src).
### Running a model
An explanation on how to run models is available in the [OSeMOSYS documentation](https://osemosys.readthedocs.io/en/latest/manual/Create%20a%20model%20in%20OSeMOSYS.html#how-to-run-osemosys-using-a-macos-operating-system).

## Help
- A good place to start searching when having questions is the [OSeMOSYS documentation](https://osemosys.readthedocs.io/en/latest/index.html).
- Many questions are already on the [OSeMOSYS forum](https://groups.google.com/g/osemosys). And if a question is missing please feel free to post it!
- If you have got the impression that there is something missing please feel free to raise an issue here on GitHub. But if you are already comfortable with the use of GitHub pull requests are welcome too.
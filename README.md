# Awesome FMI with stars

> A curated list of Functional Mock-up Interface (FMI) libraries, tools and resources.

Functional Mock-up Interface (FMI) is a tool independent standard to support both model exchange and co-simulation of dynamic models.
See the [official FMI website](http://fmi-standard.org/) for the official specification and more information about the FMI standard.

## Contents

* [FMI 2](#fmi-2)
  * [Libraries](#libraries)
    * [C](#c)
    * [C++](#c-1)
    * [Python](#python)
    * [Java](#java)
    * [MATLAB/Simulink](#matlabsimulink)
    * [Rust](#rust)
    * [Julia](#julia)
  * [Tools](#tools)
* [FMI 3](#fmi-3)
* [Community](#community)

## FMI 2

The latest (as of June 2024) stable release of the FMI 2 specification is `2.0.4`, released on 2022-12-1.
You can find the text of the FMI specification 2.0.4 at <https://github.com/modelica/fmi-standard/releases/tag/v2.0.4> ⭐ 352 | 🐛 55 | 🌐 C | 📅 2026-07-14 .
Unless noted otherwise, the tools and libraries listed are compatible with FMI 2.

### Libraries

Libraries to import, simulate and export FMUs (Functional Mock-up Units) that support FMI 2.

#### C

* [FMI Library](https://github.com/modelon-community/fmi-library) ⭐ 156 | 🐛 29 | 🌐 C | 📅 2026-07-03 - C library for import of FMUs. \[BSD]
* [FMU SDK](https://github.com/qtronic/fmusdk) ⚠️ Archived - C library for exporting FMUs. \[BSD]

#### C++

* [FMI4cpp](https://github.com/NTNU-IHB/FMI4cpp) ⭐ 110 | 🐛 10 | 🌐 C++ | 📅 2025-02-28 - FMI 2.0 implementation written in modern C++. \[MIT]
* [FMU4cpp](https://github.com/Ecos-platform/fmu4cpp) ⭐ 23 | 🐛 2 | 🌐 C++ | 📅 2025-12-03 - CMake/Github Actions template project for building FMUs in C++. \[MIT]
* [FMI++](https://github.com/fmipp/fmipp) ⭐ 20 | 🐛 3 | 🌐 C++ | 📅 2024-01-08 - C++ library for import and export of FMUs. \[BSD]

#### Python

* [FMPy](https://github.com/CATIA-Systems/FMPy) ⭐ 584 | 🐛 141 | 🌐 Python | 📅 2026-08-13 - Python package for loading and interacting with FMUs. It supports also the latest [System Structure and Parameterization (SSP standard)](https://www.modelica.org/projects). \[BSD]
* [PyFMI](https://github.com/modelon-community/pyfmi) ⭐ 226 | 🐛 17 | 🌐 Python | 📅 2026-08-14 - Python package for loading and interacting with FMUs, based on the FMI Library. \[LGPL]
* [PythonFMU](https://github.com/NTNU-IHB/PythonFMU) ⭐ 177 | 🐛 25 | 🌐 Python | 📅 2025-12-12 - Framework for exporting Python code as FMUs. \[MIT]
* [modestpy](https://github.com/sdu-cfei/modest-py) ⭐ 52 | 🐛 3 | 🌐 Python | 📅 2022-06-22 - Python package for parameter estimation in FMUs. \[BSD]
* [SimulatorToFMU](https://github.com/LBNL-ETA/SimulatorToFMU) ⭐ 45 | 🐛 14 | 🌐 Python | 📅 2022-12-23 - Python package that allows to export a memoryless Python-driven simulation program or script as a FMU. \[BSD]
* [qFMU](https://github.com/hyumo/qFMU) ⭐ 13 | 🐛 4 | 🌐 C | 📅 2023-10-26 - Generate standard LTI system FMUs through CLI \[BSD]
* [FMI++ Python Interface](https://pypi.python.org/pypi/fmipp) - Python interface for the FMI++ library. \[BSD, BOOST]

#### Java

* [FMI4j](https://github.com/NTNU-IHB/FMI4j) ⚠️ Archived - Java/Kotlin library for dealing with FMUs on the JVM platform. \[MIT]
* [javaFMI](https://bitbucket.org/siani/javafmi) - Java library for import and export of FMUs. \[LGPL3]

#### MATLAB/Simulink

* [FMIKit-Simulink](https://github.com/CATIA-Systems/FMIKit-Simulink) ⚠️ Archived - Import and export Functional Mock-up Units with Simulink. \[BSD]
* [Simulix](https://github.com/Kvixen/Simulix) ⭐ 42 | 🐛 8 | 🌐 C | 📅 2023-11-03 - A third-party Simulink tool to generate FMUs from Simulink models using the C-API. \[GPL3]
* [Simulink FMU Importing](https://mathworks.com/help/simulink/in-product-solutions.html)/[Export a Model as a Tool-Coupling FMU](https://mathworks.com/help/simulink/ug/_mw_54e936ec-2fa7-4418-be70-d99c8f91d2bd.html) - Out-of-the-box official support for FMU import and export (tool coupling) in Simulink. \[Commercial]
* [FMI Toolbox for MATLAB/Simulink](https://www.modelon.com/products-services/modelon-deployment-suite/fmi-toolbox/) - Toolbox with support for Simulink FMU Import/Export and MATLAB FMU import. \[Commercial]
* [matlab-fmu](https://sourceforge.net/projects/matlab-fmu/) - MATLAB Toolbox for Windows with support for import of FMUs for Model-Exchange and Co-Simulation as well as the export of MATLAB scripts as FMUs for Co-Simulation, based on the FMI++ library. \[BSD]

#### Rust

* [rust-fmi](https://crates.io/crates/fmi) - A Rust interface to FMUs (Functional Mock-up Units) that follow the FMI Standard. \[APACHE2/MIT]

#### Julia

* [FMI.jl](https://github.com/ThummeTo/FMI.jl) ⭐ 96 | 🐛 28 | 🌐 Julia | 📅 2026-07-09 - Library which integrates FMI and permits load, instantiate, parameterize and simulate FMUs seamlessly inside the Julia programming language. \[MIT]
* [FMIFlux.jl](https://github.com/ThummeTo/FMIFlux.jl) ⭐ 62 | 🐛 16 | 🌐 Julia | 📅 2026-05-02 - Library which offers the ability to setup NeuralFMUs, put FMUs inside any feed-forward NN topology and get a hybrid model trainable with a standard AD training process. \[MIT]

### Tools

For the official list of tools that support FMI 2, check <http://fmi-standard.org/tools/> .

* [λ-Sim](https://github.com/mbonvini/LambdaSim) ⭐ 56 | 🐛 1 | 🌐 JavaScript | 📅 2017-03-27 - Tool that converts FMU simulation models into REST APIs. \[MIT]
* [FMU-proxy](https://github.com/NTNU-IHB/FMU-proxy/) ⚠️ Archived - Framework that allows Functional Mock-up Units (FMUs) to be accessed through language independent RPC calls and that permits to transform a co-simulation FMU into a proxified version of the same FMU, so that each FMU can run in a separate process. \[MIT]
* [ROS fmi\_adapter](https://github.com/boschresearch/fmi_adapter) ⭐ 50 | 🐛 10 | 🌐 C++ | 📅 2026-05-21 - FMI support for [ROS](http://www.ros.org/), a flexible framework for writing robot software. \[APACHE2]
* [fmi\_adapter\_ros2](https://github.com/boschresearch/fmi_adapter_ros2) ⭐ 50 | 🐛 10 | 🌐 C++ | 📅 2026-05-21 - FMI support for [ROS2](https://index.ros.org/doc/ros2/), the new version of the Robot Operating System. \[APACHE2]
* [Unity-FMI-Addon](https://github.com/CATIA-Systems/Unity-FMI-Addon) ⭐ 48 | 🐛 10 | 🌐 C | 📅 2026-02-27 - FMI support for [Unity](https://unity3d.com/), a cross-platform game engine. \[BSD]
* [FMITerminalBlock](https://github.com/AIT-IES/FMITerminalBlock) ⭐ 8 | 🐛 4 | 🌐 C++ | 📅 2018-04-11 -  Two way interface between the FMI and IEC 61499-based controllers. \[BSD]
* [Dymola](https://www.dymola.com) - A modeling and simulation environment for Modelica, with full support for FMI. \[Commercial]
* [FMIGo!](http://www.fmigo.net/) - A set of tools for dealing with the FMI and SSP standards. \[MIT]
* [fmu-viewer](https://hyumo.github.io/fmuviewer-web/) - A simple FMU viewer in the browser

## FMI 3

The latest (as of June 2024) stable release of the FMI 3 specification is `3.0.1`, released on 2023-07-10 .
You can find the text of the FMI specification 3.0.1 at <https://fmi-standard.org/docs/3.0.1/> .
General information on the FMI 3.0 feature list can be found in <https://fmi-standard.org/faq/> .

Some of the projects listed in the previous section also support for FMI 3 :

* **Examples**:
  * [Reference-FMUs](https://github.com/modelica/Reference-FMUs) ⭐ 224 | 🐛 49 | 🌐 C | 📅 2026-08-12 : `3.0` examples FMUs are available, including examples for new co-simulation features such as scheduled co-simulation and early return in co-simulation.
  * [PMSFIT/FMI30TestFMUs](https://github.com/PMSFIT/FMI30TestFMUs) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2026-03-13 : Some examples FMUs based on the FMI 3.0 specification are available, including features such as binary variables.
* **Modelica:**
  * [Dymola](https://www.dymola.com) - support for FMI `3.0` is available, including arrays, terminals, icons, event mode and early return.
* **Python:**
  * [fmpy](https://github.com/CATIA-Systems/FMPy) ⭐ 584 | 🐛 141 | 🌐 Python | 📅 2026-08-13 - support for FMI `3.0` is available.
* **Julia:**
  * [FMI.jl](https://github.com/ThummeTo/FMI.jl) ⭐ 96 | 🐛 28 | 🌐 Julia | 📅 2026-07-09  - experimental support for FMI `3.0` is work in progress
* **Simulink:**
  * [FMIKit-Simulink](https://github.com/CATIA-Systems/FMIKit-Simulink) ⚠️ Archived - support for export of FMU `3.0` is available.
* **Formal models**
  * [FMI-VDM-Model](https://github.com/INTO-CPS-Association/FMI-VDM-Model) ⭐ 13 | 🐛 3 | 🌐 HTML | 📅 2025-07-28 - [VDM](https://en.wikipedia.org/wiki/Vienna_Development_Method) formal models for the FMI3.0 specification.

## Community

* [Stack Overflow](https://stackoverflow.com/tags/fmi) - Questions related to FMI in Stack Overflow.
* [Twitter's FMI Info and News](https://twitter.com/fmi_info) - Unofficial news account about the FMI Standard, FMI usage and FMI tools.
* [LinkedIn FMI Group](https://www.linkedin.com/groups/7477473/) - Open group to spread news and discuss topics w\.r.t. FMI.

## Contribute

Contributions are welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._

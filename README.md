# Awesome Flight-Software

I'm huge fan of flight software for satellites. I have been studying the topic for a while, understanding difference 
approaches and following different actors. This is a list of open-source flight software frameworks, and other 
resources, I have found across the years.

> **Note:** To the best of the authors' knowledge, these are all currently available open-source flight software 
> frameworks. If you are aware of any framework that is not listed here, please open an issue or submit a pull request.



## Frameworks

## List of Flight-Software Frameworks


| Framework                 | Main Developer                       | Scope                                              | Impl. Language         | License         | Repo |
| ------------------------- | -------------------------------------| -------------------------------------------------- | ---------------------- | ----------------| --------------------------------------- |
| core Flight System        | NASA                                 | HAL, OSAL, Middleware, Component Framework, Services    | C                      | Apache 2.0      | [https://github.com/nasa/cFS](https://github.com/nasa/cFS) |
| F Prime (F´)              | NASA JPL                             | Component Framework, Middleware, Services               | C++                    | Apache 2.0      | [https://github.com/nasa/fprime](https://github.com/nasa/fprime) |
| NanoSat MO Framework      | ESA                                  | Component Framework, Middleware, Services               | Java                   | ESA Open Source | [https://github.com/esa/nmf-mission-ops-sat](https://github.com/esa/nmf-mission-ops-sat) |
| CubedOS                   | Vermont State University             | Component Framework, Middleware, Services               | SPARK Ada              | GPLv3           | [https://github.com/cubesatlab/cubedos](https://github.com/cubesatlab/cubedos) |
| Outpost                   | DLR                                  | Middleware, Services                                    | C++                    |  MPL-2.0        | [https://github.com/DLR-RY/outpost-core](https://github.com/DLR-RY/outpost-core) |
| Flight Software Framework | University of Stuttgart              | OSAL, Middleware, Services                               | C++                    | Apache 2.0      | [https://egit.irs.uni-stuttgart.de/fsfw/fsfw](https://egit.irs.uni-stuttgart.de/fsfw/fsfw) |
| sat-rs                    | University of Stuttgart              | Middleware, Services                                    | Rust                   | Apache 2.0      | [https://egit.irs.uni-stuttgart.de/rust/sat-rs](https://egit.irs.uni-stuttgart.de/rust/sat-rs) |
| Adamant                   | LASP University of Colorado Boulder  | Middleware, Component Framework, Services               | SPARK Ada              | Apache 2.0      | [https://github.com/lasp/adamant](https://github.com/lasp/adamant) |
| Space ROS                 | NASA and Blue Origin                 | Middleware, Component Framework, Services                | C++ / Python           | Apache  2.0     | [https://github.com/space-ros/space-ros](https://github.com/space-ros/space-ros) |
| RODOS                     | University of Würzburg               | RTOS, Middleware                                        | C++                    | GPLv3           | [https://gitlab.com/rodos/rodos](https://gitlab.com/rodos/rodos) |


where: 
- HAL: Provides Hardware Abstraction Layer
- OSAL: Provides Operating-System Abstraction Layer
- RTOS/OS: Provides the Operating-System
- Middleware: Provides a Middleware for Inter-Process/Inter-Component Communication
- Component Framework: Defines how the Components should be implemented and ist behavior
- Services: Provides readily usable services, usually using the Component Framework




### Educational Frameworks
Projects developed for educational purposes.

| Framework                          | Main Developer                      | Impl. Language         | License         | Repo |
| ---------------------------------- | ------------------------------------|------------------------|-----------------|------|
| SmallSat Flight Software Framework | Costa Rica Institute of Technology  | C                      | MIT             | [https://github.com/olmanqj/sfsf](https://github.com/olmanqj/sfsf) |
| PyCubed                            | PyCubed Project                     | Python / CircuitPython | MIT             | [https://github.com/pycubed/software](https://github.com/pycubed/software) |




### Dead projects
A list of Frameworks that apparently have gone defunct :,(

| Framework                 | Developer                            | Scope                                              | Impl. Language         | License      | Mirrors |
| ------------------------- | -------------------------------------| -------------------------------------------------- | ---------------------- | ------------ | --------------------------------------- |
| Kobos                     | KubOS Corporation                    |                                                    | C / Rust               | Apache  2.0  | https://github.com/neo4reo/kubos <br> https://github.com/xbai9225/kubos/ |



## Reference Architectures

A list of reference architectures, in other words descriptions of how flight software architecture should be designed 
according to a particular organization, something like a blueprint.

- [ESA's SAVOIR](https://savoir.estec.esa.int/SAVOIROutput.htm) (Required to be in a ESA member state to access documentation 👎)
- [CCSDS CAST](https://ccsds.org/Pubs/811.1o1e1.pdf)


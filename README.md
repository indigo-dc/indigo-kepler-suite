# indigo-kepler-suite
A Kepler (https://kepler-project.org/) suite incorporating module for INDIGO-DataCloud project (https://github.com/indigo-dc/indigo-kepler-module.git)

# Installation
```sh
mkdir kepler.modules
cd kepler.modules
svn co https://code.kepler-project.org/code/kepler/releases/release-branches/build-area-2.5 build-area
git clone https://github.com/indigo-dc/indigo-kepler-suite.git
cd build-area
ant change-to -Dsuite=indigo-kepler-suite
ant run
```

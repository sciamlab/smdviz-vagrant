# SciamLab Modern Data Visualization Course Vagrant box

This is a sample Vagrant initialization project to create and configure the Vagrant box for the course.
It contains a bunch of prepackaged tools and libraries in addition to the course documentations

## Vagrant configuration
The provided Vagrantfile setup a base virtal machine using Virtualbox with 2 cores and 4Gb of RAM, running in a private network

To setup it clone this repo, and run vagrantup:

```shell
$: git clone https://github.com/sciamlab/smdviz-vagrant.git 
$: cd smdviz-vagrant
$: vagrant up 
```

## Configured software
The vagrant contains a bunch of preinstalled and configured software:

* PostgreSQL 10
* several data manipulation Bash CLI tools
* CSVKit tool
* CLI tool for BigML’s API
* Jupyter Notebook
* Apache Spark 2.1.0
* Apache Zeppelin 0.7.3
* Apache Superset 0.22.1

as well sample data useful for the course labs


## License
```
Copyright (c) 2018 SciamLab s.r.l.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

	http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

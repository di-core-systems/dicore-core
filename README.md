
# DiCORE Core Module #

----------
DiCORE (Distributed Cooperative Evolution) provides a solution for developers to __collaborated co-evolution__. The framework determines the kind of changes and the affected components in a business process and shares them with dependent clients. The framework aims to handle the co-evolution process by agents automatically.
This project implements the multi-agent system, which is the __main component__ of the DiCORE project and comprises two additional modules:

__DiCORE-CIA (Change Impact Analysis)__ 
supports to recognize changes and their consequences. In detail, it detects a change, categorizes the change, analyses the affected components.

__iCORE-CEC (Co-Evolution Coordination)__
realizes fully autonomous agent collaboration for service co-evolution.

----------
## How To Run ##

 1. Extract the contents of *src/* to your project folder
 2. Add the dependenies to your java project (*dicore-cia-graph-based-pattern*, *dicore-cia-asp*, *dicore-cia-behaviour*, and external libraries)
 2. Run *gradle* 

----------
## How To Run Test Scenario ##

 1. Run `$ StartServices ` in the project de/uniks/vs/scenario folder 
 2. Run `$ StartClientApplication ` in the project de7uniks/vs/scenario folder

----------
## Ext. Libraries Used ##

 - Clingo4j - https://github.com/lorislab/clingo4j
 - JGraphX - https://github.com/jgraph/jgraphx
 - Yaoqiang BPMN Editor - https://sourceforge.net/projects/bpmn/files/?source=navbar
 - Glassfish - http://www.oracle.com/technetwork/middleware/glassfish/overview/index.html
 
----------
## Authors ##
 

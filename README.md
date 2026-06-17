# pyares-directory
Welcome to the PyAres directory. This repository serves as a central locaiton for finding templates, examples, and implmentations of PyAres servcies for use with ARES OS.
## Templates 
Templates provide a preformated repository for setting up your service. All offical AFRL-ARES templates are availible from the [pyares-templates](https://github.com/AFRL-ARES/pyares-templates) master repository
| Name | Description | Source | License | 
|------|-------------|--------|---------|
|[PyAres Analyzer Template (Simple)](https://github.com/AFRL-ARES/pyares-templates/tree/Develop/pyares-template-analyzer-simple)| Simple PyAres Analyzer template for basic analysis logic | [AFRL-ARES](https://github.com/AFRL-ARES) | MIT | 
|[PyAres Analyzer Template](https://github.com/AFRL-ARES/pyares-templates/tree/Develop/pyares-template-analyzer)| PyAres Analyzer template. Implements analyzer logic as a class for more complex functionality| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT | 
|[PyAres Planner Template (Simple)](https://github.com/AFRL-ARES/pyares-templates/tree/Develop/pyares-template-planner-simple)| Simple PyAres Planner template for basic planning logic | [AFRL-ARES](https://github.com/AFRL-ARES) | MIT | 
|[PyAres Device Template (Simple)](https://github.com/AFRL-ARES/pyares-templates/tree/Develop/pyares-template-device-simple)| Simple PyAres Device template for basic devices| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT | 

## Example Implementations
| Name | Type | Description | Source | License | 
|------|------|-------------|--------|---------|
|[pyares-dataq-2008](https://github.com/AFRL-ARES/pyares-dataq-2008)| Device | PyAres Device for DataQ DI-2008 Dataloggers| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT |
|[pyares-ax-planners](https://github.com/AFRL-ARES/pyares-ax-planners) | Planner | Pyares interface for Meta's Ax Bayesian Optimization API| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT |
|[Latin-Hypercube-Planner](https://github.com/AFRL-ARES/Latin-Hypercube-Planner)| Planner | An iterative Latin hypercube planner| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT |
|[ARES-Print-Analyzer](https://github.com/AFRL-ARES/ARES-Print-Analyzer)| Analyzer | Computer vision based FDM print quality analyzer, based on the work of Ganitano et al. Meant for use with the [Educational ARES](https://github.com/AFRL-ARES/Educational-ARES) project| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT |
|[ARES-Print-Planner](https://github.com/AFRL-ARES/ARES-Print-Planner)| Planner | Simulated annealing planner for optimizing FDM 3d printing based on the work of Ganitano et al. Meant for use with the [Educational ARES](https://github.com/AFRL-ARES/Educational-ARES) project| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT |


## Demo/Development Tools
| Name | Type | Description | Source | License | 
|------|------|-------------|--------|---------|
|[pyares-demo-response](https://github.com/AFRL-ARES/pyares-demo-response) | Analyzer | A syntheic response surface made up of a mix of N-dimensional gaussians. Useful for testing out planners.| [AFRL-ARES](https://github.com/AFRL-ARES) | MIT |

# Contributing
If you have a PyAres based project you think would be useful to the community and would like it included here, please submit a Pull Request. Be sure to include a link to your repository. Services should **NOT** include any proprietary elements (code, data, etc.) that you are not licensed to redistribute. If your service depends on these elements consider implementing your service as an interface which relies on the user to have their own access approriately licensed resources.

# Disclaimer
The contents of this repository is intented for purely informational purposes. Inclusion does not imply the endorsement or fitness-for-purpose of any linked repository.

# Distribution
Distribution A: Approved for public release; distribution unlimited. AFRL-2026-2820

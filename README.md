# Diamonds Installation Guide
Automatic detection algorithm for *Drosophila melanogaster* activity. Adapted from https://github.com/kanglab/Sapphire.git

Created by Daniel Ward, Stephen Cini, Cole Morris, Bridget Sweeney, and Jeremiah Zartman

Department of Chemical and Biomolecular Engineering, University of Notre Dame

## Description
The Drosophila Individual Activity Monitoring Detection System (DIAMonDS) is a software with the capability to monitor fly activity and recognize certain milestones in the life cycle of a fly. This software was pioneered and discussed in a paper by Seong et al. (2020). An Epson Perfection V600 Scanner is used in collaboration with VueScan software to collect time lapse images to input into the DIAMonDS system. Additionally, independent timelapse video may be created from the scanner’s images using Fiji. These videos allow for manual detection of fly activity across a known period of time, with particular significance in comparing fly populations.

## Dependencies
A complete list of dependencies can be found in the environment.yml file. Use of Diamonds/Sapphire program does require Anaconda. 

## Installation Instructions
### Creating Conda Environment
1. Download this repository to local files. 
2. In terminal window, change directory to downloaded folder. Create and activate sapphire environment
```console
% conda env create -f environment.yml
% conda activate sapphire
````
3. To check that all dependencies are installed, use 
```console
% conda list
```
Manually verify that all dependencies match those in the environment.yml file. If not, manually install missing dependincy using 
```console
% pip install DEPENDENCY_NAME
```

### Using Sapphire
1. To activate Sapphire, use
```console
python sapphire.py
```
2. Refer to detailed protocol for more information.

## References
Ki-Hyeon Seong, Taishi Matsumura, Yuko Shimada-Niwa, Ryusuke Niwa, Siu Kang (2020). The Drosophila Individual Activity Monitoring and Detection System (DIAMonDS). eLife 9:e58630. doi.org/10.7554/eLife.58630 

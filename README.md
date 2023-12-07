# SdoAnalysisToolkit_DemoData
Extended Dataset used for SDO Analysis in the Paper

This repository has been spun off from the SDO Analysis Toolkit to reduce the download size of the main toolkit. 

**INSTALLATION INSTRUCTIONS:** 

1. Clone for download the full SDO Analysis Toolkit from https://github.com/GiszterLab/SdoAnalysisToolkit

2. Clone or download this repo (~400 MB) to the local drive. 

3. Place (merge) the contents of this repo, the directory '../demoData/' into the SDO Analyis Toolkit '../demoData/' directory.

4. Clear the variable space within MATLAB using the '$clear' command. (This will avoid any issues with variables called 'xtData' already existing within the workspace.)

5. Run the script 'concatenate_xtData.m' found within this directory. When prompted by the UI to select files, select 'xtDataTrial01.mat', 'xtDataTrial02.mat', ... 'xtDataTrial22.mat' (i.e., 22 files). This script will combine these files in the directory into a single variable, 'xtData', and will save this structure within the '.../demoData/' directory as '../demoData/xtData.mat' (This file will be ~400 MB.)

6. Run the SDO Analysis Toolkit as before (e.g., 'sdoAnalysis_demo.mlx'). When prompted to load 'xtData', direct the UI towards the newly created 'xtData.mat' ~400MB file in the '../demoData/' directory within the SDO Analysis Toolkit (as in Step 3). When prompted to load 'ppData', load the 'ppData.mat' file from within the same directory. Note that 'ppData.mat' is a file which was original downloaded from this (SdoAnalysisToolkit_DemoData) directory.

7. After successsful generation of the (concatenated) 'xtData.mat' structure within the main SDO Analysis Toolkit folder, this demoData directory can be deleted from the local drive. 


# Rice_et_al_2025
Contains all data used for the toluene proof of concepts studies using rodent primary cortical cells and human iPSC (SynFire) cells.
This repository contains two folders; RMDs and Raw_Data folders. 
The RMDs folder contains: 
Toluene_PreProcessing_Rodent.RMD: Contains all preprocessing steps to calculate weighted mean firing rate and the number of active electrodes for all rodent data. Input: all Rodent raw csv files and the MaestroExperimentalLog_Ontogeny.csv file. Output: Preprocessed_file_Rodent.csv.
Toluene_PreProcessing_SynFire.RMD: Contains all preprocessing steps to calculate weighted mean firing rate and the number of active electrodes for all SynFire data. Input: all SynFire raw csv files and the MaestroExperimentalLog_Ontogeny.csv file. Output: Preprocessed_file_SynFire.csv.
Toluene_Normalizing_Plotting_Rodent.RMD: Contains all normalizing and graphing steps. Input: Preprocessed_file_Rodent.csv. Output: Normalized weighted mean firing rate and normalized number of active electrodes line graphs for rodent data.
Toluene_Normalizing_Plotting_SynFire.RMD: Contains all normalizing and graphing steps. Input: Preprocessed_file_SynFire.csv. Output: Normalized weighted mean firing rate and normalized number of active electrodes line graphs for SynFire data.
The Raw Data folder contains: 
Rodent Folder: all spike list csv files for the Rodent data and a MaestroExperimentalLog_Ontogeny.csv which serves as a meta file.
SynFire Folder: all spike list csv files for the SynFire data and a MaestroExperimentalLog_Ontogeny.csv which serves as a meta file.

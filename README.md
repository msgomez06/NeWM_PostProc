# NeWM_PostProc
Repository for Global Forecasting of Tropical Cyclone Intensity Using Neural Weather Models
This repository is organized as follows:

## Directory Structure

#### 01_Backend/
_Contains scripts for interfacing with IBTrACS, ERA5, and neural weather model outputs. Handles a significant portion of the workflow and provides utilities._
> metrics.py <br>
> utils\
>> constants.py <br>
>>  dat_to_xr.py <br>
>>  data_lib.py <br>
>>  date_maker.py <br>
>>  ERA5_dler.py <br>
>>  ML_functions.py <br>
>>  toolbox.py <br>

#### 02_Data_Processing/
_Includes scripts for preprocessing tracks and associated data._
- track_preprocessing_reanalysis.py
- track_preprocessing_newms.py
- data_preprocessing.py

#### 03_Models/
_Includes the scripts where model architectures are defined._
- baselines.py

#### 04_Training_Scripts/
Contains helper functions and utility scripts.
- convolutional_model_runner.py
- linnear_model_runner.py

#### 05_Analysis_Scripts/
Scripts for analyzing data and model results.
- case_studies.py
- case_study_animation.py
- dropout_curves.py
- histogram_maker.py
- model_evaluation.py
- tex_pairs.py
- track_displacement_analysis.py

Each script is modular and documented to facilitate easy understanding and integration into larger projects.

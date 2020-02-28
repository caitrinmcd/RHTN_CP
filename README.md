# RHTN_CP
Resistant hypertension and controlled hypertension computable phenotypes.  
Each of these comptuable phenotypes contain multiple steps.  
The codes are based on data in the PCORnet Common Data Model.  

The codes use the antihypertensive medication maps available at github.com/caitrinmcd/AntiHTNMedClassification

The codes should be run in the following order and may need modifications or cleaning depending on your data structure:

1) RHTN_1_1_MappingRXnormvMap_03042019
2) RHTN_1_2_MappingRxNormvMerge_03012019
3) RHTN_2_a_Procedure codes v1
4) RHTN_2_b_Formatting_Data_withQC_03042019
5) RHTN_3_Exposure_Merge_RxNorm_v09262019
6) RHTN_4_Tables_v03052019_RxNorm or RHTN_5_Exclusion_and_Merges_v3.5.2019
7) RHTN_5_Exclusion_and_Merges_v3.5.2019 or RHTN_4_Tables_v03052019_RxNorm

The order of the last two codes will depend on if you want to add the exclusion criteria to your RHTN and/or controlled HTN definitions.

These codes were created by Caitrin W. McDonough; the manuscript describing these codes is currently under review.

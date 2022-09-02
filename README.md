# DL-Project
***by 
NINAD MHALGI and ABICHAL GHOSH***

The file "DL_Midsem_U2Net.ipynb" contains the implementation of UNet, whereas "Final_DL_Compre.ipynb" contains the implementation of U2Net Compre Final 

The ipynb notebook contains one of the possible training and test combination which is
      
      trained - ECSSD, validated - ECSSD
      
However, for the comparitive study, the following combinations have been used

      trained - ECSSD, validated - ECSSD
      trained - ECSSD, validated - MSRA
      trained - ECSSD, validated - DUTS
      trained - MSRA, validated - ECSSD
      trained - MSRA, validated - MSRA
      trained - MSRA, validated - DUTS
      
In order to obatain all the combination results, the datasets and models have been provided in the form of google drive link

If one wants to train a new model on a new dataset follow the steps -

      1 download the dataset zip file
      2 unzip the file
      3 set the train image and mask pathway to the intended
      4 run
      
If one wants to validate a pretrained model, follow the steps -

      1 skip to validation
      2 download the intented pretrained model file from google drive link
      3 load the pretrained model
      4 run
      
If one wants to validate a model on a different test/validation set, follow the steps - 

      1 download the validation dataset zip file
      2 unzip the file
      3 skip to the validation image and mask path declaration
      4 change the declaration to intented
      5 run

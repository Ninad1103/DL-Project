# DL-Project

The ipynb notebook contains one of the possible training and test combination which is
      
      trained - ECSSD, tested - ECSSD
      
However, for the comparitive study, the following combinations have been used

      trained - ECSSD, tested - ECSSD
      trained - ECSSD, tested - MSRA
      trained - ECSSD, tested - DUTS
      trained - MSRA, tested - ECSSD
      trained - MSRA, tested - MSRA
      trained - MSRA, tested - DUTS
      
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

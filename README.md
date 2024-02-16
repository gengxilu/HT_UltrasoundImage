# HT_UltrasoundImage

To download the sample of ultrasound image data: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/GQDA01

1. Test Environment: Windows 11 computer with an Intel i9-13900k processing unit and NVIDIA RTX 4090 graphics processing unit. The model development platform was Python 3.10 with the PyTorch (version 2.10; pytorch.org) and CUDA (version 12.1) deep-learning framework.
   
2. System requirements:
   Python 3.10; Python packages: Pytorch for Python, Numpy, scikitlearn, Matplotlib.  
   (Optional, Recommended) Nvidia GPU with CUDA support. If not available, change the 'device' to 'CPU'. This will lead to slightly longer training and running time of the machine learning model. 

3. To run the demo:
   1. Download all files in the repository and the sample of ultrasound image data from the Harvard Dataverse using the above link (file size ~2.5GB). Unzip the Ultrasound image data. 
   2. Run the Python script directly. Make sure the data path is correct. It is in the Python notebook style to include output from the test environment.
   3. Expected output is already included in the Notebook file. The outputs such as 'Loss in test', and mean error 'MeanE_CNN' should vary slightly due to the random selection of training and testing data. The average processing time per image can vary largely due to the running system specs.
   4. In the test environment listed above, the run time of this demo is usually within 15 minutes.
   5. To run your data with this script, make    

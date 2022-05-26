The lstm.ipynb was run on Google Colab, and the required files were placed in Google Drive. Colab was mounted with the file location of the required csv in Google Drive. 

Steps to run lstm.ipynb:
1. Place the Inshorts_Cleaned_Data.xlsx in your Google drive and note down the path. 
2. Replace the path to the xlsx file in the following command:
reviews = pd.read_excel("PUT YOUR PATH HERE")
3. The checkpoint file also gets stored in Google drive. Change the path accordingly and then replace the path in the following lines:
checkpoint_path = "PUT YOUR PATH HERE"
Note: The model gets checkpointed and stored in a file with .ckpt extension. 
4. Run the cells of the ipynb notebook one after the other. 

Note:
This ipynb runs on TensorFlow 1.13.2. The code in the ipynb installs this version of TensorFlow automatically. 
The code runs for 50 epochs, and each eroch takes 30-35 mins to execute. 
The ROGUE scores take arounf 8-10 hours to completely execute. 
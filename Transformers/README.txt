The Transformer.ipynb was run on Google Colab, and the required files were placed in Google Drive. Colab was mounted with the file location of the required csv in Google Drive. 

Steps to run Transformer.ipynb:
1. Place the data.xlsx in your Google drive and note down the path. 
2. Replace the path to the xlsx file in the following command:
data_unprocessed_news = pd.read_excel('/content/drive/MyDrive/Transformers/data.xlsx')
4. Run the cells of the ipynb notebook one after the other. 

Note:
The code runs for 150 epochs, and each epoch takes 2-3 mins to execute. 
The ROGUE scores take around 8-10 hours to completely execute. 

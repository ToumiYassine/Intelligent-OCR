# Intelligent-OCR
Intelligently Extract Text &amp; Data from Document with OCR NER

We will explain the stages of the project :

- You should install tesseract from the web site "https://tesseract-ocr.github.io/tessdoc/Downloads.html" and install all the packages in the file "requirementstxt' -->  pip install -r requirements.txt
-  The 'Pytesseract.ipynb' notebook is  used to extract the text from the invoices.
- The 'Data_Preparation.ipynb'  notebook is used to transform all the texts extracted from the invioces in the form of a table with their labels like O, I, Org, Web,......
- The 'Data_Preprocessing.ipynb' notebook is used to clean , convert to spacy format and split to train and test dataset.
- The 'Predictions.ipynb' notebook is used to train and  predict the cataegorie of the text like Web , Phone , Name , Org ... , the output is a two folders : best model  and last model
- The 'Document_scanner.ipynb' notebook is used to scan the input image and resize .
-For the deployment you should install Flash , download the Zip file 'flask deploy' , extract it  and run the main.py 

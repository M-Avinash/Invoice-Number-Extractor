# Invoice-Number-Extractor
A simple script to extract invoice numbers from Invoice PDF's. 

The Script uses tesseract OCR and Pytesserct wrapper to do the text extraction.
Once the text has been extracted I use N-grams and specifically Trigrams.

The approach is to find trigrams starting with the string "invoice". I have added some rules
to filter out unwanted trigrams and zero in on the Invoice Number. This approach can be extended 
to identify other fields of interest such as Total amount, Due date, Order Number, Order date Etc. 

Identifying addresses will not be possible with this script.


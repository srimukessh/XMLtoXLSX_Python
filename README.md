# XMLtoXLSX_Python
Parse XML and export it to XLSX


This [link](https://www.sec.gov/Archives/edgar/data/1484018/000148401818000039/0001484018-18-000039.txt) shows a filing (form N-CEN) of an ETF with the SEC. The XML block of this link is shown in "test2.xml"

This code (Python Jupyter Notebook - "xml2xlsx.ipynb") parses through the XML block of the link and retrieves and writes the authorized participants on a .xlsx. (Output file in this case is "List of Authorized Participants.xlsx")

Python Modules Used:
1. The Element Tree module for XML parsing 
2. xlsxwriter module for writing the records of interest in an Excel document (.xlsx format)

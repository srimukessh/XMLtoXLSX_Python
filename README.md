# XMLtoXLSX_Python
Parse XML and export it to XLSX


This [link](https://www.sec.gov/Archives/edgar/data/1484018/000148401818000039/0001484018-18-000039.txt) shows a filing (form N-CEN) of an ETF with the SEC. The XML block of this link is shown in 'test2.xml'

This code parses through the XML block of the link and retrieves and writes the authorized participants on a .xlsx. 

The Element Tree module for XML parsing and xlsxwriter module for writing the records of interest in an Excel document are used here.

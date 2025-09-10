# Python Project 14: PDF Merger Tool 📄🧠  

## 📌 Problem Statement:  
Create a Python script to merge multiple PDF files into a single document — useful for reports, portfolios, or combining scanned pages.

## 🧠 What You'll Learn:  
- Using PyPDF2 library  
- File handling and automation  
- Creating clean, merged output PDFs

## ✅ Python Code:  
```
import PyPDF2
import os

List of PDFs to merge
pdfs = ['file1.pdf', 'file2.pdf', 'file3.pdf']

merger = PyPDF2.PdfMerger()

for pdf in pdfs:
    merger.append(pdf)

merger.write("merged_output.pdf")
merger.close()
```

## 📤 What It Does:  
1. Takes input PDFs  
2. Merges them in order  
3. Creates a single combined file

## 🛠️ Requirements:  
bash
pip install PyPDF2


## 🔧 Try Modifying:  
- Add GUI using Tkinter  
- Sort files by name or date  
- Allow user input for file selection

## 💡 Use Cases:  
✅ Merge invoices or receipts  
✅ Combine chapters into a single book  
✅ Send bundled project documents 
✅ Combine chapters into a single book  
✅ Send bundled project documents  

# PDF Splitter (Google Colab)

A simple Python mini project that splits a PDF into two parts at a user-specified page using PyPDF2. This version is made to run entirely in Google Colab.

## Features

- Upload PDF via Colab
- Specify page number to split
- Download the two resulting PDFs

## Instructions

1. Run the cell to install PyPDF2
2. Upload your PDF using `files.upload()`
3. Call the `split_pdf()` function with your file name and split page number
4. Download split files using `files.download()`

## Example

```python
split_pdf("sample.pdf", "output", split_page=5)

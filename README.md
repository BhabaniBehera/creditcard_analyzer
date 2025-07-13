# creditcard\_analyzer

This code converts the encrypted pdf statements into a excel file having a detailed sheet and a summary sheet.

## Requirements

* Python 2.7
* Apache PDFBox Jar 2.0.6

## Configuration

Configuration is provided in config.ini:

* PDF\_FILE\_PATH: Path of encrypted pdf file
* PDFBOX\_COMMAND: Should not be modified, unless you want a specific encoding
* FILE\_NAME\_PREFIX: Output file name

## Usage

Edit the configuration in config.ini and execute "**python parser.py**". The excel file with extension .xlsx will be created.



Test comment


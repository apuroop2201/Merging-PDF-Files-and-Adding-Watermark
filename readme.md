**PDF Merger and Watermarker
This is a Python script that allows you to merge multiple PDF files into a single PDF and add a watermark to the merged PDF.

Requirements
Python 3.x
PyPDF2 library (pip install PyPDF2)
How to Use
Clone this repository or download the pdf_merger_watermarker.py script.

Place the PDF files you want to merge into the same directory as the script.

Optionally, add the watermark file (a PDF with a transparent background) into the same directory if you want to apply a watermark.

Open a terminal or command prompt, navigate to the directory containing the script and the PDF files.

Run the script with the following command:

bash
Copy code
python pdf_merger_watermarker.py
The script will prompt you to provide the names of the PDF files you want to merge. Separate each file name with a space.

If you want to add a watermark, the script will ask you to enter the name of the watermark PDF file.

The merged and watermarked PDF will be saved as merged.pdf in the same directory.

Notes
The watermark PDF should ideally have a transparent background to avoid covering the original content.

Ensure that the PyPDF2 library is installed before running the script. If not installed, run pip install PyPDF2.

This script is tested with simple PDF files. Complex PDFs with advanced formatting or interactive elements may not be fully supported.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to customize the README.md file further, adding more details or instructions specific to your project. The README.md file serves as documentation for users to understand how to use the script and any important considerations or limitations.

# PDF_Splitter <br>
### This is python code for PDF Splitter. <br>

# Usage
#### 	1. Download the above given "Research.pdf"(https://github.com/Sukanya-29/PDF_Splitter/blob/main/Research.pdf) file. <br>
#### 	2. Upload it in the folder section of above given PDF_splitter_code.ipynb(https://github.com/Sukanya-29/PDF_Splitter/blob/main/PDF_splitter_code.ipynb). <br> OR <br> Set the path for input file and enter the path in the file.

# How It Works <br>

#### **This function takes three arguments:**
- **`input_pdf`**: The path to the input PDF file.  
- **`output_dir`**: The directory where the split PDF files will be saved.  
- **`split_page`**: The page number where the PDF will be split.

#### **The function performs the following steps:**
- Checks if the output directory exists and creates it if it doesn't.  
- Reads the input PDF file.  
- Splits the PDF into two parts based on the specified page number.  
- Saves the two parts as `part1.pdf` and `part2.pdf` in the specified output directory.


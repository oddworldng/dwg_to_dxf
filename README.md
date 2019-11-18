# Convert DWG to DXF

## Description

Python script to convert DWG (AutoCAD) to DXF file using TeighaFileConverter (ODA File Converter) and subprocess library.

## Requirements

Install [ODA Converter](https://www.opendesign.com/guestfiles/oda_file_converter) (formerly Teigha Converter) and add the installation path to the environment variable.

## Configuration

Edit `dwg_to_dxf.py` file and change this variables by yours:
* TEIGHA_PATH: If the environment variable is defined just use "ODAFileConverter".
* INPUT_FOLDER: Input folder where DWG files are located.
* OUTPUT_FOLDER = Output folder where you want to save DXF files (usually is the same that INPUT_FOLDER).
* OUTVER: Output version (ACAD9, ACAD10, ACAD12, ACAD14, ACAD2000, ACAD2004, ACAD2007, ACAD20010, ACAD2013, ACAD2018).
* OUTFORMAT: Output format (DXF).
* RECURSIVE: Read recursive subfolders? (0, 1).
* AUDIT: Audit every input DWG file? (0, 1).
* INPUTFILTER: Input filter (*.DWG, *.DXF).

## Authors
* **Andres Nacimiento Garcia**, computer engineer at [University of La Laguna](https://ull.es/). <andresnacimiento[at]gmail[dot]com>

## Contributors
* **Mariano Sanz**, cartographer. <majafrades[at]gmail[dot]com>

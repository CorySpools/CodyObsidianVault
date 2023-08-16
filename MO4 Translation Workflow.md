# Overview

1. On a Windows computer, MO4 rvdata2 files are converted into YAML files using ruby scripts.
   ![[Pasted image 20230815203755.png]] 
    ![[Pasted image 20230815203812.png]]
2. YAML files are converted into CSV (Comma-Separated Value) files.
   ![[Pasted image 20230815204534.png]]
3. CSV files are uploaded into Google Sheets, where they are much easier to edit.
   ![[Pasted image 20230815204739.png]]
4. Translation members will use Google Sheets to log their translations. A separate column will be added for the translated text. Adjustments can be made if someone wants to use a different editor. The important thing is the structure of the file (columns, rows, text encoding).
   ![[Pasted image 20230815204850.png]]
5. After Translation is completed, the CSV will be downloaded to the Windows computer.
   ![[Pasted image 20230815204917.png]]
6. The CSV files will be converted back into YAML files.
7. The YAML files will be converted back into MO4 rvdata2 files.
8. The rvdata2 files will be ready to use or be further edited using RPGMaker.
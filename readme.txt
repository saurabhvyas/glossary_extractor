This project requires jupyter notebook installed and uses python 2.7 

If you are using a different python environment , please see python virtual environment package


Step 1 : using pdftotext terminal commnad ( inbuilt in ubuntu ) , extract glossary from a pdf that you wish to extract concepts from , for this you have to see the range of glossary pages , eg. if it's 330 - 340 then type in 

 pdftotext -s page no. -f page no.  input.pdf output.txt 

repeat , this for each pdf , and then concatenate all output .txt files into a single .txt , let's call this final.txt 

Step 2: now type , jupyter notebook in the root of this folder , this will open the glossaryv4 file , then you can change path to point to final.txt , I have commented out the code in that file

this will produce a final .txt will with all bigrams, and noise removed to as much as possible.


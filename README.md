# PowerShell File Automation 

## Apex to Drop Preview
This program searches , selects, and presents a list of files that include a given account number in it's name. 

A .txt file contains a list of account numbers, one per line. Apex_to_drop_preview takes that list of account numbers, then searches a given folder for files that contain that account number in it's name. If no match is found, that account number is returned with NO MATCH. If a match is found, the name of the file and file path is listed. At the end, the number of files found is listed. 

The goal of this script is to make sure the program is selecting the correct files, to make sure my files are named correctly, and to make sure a matching file exists. 


## Apex to Drop 
Once you are happy with the preview results, run the Apex_to_Drop code. 

This uses the same .txt file with account numbers listed. The program selects matching files and account numbers and copies that file into a new folder. It also lists if any files were skipped, missing, and the total number of selected files. 

The goal of this script was to streamline the process of having to search a large folder for over 70 account numbers individually to then upload to an image processing application. With this script, I can now use the destination folder to select all the matching account numbers at once and easily upload to our application. It also offers a 'check' to make sure my files are named properly, I am not forgetting to upload an account, and keeps a record of which files I have uploaded. 

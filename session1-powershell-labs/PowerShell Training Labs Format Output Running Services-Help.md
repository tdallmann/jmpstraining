# Lab Help Compare one.txt and two.txt and display the Differences

## SYNOPSIS
Compare two files - one.txt and two.txt and display the differences between the files using PowerShell

## DESCRIPTION
In the PowerShell console, compare the contents of the two files included with this lab - one.txt and two.txt - display only the differences.

Then compare the files and display both the differences and the matches

Do not open the txt files.

* Are the files different?
* What is the same between the content in files?


## EXAMPLES

### EXAMPLE 1
Use PowerShell to compare one.txt and two.txt  `compare-object -referenceobject one.txt -differenceobject two.txt`


![Differences between two files](compare-object-differences.png)

### EXAMPLE 2
Compare the content of the files and display both differente lines and similar lines `compare-object -referenceobject (get-content one.txt) -differenceobject (get-content two.txt) -includeequal`

![Different lines in two files](compare-object-content-differences.png) 


## NOTES
Please use the examplea as needed to work through the Labs. Some of the examples in the earlier labs may directly provide the solution
you are looking for - as we progress this may not be the case and you may need to work with others around you or build on what has been
presented in previous sessions to work through the labs.

While you may find some results in Google that will get you the answer you seek - please try not to jump right to the Internet to collect
the answers to the labs - working out the problem with the tools mentioned in the session and previous lab documents and working with 
colleagues will also help you work through the labs. 


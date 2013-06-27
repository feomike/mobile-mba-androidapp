# MMBA Project - JSON To CSV Transformer
 
# **Pre-requisite** 
	The project requires java,maven to be set in the classpath before you could run the utility and 
	also make sure all the files need to be converted into csv have to be in the input folder.

## *** Build the project***
*	mvn clean package

## **Command to run the utility program** 

* 	java -jar mmba-1.0.jar \<sourceFolder\> \<destinationFolder\> \<Delimiter\> \<convertToJsonFlag\> \<formatJsonFlag\>

###	arguments:
*	sourceFolder -> source location (sub directories allowed)
*	destinationFolder -> destination folder (two files will be created with named samknows.<timestamp>.json/csv)
*	delimiter(optional) -> defaulted to ~
*	convertToJsonFlag(optional) -> true/false
*	formatJsonFlag(optional) -> true/false
*	Example: java -jar mmba.jar C:\Samknows\data\json C:\Samknows ~ true true

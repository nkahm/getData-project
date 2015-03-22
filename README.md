# getdata-course-project
Course project for "Getting and Cleaning Data" coursera MOOC course.

The R script here is in [run_analysis.R](run_analysis.R)

The parameters required for the script are listed at the top: 
* URL (download link), 
* DIR (data directory), 
* TIDY_FILENAME (tidy.txt by default), 
* AGGREGATED_FILENAME (aggregated.txt by default).

If data directory doesn't already exist in current working directory, script will firstly download and unpack data. Then it will create tidy datasets and save them to two text files.

A codebook that explains the various parts of the R script is available here [CodeBook.md](CodeBook.md)

Getting-and-Cleaning-Data
=========================

## Script description

The script called run.analysis.R was created to merge the test and training sents together.

Prerequisies for the script as follows:

1. UCI HAR Dataset must be extracted
2. UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.




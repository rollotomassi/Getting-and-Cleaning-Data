
run_analysis.R description

First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".

Make sure the folder "data" and the run_analysis.R script are both in the current working directory.

Second, use source("run_analysis.R") command in RStudio.

Third, you will find two output files are generated in the current directory:

        merged_data.txt (7.9 Mb): it contains a data frame called cleanedData.
        data_means.txt (220 Kb): it contains a data frame called result.

Finally, use data <- read.table("data_means.txt") command in RStudio to read the file.
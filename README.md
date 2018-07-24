Data for Machine Learning for Good
====

This repo's main function is storing the data for the [Introduction to Machine Learning for Good](https://github.com/DeltaAnalytics/machine_learning_for_good) course.

Most people will never directly interact with this repo. There is a shell script that automatically pulls this repo into the main repo.

If shell script does not work, download a zipped copy of the repo, unzip it, and move the data file into the course folder.

The repo also contains the code to download and munge data from the KIVA API. This is used when you want to switch to a different country. Run `get_kiva_data.ipynb` to call KIVA API and save an updated csv.

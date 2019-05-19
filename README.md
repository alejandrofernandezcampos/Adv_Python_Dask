# Adv_Python_Dask
The objective is to rewrite the Bike Sharing analysis done in the Python for Statistical Programming subject using Dask data structures and ecosystem instead of plain pandas.


After some EDA and data cleaning, diffetent machine learning methods are used withing the Dask distribited computing framework. 

The final pipeline takes two Dask Dataframes, one with predictos and other with the label, performs dummification of the selected categorical variables, scaling of the numerical ones and fit a random forest model with the pre-selected parameter resulting from GridSearch.

Future work on the pipeline should be done to include the raw data and perform the precleaning work of removing nulls if any, remove outlayers and automatically separate features from label.

A final step for the pipeline would be implementing GridSearch of model parameter within the pipe.

A future step for dask preprocessing would be run the client job on a cluster of computers.

Thanks to Juanlu001 for proposing the exercise.

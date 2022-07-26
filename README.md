# LinearRegressionsPractice
Team macro looks to improve their algorithm

Macro 2.* - linear regression
Macro 3.* - random Forest

I think that this is the next logical step for our algorithm.  It is a slight step up, but nothing super crazy.  Maybe next we should try random forests then neutral netowrks, ect.

You will need jupyter notebook to run the files. JNB is cleanest run from anaconda navigator: https://docs.anaconda.com/anaconda/install/

The data that I used is in this reposatory, but it would probably be easier to manage is you just emailed me at arjunsohur@gmail.com for the files.  You will need to upload these files into JNB to access them easily.



Current notes/working points:
 - [Macro 2.3] You can't just enter raw data and get a raw price prediction becasue the algorithm uses rescaled data.  For example, if I had a data_set = [3,6,7,8] and expected to get price 4.00, I would have to data_set = scale.fit_transform(data_set) which would make the data have mean 0 and standard deviation 1.  The program won't accept the original array becasue the data needs to be preprocessed.  It keeps the integrity of the data, but the prediction price won't be around 4, it would be something according to the resclaed values.  ---  July 25 2022
 - [Macro 2.3] What exactly fit, transform, and fit_transform are doing.  ---  July 25 2022
 - [Macro 3.1] Working on extrapolating data.  I'll maybe add a lasso regression to it when data goes out of bounds.

# Predicting West Nile Virus Group Project



## Repository Contents

* assets
  * spray.csv
  * test.csv
  * test.csv
  * weather.csv
* code
  * project-4-wnv-nb1.ipynb
  * statistical-wnv.ipynb
  * project-4-wnv-nb3.ipynb
* output
  * test_weather_daily.csv
  * train_spray_under3miles.csv
  * train_spray_weather_avg.csv
  * train_weather_daily.csv
* deliverables
  * presentation.pdf
  * project_tasks.pdf

## Datasets

Initial datasets were provided by the Chicago Department of Public Health and are found in the **assets** directory.

* **spray.csv**: Data concerning spray locations and datatimes for 2011-2013.
* **test.csv**: Mosquito testing dataset to be used for final model predictions.  Kaggel prediction submissions are based on this feature set.  Years covered, 2008, 2010, 2012, 2014.
* **train.csv**: Mosquito testing dataset to be used for fitting models. Years covered, 2007, 2009, 2011, 2013.
* **weather.csv**:  Weather data from 2007-2014 for May-October. Data is provided for two weather stations.

Generate datasets used for actual fitting and testing are found in the **output** directory.  Note the train_weather_daily.csv and test_weather_daily.csv are the two files ultimately used for EDA and modeling. 

* **test_weather_daily.csv**: Test data merged with Station 1 weather data.
* **train_spray_under3miles.csv**: Training data with spray information for traps within thhree miles of spray location.
* **train_spray_weather_avg.csv**: Training data with spray information and average monthly weather data.
* **train_weather_daily.csv**: Training data merged with Station 1 weather data.

##  Code

Project code is broken out into three jupyter notebooks that can be found in the (_surprise_) **code** directory.  Please note that the notebooks can be executed in any order.  The datasets that are used exist in the **output** directory and do not need to be re-generated.

* **project-4-wnv-nb1.ipynb**: Asset processing and dataset generation
* **statistical-wnv.ipynb**: EDA
* **project-4-wnv-nb3.ipynb**: Modeling


## Extra

A project task list and the presentation pdfs in the **deliverable** directory.

# Power-Plant-Data-Analysis
Project topic:

In this project we will build a model to predict the electrical energy output of a Combined Cycle Power Plant (https://en.wikipedia.org/wiki/Combined_cycle_power_plant), which uses a combination of gas turbines, steam turbines, and heat recovery steam generators to generate power.  We have a set of 9568 hourly average ambient environmental readings from sensors at the power plant which we will use in our model.

The columns in the data consist of hourly average ambient variables:
- Temperature (T) in the range 1.81°C to 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in the range 25.36-81.56 cm Hg
- Net hourly electrical energy output (PE) 420.26-495.76 MW (Target we are trying to predict)

The dataset (https://storage.googleapis.com/aipi_datasets/CCPP_data.csv) may be downloaded as a csv file.  Note that Safari users may have to navigate to File -> Save As and select the option "Save as source" to download the file.  Once you have downloaded the data, please review the Project Modeling Options reading and select a method of working with the data to build your model: 1) using Excel, 2) using Python, or 3) using Google AutoML.

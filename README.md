# EDS220_Fall2022_HW2
### An Analysis of Global Flood Data

Contents:
- HW2_template.ipynb: Template Jupyter notebook for use in Homework 2 and final project
- environment.yml: Template environment file for use in creating Binder environment for running Jupyter notebook

Project Purpose:
The goal of our project is to map the flood events in the Philippines ranging from year 2000 to 2018. The Philippines is a series of thousands of islands in Southeast Asia with multiple climates such as tropical rainforest, tropical monsoon, tropical savanna, humid subtropical and oceanic. The country is exposed to many earthquakes on a daily basis and is surrounded by many active volcanos. Climate change has led to more extreme weather patterns including heavier rainfall and storm surges. A series of tropical storms over the years have led to mass destruction and loss of human life. 

Data Description:
The Global Food Database was created by the Dartmouth Flood Observatory (DFO) and Cloud to Street with the intent of being utilized for global flood risk management and mitigation. This ImageCollection was funded by Google Earth Outreach, and includes 18 years (2000-2018) of satellite-based flood data available on Google Earth Engine. The dataset includes 913 flood events using 12,719 scenes that that were successfully mapped to include the extent and temporal distribution using Terra and Aqua MODIS sensors. Each of the events are represented as an image in the ImageCollection and can be filtered by date, country, and DFO “original ID”.

The bands in the dataset include duration of flood along with a value of 0 or 1 to represent whether or not there was a flood event. Data on cloud coverage is displayed as the number of cloud-free observations in days between the start and end day of each event. In addition, cloud coverage has been assigned a percentage of clear view observations during a given flood event.

The dataset includes many image properties such as:
   - estimated fatalities
   - country code
   - main cause of flood 
   - the centroid longitude 
   - the centroid latitude
   - severity of flood event 

How to Install and Run Data
   - 1. 

Information for final project:
- Presentation dates: **Nov 29; Dec 1**
- Final writeup hand-in date: **Dec 5**
- Deliverables (for in-class presentation):
  - Jupyter notebook - all sections completed, initial sections edited to reflect grade feedback
  - Binder environment compiled to allow others to run code easily
  - Group-led presentation on assigned date

- Deliverables (for final writeup):
  - Jupyter notebook, supporting data files, Binder environment, and README in repo
  - Edits reflecting student and instructor feedback can be made until due date

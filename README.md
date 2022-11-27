# EDS220_Fall2022_HW2
## An Analysis of Global Flood Data

#### Student Authors: Elise Gonzales, Lewis White, Amrit Sandhu

### Contents:
- HW2_template.ipynb: Template Jupyter notebook for use in Homework 2 and final project
- environment.yml: Template environment file for use in creating Binder environment for running Jupyter notebook

### Project Purpose:
The goal of our project is to map the flood events ranging from year 2000 to 2018. More specifically, the goal is to focus on the flood events in Bangladesh and their impacts in the past 20 years. Bangladesh has a tropical monsoon-type climate, with hot and rainy summers and dry winters. It has very low-lying land, and is exposed to increased rainfall and cyclones that are likely going to intensify due to climate change. Bangladesh is densely populated, with 70 million people living in flood-prone areas. Flood events leave hundreds of thousands of people displaced yearly. A series of cyclones and storms over the years have led to mass destruction and loss of human life.

### Data Description:
The Global Food Database was created by the Dartmouth Flood Observatory (DFO) and Cloud to Street with the intent of being utilized for global flood risk management and mitigation. This ImageCollection was funded by Google Earth Outreach, and includes 18 years (2000-2018) of satellite-based flood data available on Google Earth Engine. The dataset includes 913 flood events using 12,719 scenes that that were successfully mapped to include the extent and temporal distribution using Terra and Aqua MODIS sensors. Each of the events are represented as an image in the ImageCollection and can be filtered by date, country, and DFO “original ID”.

The bands in the dataset include duration of flood along with a value of 0 or 1 to represent whether or not there was a flood event. Data on cloud coverage is displayed as the number of cloud-free observations in days between the start and end day of each event. In addition, cloud coverage has been assigned a percentage of clear view observations during a given flood event.

The dataset includes many image properties such as:
   - estimated fatalities
   - country code
   - main cause of flood 
   - the centroid longitude 
   - the centroid latitude
   - severity of flood event 

### How to Install and Run Data
   - To add our data, please use [the GitHub pull request approach] (https://help.github.com/articles/using-pull-requests/). You can either work online or        create a local copy ("clone") of this repository to work in.

### Information for final project:
- Presentation dates: **Nov 29; Dec 1**
- Final writeup hand-in date: **Dec 5**
- Deliverables (for in-class presentation):
  - Jupyter notebook - all sections completed, initial sections edited to reflect grade feedback
  - Binder environment compiled to allow others to run code easily
  - Group-led presentation on assigned date

### Deliverables (for final writeup):
  - Jupyter notebook, supporting data files, Binder environment, and README in repo
  - Edits reflecting student and instructor feedback can be made until due date

![image](https://user-images.githubusercontent.com/110213774/202562515-54d9687f-f10d-4aa2-b6b8-4a5da4c3ffc3.png)


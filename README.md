# My-University-PythonDataScience-Project
Study and visualization of data/statistics of the pandemic situation in the Subcarpathian province

The chosen problem is related to the global Pandemic, which has paralyzed the economy, business and other aspects of human life forcing a change in these very aspects and changing various strategies related to the economy, but also most importantly to safety, hygiene and health in public places, so people should be comfortable and visualized as to how things really are that are felt in numbers and not felt in the realm of daily thoughts therefore the lack of awareness of the seriousness of the situation is also a problem that needs to be solved by showing tangible data.

CHOSEN DATA

A database of statistics on the epidemic situation in Poland, maintained independently by Michał Rogalski, was selected. From this database, the sheet "Epidemic situation in the provinces" and from it the province "PODKARPACKIE" was selected as a set for analysis and visualization. It was necessary to transfer this data to a new excel file in .cvs format and separate the data with commas so that reading it through the "pd.read_cvs()" function would be correct.

There are eight columns in the sheet for each province, which have names that are too long to be conveniently visualized, so we have taken the liberty of abbreviating them and they look as follows:
  - hospi - Number of people hospitalized
  - zmian - shift (d/d)
  - łóż - Number of patient beds
  - %zaj - % occupied
  - respSC - Number of occupied respirators (severe condition)
  - zmian.1 - change (d/d)
  - respL - Number of respirators
  - %zaj.1 - Number of respirators

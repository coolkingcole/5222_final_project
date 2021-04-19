# 5222_final_project
Final for 5222 QGIS choropleth map maker(Project 2 prompt)

# User Manual
### Installation  
Run ```python -m pip install -r requirements.txt``` if you run into module errors.  
This should solve any "ModuleNotFoundError: No module named X" errors  
This plugin is installed via the .zip qgis plugin installation like any other plugin. Steps below-  

## Step1  
Click **plugin menu**  
![image](./assets/step1.PNG)  

## Step2  
Click **Manage and install plugins...**  
![image](./assets/step2.PNG)  

## Step3  
Click **Install from Zip** and browse to downloaded zip
![image](./assets/step3.PNG)  

### Usage  
Clicking the tool icon will prompt you for a folder. When the folder is provided by the user a dropdown menu will be filled with the \*.shp files in that directory. Once a file is chosen the user will have to choose a NUMERIC field in the dropdown. Click OK. The plugin will automatically make a 5 class Choropleth map.

# pasefRiQCalibrator
Welcome to the pasefRiQ calibrator! This simple tool allows you to apply a single one point calibration shift to a low mass region any standard MGF file. We use it to allow more accurate mass windows for the extraction of reporter ion signal. 

![image](https://user-images.githubusercontent.com/39571544/153672803-12f54505-765f-43dd-b14b-0fac98722998.png)

To use this, download the zip file. Unzip it. Double click on the .EXE file. 
There are only 4 buttons in this GUI.
Pick your file.
Give it your manual calibration mass shift.
Tell it where you want it to stop applying the mass shift. I'm only using it up to 136 m/z to incorporate commercial reporter ions.
Hit the Calibrate Button!
Your new MGF file will show up in the folder where the .exe file is.  

![image](https://user-images.githubusercontent.com/39571544/153673006-ab26b0d6-fb0c-44f3-8bbc-415432c95e3f.png)

Following recalibration you can use much tighter mass tolerances on systems that experience mass calibration drift over time. 
For example, the top panel is a commercial tandem mass tag labeled yeast triple knock out standard digest from Thermo Fisher Scientific.
Prior to pasefRiQCalibration, the instrument generating this data can not accurately detect the reporter ion channels with 20ppm mass accuracy. 
![image](https://user-images.githubusercontent.com/39571544/153690837-6c80ccc6-4e00-41cc-a49d-79a7a39dbb6b.png)
Following recalibration this time of flight instrument can integrate the reporter ions. 
For more information please consult the Orsburn, Yuan and Bumpus, February 2022 preprint on biorxiv. 

Happy reporter recalibrating!

# BEMCalibration Tool - Example
<p>1 - Run the BEMCal.exe to unzip the main folder (BEMCal) in your local pc</p>
<p>2 - Open the new folder (BEMCal) and run the BEMCal.exe file within it. Wait some seconds until the UI is loaded.</p>
<p>3 - Press the "Load a config file" button and select a config json file. An example is provided in the "example" folder ("config.json").</p>
<p>4 - Once loaded, click on the "IDFanalyse" button to start the anaysis of your IDF (the path is defined in the config.json file) and read the output in the terminal window.</p>
<p>5 - Check the ranges of variation of the automatically defined parameters in "problem.xls" file, placed in the IDF folder (./example/test/) within the subfolder "Shared_folder", and modify them if needed. </p>
<p>6 - Once saved the problem.xlsx file, run the sensitivity analysis pressing on the "Sensitivity" button. Wait till the end.</p>
<p>7 - Once the sensitivity is finished, put the the calibration data in the calibration_data.xlsx file placed "Shared_folder" (left blank the output that must not be calibrated). A calibration_data.xlsx file is placed as example in the ./example/test folder.</p>
<p>8 - Run the calibration by pressing the "Calibration" button and read the messages in the terminal. It is possible to stop the analysis by pressing Y when asked (for example, when one index in the terminal is lower then 15 acording to ASHRAE limits).</p>
<p>9 - Once the calibration is finished, the optimized IDF will be printed in the "finalpop_IDFs" folder within the IDF folder. The calibration indexes are plotted in the final_pop.xlsx</p>

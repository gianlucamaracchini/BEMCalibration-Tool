# BEMCalibration Tool - Example
<p>1 - Run the BEMCal.exe to unzip the main folder (BEMCal) in your local pc</p>
<p>2 - Open the new folder (BEMCal) and run the BEMCal.exe file within it. Wait some seconds until the UI is loaded.</p>
<p>3 - Press the "Load a config file" button and select a config json file. An example is provided in the "./BEMCal/example/" folder ("config.json").</p>
<p>4 - Once loaded, click on the "IDFanalyse" button to start the analysis of your IDF (the path is defined in the config.json file) and read the output in the terminal window.</p>
<p>5 - Check the ranges of variation of the automatically identified parameters in the "problem.xls" file within the subfolder "Shared_folder" in the IDF folder (./example/test/Shared_folder for the example), and modify them if needed. </p>
<p>6 - Once the problem.xlsx file is saved, run the sensitivity analysis by pressing on the "Sensitivity" button. Wait till the end.</p>
<p>7 - Once the sensitivity is finished, put the calibration data in the calibration_data.xlsx file placed in the "Shared_folder" (left blank the output that must not be calibrated). The calibration_data.xlsx file of the example is placed in the ./example/test folder and can be used for testing the calibration. </p>
<p>8 - Run the calibration by pressing the "Calibration" button and read the messages in the terminal. It is possible to stop the analysis by pressing Y when asked (for example, when one index in the terminal is lower than 15 according to ASHRAE limits).</p>
<p>9 - Once the calibration is finished, the optimized IDF will be printed in the "finalpop_IDFs" folder within the IDF folder. The calibration indexes are plotted in the final_pop.xlsx</p>

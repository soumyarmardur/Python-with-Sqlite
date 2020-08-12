# Python-with-Sqlite

python script which implements the below function. sqlite is attached for accessing the databse

* <b>cell_with_highest_temperature()</b><br>
Function returning the device_id of the cell with the highest temperature.

* <b>module_with_highest_temperature()</b><br>
Function returning the device_id of the module which has the cell with the highest temperature 

* <b>averate_voltage_in module(device_id)</b><br>
Function returning the average voltage of all the cells in all the modules in the stack represented by the device_id, Cells with Voltage below 0.1V are dead cells and should be excluded from this analysis.

# Critical Path Method for Project Management written in C

This is the software I created using C in linux Fedora 33. YOu may download it and use it for your own personal use. 
This software has no warranty . Please watch my video on youtube for the demo. It will run natively on linux.

To run the code in the linux command line:     
./cpmv01 data.csv

or to just compute cpm on a range of task (e.g. taskA to task d )     
./cpmv01 data.csv 4

If you are going to create your own csv file, please follow the format indicated in the data.csv to
avoid any errors. 

Writing you own csv:   
1. DESC = Task description . up to 15 characters 
2. CODE = 1 letter or 1 character as tag which identifies that specific task
3. PREDECESSORS = These are task tags (CODES) which signifies the tasks preceding this task.
4. DAYS = the amount of time in DAYS that the task is expected to be completed. 

Notes:
1. Please use comma ',' to separate columns 
2. Please strictly follow the format of the data.csv file in creating your own input file.



<Critical Path Method by Pinoystat >
    Copyright (C) <year>  <name of author>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

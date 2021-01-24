# satellite-tracker
Using Python to create a Satellite Tracking Interface.

# Server Setup
- Using mysql to create the database - copy this and create a database to store satellite information:
CREATE table mydatabase.tles (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255), line1 VARCHAR(255), line2 VARCHAR(255));
- These packages must be installed:
  - mysql.connector
  - requests
- Run server_download.py
- Start the server by running ascioServer.py

# Client Setup
- Would highly recommend setting up a conda environment - these packages must be installed:
  - traits
  - traitsui
  - tvtk
  - mayavi
  - skyfield
  - pyface
  - ctypes
  - envisage
  - pyqt
- in main.py change serverIP and portNo variables (lines 15 & 16) to that of your server's.
- run main.py (and cross your fingers)

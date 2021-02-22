# gdoor_charting
A command line program, named gnup, to read the database and produce temperature and humidity a chart for the webpage. 
This program is used with the gdoor program's sqlite3 database to make a chart. It is called by the php code in gdoor/index.php. 
The program  reads the timestamp, temperature, and humidity data from garage.db to write a readings.txt datafile. It then uses popen() 
to launch gnuplot and send it commands to produce a chart from readings.txt.  


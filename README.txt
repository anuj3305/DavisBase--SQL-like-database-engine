The project was developed on a Windows machine using Java version 1.8.

Follow the instructions below to run the code:
1. Extract the compressed folder.
3. Navigate to the path where the folder has been extracted.
4. Navigate to the src\database folder and compile all the files using the below command.
   [your folder]\DavisBase\src\database>javac *.java
5. Navigate to the parent directory (\src folder).
6. Run the DavisBase file:
   [your folder]\DavisBase\src>java database.DavisBase


EXAMPLES:
	1. CREATE DATABASE test;
	2. USE test;
	3. CREATE TABLE cars (id INT, name TEXT);
	4. INSERT INTO cars VALUES (1, honda);
	5. DROP TABLE cars;
	6. DROP DATABASE test;

















 

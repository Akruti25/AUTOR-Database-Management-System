# AUTOR - Database Management System

## Instructions on how to compile and execute the code:

The procedures for setting up the environment needed to compile and run the code are listed below.
### A.	REMOTE CONNECTION
  1.	Putty is required to establish a connection to the remote EOS server. 
  2.	When the file has been downloaded, run it.
  3.	Under "Host Name," include "remote.eos.ncsu.edu". 
  4.	Click ‘Open’. Upon giving your unity ID and password, you will be connected to the remote EOS server.

### B.	EXECUTION
  1.	In the command prompt of your system, run the following query:
           pscp -P 22 DBMSProject1Main.java sbhatia6@remote.eos.ncsu.edu:/afs/unity.ncsu.edu/users/s/sbhatia6/
  2.	Add Oracle to your environment in the remote server using - 
           add oracle12
  3.	Set the CLASSPATH variable to include the JDBC drivers in the remote server.
           export CLASSPATH=.:/afs/eos.ncsu.edu/software/oracle12/oracle/product/12.2/client/jdbc/lib/ojdbc8.jar
  4.	Run the following command: 
           javac DBMSProject1Main.java 
  5.	Executing the file: 
           java DBMSProject1Main.java 

### Member Names 
  1. Manan Patel 
  2. Akruti Sinha 
  3. Soha Bhatia
  4. [Ravi Ghevariya](https://github.com/ravighevariya10)

_Note: Please be advised that this project constitutes a component of an academic endeavor for CSC 540: Database Management System, completed during the Fall semester of 2022._

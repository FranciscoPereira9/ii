****README A4_RS1_A****

* Executable OS: Windows
* Data Base: MariadB, with phpMyAdmin hosted by FEUP. Log in data included in the executable file.

* Intructions: To run the executable A4_RS1_A_mes.jar, 1st run the file "run_java.bat", then the simulator codesys with the following parameters:
	- 1st argument should be the name of the OPC-UA server, i.e. "DESKTOP-G3Q32TE"
	- 2nd argument if infomration from last session should be discarded, "n" to keep or "y" to discard.
	 If "y", the program will ignore all the information in the database and the initial state of the sfs.
	 If "n", it will fetch the database, as well as,  everything that happened in the sfs and was not read by the MES.
	 - the bat file indicated to write in two separate text files, the std and stderr, respectively in "out.txt" and "error_out.txt".
	 

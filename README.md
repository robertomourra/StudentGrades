# StudentGrades
Platform used to Develop Code: Microsoft Windows 10

Any Special Steps to Compile Code: 

	a-(mysql-connector.jar present in "res" folder should be added to Java Class Path of the project.
	b- MySql Database should be installed
	c- JDBC drivers should be installed for MySQL
	d- Import database.sql in MYSQL for database schemas.
	
  	Any bugs program has:
	a- No input validation is done. For example if a string is entered instead of integer, program might not perform desired output.
 	 Summary of approaching problem
	a- Created database tables for relevant classes (course, grade, semester, student and transaction)
	b- The created respective methods to save relevant information into database for example saveCoureToDb, saveGradeToDb or saveStudentToDb.
	c- Wherever objects were added to ArrayList, respective function was called to save into db as well.
	d- Created method to load all information from database.
	c- Wrote checks on code to avoid duplicate records.

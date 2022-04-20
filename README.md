# Vendor Dataset Documentation

Goal: Identify friction points students describe in the following text dataset

Context:
	* Undergradutes in College of IT
	* Term start dates were between 2016-08-31 and 2021-08-31
		* "Term" = 6 month unit of time used at WGU.
		* Notes were created between 2019-06-03 and 2021-07-31

* Student Level Data
	* "STUDENT_PIDM" = Student's ID, used for joining across tables
	* "Term Description" = Month and Date of Term that student's term began. Terms begin on the first of every month.
	* "Term Code" = Numeric code for term start date
	* "Program Code" = Student's Major within College of IT
	* "Drops" = Whether the student withdrew from WGU that term.

* Note Level Data
	* "CREATEDDATE" = When the Mentor's note to the student was generated in our Salesforce system
	* "SHORTTEXT__C" = Text the Mentor wrote in the systen
	* "PIDM__C" = Student ID, used to join with Student Level data
	* Name and Type can be ignored.


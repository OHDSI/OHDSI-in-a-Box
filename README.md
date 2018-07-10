# OHDSI-in-a-Box
AWS AMI containing SynPUF data in OMOP CDM, a RDBS including query client, WebAPI, ATLAS.

To launch the AWS OHDSI In-a-box instance search for IQVIA or OHDSI in the community AMI search box in AWS.  

The search will return 2 instances to choose from for your EC2 instance. 


1) iqvia-ohdsi-postgresql-100k-v1.00

2) iqvia-ohdsi-sqlserver-100k-2.3m-v1.00


iqvia-ohdsi-postgresql-100k-v1.00 - Details
  
	Atlas 2.3.1
  		http://localhost:8080/atlas
  	WebAPI 2.3.0
   		http://localhost:8080/WebAPI
   		http://localhost:8080/WebAPI/vocabulary/search/cardiomyopathy
  	Tomcat Login 9.0.4:
  		URL: http://localhost:8080
  		User: admin
  		Password: ohdsi
  	PostGre Admin Login (via pgAdmin)
  		Username: postgres
  		Password: ohdsi
  	pgAdmin 4
  	PostgreSQL
  	100k Sample Database
  	Rabbit In A Hat (jar file, shortcut on desktop)
  	WhiteRabbit (jar file, shortcut on desktop)

iqvia-ohdsi-sqlserver-100k-2.3m-v1.00 - Details

	Atlas 2.3.1
		http://localhost:8080/atlas
	WebAPI 2.3.0
		http://localhost:8080/WebAPI
		http://localhost:8080/WebAPI/vocabulary/search/cardiomyopathy
	Tomcat Login 9.0.4:
		URL: http://localhost:8080
		User: admin
		Password: ohdsi
	SQL Server sa Login (via Management Studio)
		Username: sa
		Password: ohdsi
	100k Sample Database
	2.3m Sample Database
	Rabbit In A Hat (jar file, shortcut on desktop)
	WhiteRabbit (jar file, shortcut on desktop)
	Server Login 

Server Credentials
	User: iqvia-ohdsi
	Password:  I!QViAOH@DSI18
	(Note: It is highly recommended to change the password once logged in)

# uploadfile
### Description:
Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications. All configuration is done by annotations. You don’t need a single XML configuration file. Here we use in memoru H2 db.
### System Requirement :
JAVA 1.8 Spring Boot 1.5.1 H2 db Hybernate Spring Security
### Below available REST API:

http://localhost:8080/rest/filemetas?keyword=005  
("GET" Search "keyword, page, pageSize" keyword may id/name/fullname/skypeid etc.)

http://localhost:8080/rest/filemetas 
("POST" @RequestBody @Valid FileMeta filemeta)

http://localhost:8080/rest/filemetas/005 
("PUT" update filemeta, as per Id)

http://localhost:8080/rest/filemetas 
("DELETE" filemetas, @RequestParam String[] ids)

http://localhost:8080/rest/photos/007 
("GET" Content as per Id)

http://localhost:8080/rest/photos/007 
("POST" Upload Content as per Id)

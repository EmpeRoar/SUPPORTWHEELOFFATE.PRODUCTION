# SUPPORTWHEELOFFATE.PRODUCTION
SUPPORTWHEELOFFATE.PRODUCTION


1. In IIS Create 3 Sites
   8081 - points to fileserver
   8082 - points to webui
   8083 - points to webapi
   
2. create a database named SUPPORTWHEELOFFATE_
3. restore the database from file supportwheeloffate_db.bak
4. make sure to application pool in iis in registered in the sql server's security logins.
5. goto localhost:8082 to view the app.

# CLIENT-SERVER ARCHITECHTURE

## This project is aimed at implemeting a client-server architecture using MySQL database management system.

I spinned 2 instanced (Linux-based virtual server)
    - mysql server
    - mysql client

I installed mysql server software on the mysql server Linux Server

 ![InstalledMySQL_Server](./Images5/Installed_mysql_server.PNG)

...and installed mysql client software on the mysql client Linux Server

 ![InstalledMySQL_Client](./Images5/Installed_mysql_client.PNG)


Opened a port 3306 for MySQL Server
 
 ![OpenedPort3306](./Images5/Open_Port3306.PNG)


Created a database named remote_user

 ![CreatedDB](./Images5/Server-created_database.PNG)


I then configured MYSQL Server to allow remote host connection and replaced ‘127.0.0.1’ to ‘0.0.0.0’
 
 ![Allow_RH_Connection](./Images5/Server-permit_remotehost_connection.PNG)


I connected remotely to mysql server from mysql client. Then used 'Show databases;' to check connection.

 ![ConnectRemotely](./Images5/Client-Server_Connected.PNG)





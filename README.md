# textfiles


ssh sonusaini@20.7.176.246

Sksaini@0798

0ddfbdb08b2a47508463e4347dccc6a3


sudo apt-get update

java :
java -version
sudo apt-get install openjdk-11-jre-headless
----java path : /usr/lib/jvm/java-1.11.0-openjdk-amd64/

-----------------------------------------------------------------
jenkins-war :
wget http://updates.jenkins-ci.org/download/war/2.358/jenkins.war
sudo service jenkins status
java -jar jenkins.war --httpPort=8089

------------------------------------------------------------------
Git :
sudo apt-get update
sudo apt-get install git

------------------------------------------------------------------
maven :
sudo apt install maven
wget https://dlcdn.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz -p /tmp
----maven path :Teja@Jenkins:/$ mvn -version
Apache Maven 3.6.3
Maven home: /usr/share/maven

------------------------------------------------------------------
mysql :
sudo apt install mysql-server
sudo service mysql status
sudo ss -tap | grep mysql
mysql --version
 sudo systemctl start mysql.service
----enter to mysql: sudo mysql -u root
----set username and password:  ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root';
----create database:  create database UniversityData;
----use db: use UniversityData;
----quit

------------------------------------------------------------
Docker :
sudo apt-get update
sudo apt-get install docker.io

giving permision to read write and everything:
sudo chmod 777 /var/run/docker.sock

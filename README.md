## 🌤️날씨별 옷차림 & 관광지 추천 시스템👗

<br/>

###  ✔ 시작가이드
#### ☂️ For building and running the application you need :
- mysql 8.0.34
- mongodb 4.4.22
- node.js 16.20.2
- npm 9.5.1
- Linux Ubuntu 20.04

#### ☂️ Installation
```
# git clone https://github.com/westmini427/Weatherdata-project.git
# cd source_codes
```
#### ☂️ Server
```
# apt install -y npm
# npm install -g nodemon
# npm init -y
# npm install express morgan path body-parser cookie-parser axios mongoose sync-mysql dotenv async
# nodemon app.js
```

#### ☂️ Database (mongodb, mysql)
```
# wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
# echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | tee /etc/apt/sources.list.d/mongodb-org-4.4.list
# wget http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2_amd64.deb
# dpkg -i libssl1.1_1.1.1f-1ubuntu2_amd64.deb
# rm -rf libssl1.1_1.1.1f-1ubuntu2_amd64.deb
# apt -y update; apt -y upgrade
# apt -y install mongodb-org
# systemctl start mongod
# systemctl status mongod

# mongod --version
db version v4.4.22

# mongo

# vi /etc/mongod.conf

 24   bindIp: 0.0.0.0

# systemctl restart mongod
```
```
# apt -y update; apt -y upgrade
# apt -y install mysql-server
# systemctl restart mysql
# systemctl status mysql
# systemctl enable mysql
# netstat -ntlp
# vi /etc/mysql/mysql.conf.d/mysqld.cnf

 31 bind-address            = 0.0.0.0
 32 mysqlx-bind-address     = 0.0.0.0

# systemctl restart mysql
```
<br/>

### ✔ 기술스택

|Category|Language|
|:--:|:--|
|Server|![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)|
|Frontend|![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) |
|Backend|![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)|
|Database|![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)|

<br/>

### ✔ 프로젝트 개요

- 팀명 : 메이웨더
- 인원 : 2인 [ 서민희, 정지원 ]
- 기간 : 10일 [ 2023.04.24.(월) ~ 2023.04.27.(목) ]
- 문서 : Wireframe, Table configuration, API report, Architecture

<br/>

### ✔ 프로젝트 목적
- 
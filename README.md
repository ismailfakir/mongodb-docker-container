# mongodb-docker-container
How to run:
1. create directory 'mongodb_data' in the current folder.
2. create the following the following files with secret password for mongodb 'root' user & mongo express 'admin' user:
- db_root_password.txt
- me_admin_password.txt
3. run 'docker-compose up -d'

mongodb: 
    address: localhost:37017 or {public-ip}:37017
    user: root
    password: contant of 'db_root_password.txt'

mongo express: 
    address: http://localhost:9081/ or http://{public-ip}:9081/
    user: admin
    password: contant of 'me_admin_password.txt' 
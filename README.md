# wos_builder
Create and populate a MySQL Database from Web of Science raw xml data

## Requirements

mysql.connector

I downloaded this binary from the MySQL pages and installed as sudo :

wget http://dev.mysql.com/get/Downloads/Connector-Python/mysql-connector-python_2.1.4-1ubuntu16.04_all.deb
dpkg -i mysql-connector-python-cext-py3_2.1.4-1debian8.2_amd64.deb


cElementTree

# GT-MSI Project Instruction
1. Move 2022_CORE.zip to the same folder as the code repo, which means there is a parent folder contains wos_buider and 2022_CORE.zip
2. ./runner.sh
3. Waiting for the code to generate tables with prefix 2022_ based on the data.
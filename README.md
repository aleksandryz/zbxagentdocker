# Zabbix agent in dockers

## Setup

### 1 Initial configuration
In the file .env_agent you can configure ZBX_SERVER_HOST you needed and other options.
Example:
```
ZBX_SERVER_HOST=zabbix-server
```
### 2 Download
```
git clone https://github.com/aleksandryz/zbxagentdocker.git
cd zbxagentdocker
```
### 3 Run docker
```
docker-compose up -d
```

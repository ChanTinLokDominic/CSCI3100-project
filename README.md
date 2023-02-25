# Group members
Group ID: C1 

|Name|SID|
|:-:|:-:|
|Tse Ka Hei|1155159810| 
|Cheng Ming Chun Jason|1155126862| 
|Ng Hiu Tsun|1155144015| 
|Chan Ching Yan|115512569| 
|Chan Tin Lok|1155126874|


# Pre-requisite
`docker`: version 23.0.0

`docker-compose`: version 1.29.2

Install docker engine on https://docs.docker.com/engine/install/


# Usage
```bash
# Start the database server and the api server
docker-compose up -d

# Stop the database server and the api server
docker-compose down

# Stop the servers and clean up the database
docker-compose down -v
```

Check the api services on http://localhost:8000/docs

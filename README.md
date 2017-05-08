# docker-wp-skeleton
> Simple skeleton for wordpress with docker

## Getting started
1 - Copy the files from this repository to the project folder  
2 - Download the wordpress version you want and unzip to the folder `wp`  
3 - Run the following command to raise the database  
```
docker-compose up -d db
```

4 - Start wordpress with the following command 
```
docker compose up -d wp
```


### Additional information
- Permissions (Permission required to upload images and plugins inside wordpress admin)  
```
chmod -R 777 wp
```

## Access the project
To access the project go to the following address:
```
http://localhost/
```

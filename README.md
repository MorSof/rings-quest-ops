
## Rings Quest Ops

### Run all services with docker compose

#### Prerequisites
Before you begin, make sure that you have the following requirements installed on your system:
- [Node.js](https://nodejs.org/) (version 12 or higher)
- [npm](https://www.npmjs.com/) (version v18.12.1)
- [Docker](https://docs.docker.com/get-docker/)


Make sure you have pulled the latest git update by writing in the terminal
```shell
 $ git pull 
```
#### run the following commands in the terminal
```shell
$ docker-compose pull
$ docker-compose up
````
On the first time running this, the app container should be failed so you should:
1. Go to the DB section below and follow the orders there
2. ```shell
   $ docker-compose down
   $ docker-compose up
   ````

Now all the containers should work!

## DB creation locally
After your docker-compose is up, you'll need to create a DB: 
1. Navigate to [pdAdmin](http://localhost:5050/browser/) (If the links doesn't work, try to add 'http://' to the address)
2. Press on the "Add New Server" Button, a popup window will appear.
3. On the general tab name your server "rings_quest"
4. On the connection tab:
   - **Host name/address**: db 
   - **Port**: 5432
   - **Username**: user
   - **Password**: admin

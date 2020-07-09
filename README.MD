
# Installation

Before starting make sure you have git, docker and docker-compose installed on your local machine.

### Clone the project 

```bash
git clone https://github.com/comorlab/comorapp.git
cd comorapp
```

### Build the project

```bash
# This process can take several minutes. Be patient ! 
docker-compose build
docker-compose up -d
```

### Check if everything is Up and running
 
```bash
docker-compose ps
```

### Install the required dependencies

If everything is Up then run the commands below

```bash
docker-compose exec php composer install
```

Now go to http://localhost. Enjoy !

### Start the symfony server

These steps are optional

```bash
docker-compose exec php symfony server:start
```
Now go to http://localhost:8000. Enjoy !

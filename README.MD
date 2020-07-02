
# Installation

Before starting make sure you have docker and docker-compse installed on your local machine.

```bash
# This process can take several minutes. Be patient ! 
docker-compose build
docker-compose up -d
```

Check if everything is Up and running 
```bash
docker-compose ps
```

If everything is Up then run the commands below

```bash
docker-compose exec php composer install
docker-compose exec php symfony server:start # optional
```

Now go to http://localhost. Enjoy !

Now go to http://localhost:8000. Enjoy ! # optional

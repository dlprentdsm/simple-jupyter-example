# simple-jupyter-example
- Start with ```docker-compose up -d``` (use ```--build``` on first run). 
- View logs to get token: ```docker-compose logs -f```
- Runs at 0.0.0.0:8989 unless you change it
- Mounts ```data``` dir so you can easily save your work or add data.

Use a different base image as desired.

Use alternate docker-compose file if desired, with added services, like redis or postgres for you to interact with in your notbook, eg:
-  ```docker-compose -f docker-compose-redis.yml up -d && docker-compose -f docker-compose-redis.yml logs -f```

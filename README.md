# Docker configuration for Wuhu

## Requirements

- Docker
- Docker Compose

## Install

- Run `./init.sh` to create directories and set file permissions (or you can do this manually if you want more restrictive file permissions)
- *(Optional)* Change database credentials in `docker-compose.yml`
- Run `docker-compose up`
- Open the admin interface and follow [Wuhu deployment guide](./readme.txt)(Remember to set your database credentials if you modified `docker-compose.yml`)

By default the admin interface is available at [http://localhost:8081](http://localhost:8081) and the party system is available at  [http://localhost:8080](http://localhost:8080). You can change the ports from `docker-compose.yml` if you want the party system to use e.g. port 80 instead of 8080.


## Additional resources

- [Wuhu github](https://github.com/Gargaj/wuhu)
- [Wuhu website](http://wuhu.function.hu/)
- [Wuhu readme.txt](./readme.txt)

## Credits

Wuhu was created and is maintained by Gargaj / Conspiracy.

Wuhu Docker configuration by Teel / Accession ^ Faktory ^ Matt Current.
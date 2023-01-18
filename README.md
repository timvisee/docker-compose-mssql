# Microsoft SQL server in Docker
Some helpful scripts and configurations to easily get a Microsoft SQL server
instance running in a docker container on Linux.

This project uses Microsoft's docker image for SQL server and uses
docker-compose to easily manage container configurations.

## Requirements
* Linux operating system
* Docker
* Docker composer

## Usage
* Clone repository 
```bash
git clone https://github.com/tanhongit/docker-compose-mssql-server.git
cd docker-compose-mssql-server
```

* Configure password in `.env` file.
* Start the container:
```bash
./start
```
To stop the container, use the `./stop` script.
```bash
./stop
```

Log in on the database with your credentials:
* User: `sa`
* Password: `root` (default)

## License
This project is released under the GNU GPL-3.0 license. Check out the [LICENSE](LICENSE) file for more information.

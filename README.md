# Microsoft SQL server in Docker
Some helpful scripts and configurations to easily get a Microsoft SQL server
instance running in a docker container on Linux.

This project uses Microsoft's docker image for SQL server and uses
docker-compose to easily manage container configurations.

## Requirements
* Linux operating system
* Docker
* Docker compose

## Usage
* Clone repository 
```bash
git clone https://github.com/tanhongit/docker-compose-mssql-server.git
cd docker-compose-mssql-server
```
* Copy `.env.example` to `.env` and edit the file to your needs.
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
* Password: `Password123(!)Strong` (default)

> [!NOTE]
> The password can be changed in the `.env` file.

```dotenv
# .env file

SA_PASSWORD=Password123(!)Strong
```

## License
This project is released under the GNU GPL-3.0 license. Check out the [LICENSE](LICENSE) file for more information.

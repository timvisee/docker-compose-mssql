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

### Clone repository

Clone the repository to your local machine:

```bash
git clone https://github.com/timvisee/docker-compose-mssql.git
cd docker-compose-mssql
```

### Start the container
* Copy `.env.example` to `.env` and edit the file to your needs.

```bash
cp .env.example .env
```

* Configure password in `.env` file.

```dotenv
# .env file

SA_PASSWORD=Password123(!)Strong
```

* Start the container:

```bash
./start
```

> [!NOTE]
> To stop the container, use the `./stop` script.
> ```bash
> ./stop
> ```

### Log in on the database with your credentials
* User: `sa`
* Password: `Password123(!)Strong` (use the password you set in the `.env` file)

## License
This project is released under the GNU GPL-3.0 license. Check out the [LICENSE](LICENSE) file for more information.

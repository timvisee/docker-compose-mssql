mssql:
    image: 'mcr.microsoft.com/mssql/server'
    ports:
        - '1433:1433'
    environment:
        - ACCEPT_EULA=Y
        - SA_PASSWORD=Secret1234
    volumes:
        - './drive:/var/opt/mssql'

# Use the official SQL Server 2019 Linux image from Microsoft
FROM mcr.microsoft.com/mssql/server:2019-latest

# Specify environment variables for SQL Server
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=Partiunuvem@2023

# Expose the necessary ports
EXPOSE 1433

# Start SQL Server on container startup
CMD [ "/opt/mssql/bin/sqlservr" ]

# Docker Run
# docker run --name db-semanapartiunuvem -dp 1433:1433 caiobueno4it/db-semanapartiunuvem
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="images/qrfy.jpg" style="display: block;  margin-left: auto;  margin-right: auto;  width: 20%;">
  <h3 align="center">README.MD</h3>

  <p align="center">
    This file contains the instructions for the local deployment of the Docker container of the MS SQL Server database manager in its latest version.
    <br />
  </p>
</div>




# FP-BTSD_Docker
Final Proyect, Bachelor's Degree in Techniques for Software Development, Docker Tools (MS SQL Server...)

# mssql-docker-compose

## Introducción
 
 El objetivo de este proyecto es poder suministrar al equipo de desarrollo de Sealsign de infraestructura local en su pc para aprovisionar una base de datos tipo SQL Server dockerizada. El principal beneficio es poder desarrollar el producto Sealsign en local sin tener necesidad de conectarse a la base de datos compartida y por VPN.

## Requirements

 - https://www.docker.com/

## Install

### Init

Start
```
$ docker compose up -d
```

Stop
```
$ docker compose stop
```

## Documentación

*[Configure SQL Server on Linux](https://learn.microsoft.com/en-us/sql/linux/sql-server-linux-configure-environment-variables)
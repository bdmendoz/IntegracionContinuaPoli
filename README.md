# IntegracionContinuaPoli
trabajo de integración continua Poli

# Integrantes

1. Bayron Daniel Mendoza Tovar
2. Jonathan Andres Cruz Tellez
3. Juan Pablo Salazar Portilla
4. Mendez Quintero Maricela
5. Jose David Yate Capera

# Pasos para realizar la instalación

Se debe crear el dominio en el pc local, en el caso de linux se hace en

`sudo nano /etc/hosts`

`cd docker`

`cp .env.example .env`

Se llenan los datos correspondientes en el nuevo archivo .env

`docker-compose up -d --build`
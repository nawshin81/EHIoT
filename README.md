### Data Simulation on Wokwi ###

The links for the data simulation are:
[Patient 01](https://wokwi.com/projects/385760899767485441),
[Patient 02](https://wokwi.com/projects/387557103064099841),
[Patient 03](https://wokwi.com/projects/387557203386612737).

Keep the tab open on a shared screen, as switching to another screen turns off the simulation.

### InfluxDB credentials: ###

**Username:** admin

**Password:** password

### Grafana credentials: ###

**Username:** admin

**Password:** password

### Project set up ###
The steps to set up the project:
Clone the project from the GitHub link: https://github.com/nawshin81/EHIoT
Run Docker Desktop
Go to the terminal and run the commands “docker-compose build” and “docker-compose up”
Go to the Wokwi simulation link to run the data simulation. Please keep in mind, switching over to another tab/ screen pauses the simulation. So, keep the simulation tab open on a divided screen/ monitor.
Visit http://localhost:1880 to see the Node-RED flow.
Visit http://localhost:8086 to access InfluxDB.
In the InfluxDB login interface input the username and password for authentication.
Username: admin
Password: password
Visit http://localhost:3000 to access Grafana.
In the Grafana login interface input the username and password for authentication.
Username: admin
Password: password
Navigate to the dashboard and open the “Patient Monitoring Dashboard”


# Docker

## Development Environment

In this repo you will find a Docker Compose to run Wordpress

## Prerequisites

You need to have:
* Docker-compose installed
* Root privileges


## Instructions

1. Download the `wordpress` folder so you can get access to the **docker-compose** file and deploy on Docker a **Wordpress** instance with **MySQL**
   
2. Once it'ss downloaded, access to the `wordpress` folder and run the following command:
   ```
   docker-compose up
   ```
> add `-d` parameter at the end of the line to run it detached (on the background)

3. Open a browser and access to the URL:
   ```
   http://localhost:8080/

   or

   http://127.0.0.1:8080/
   ```
> *port has been edit to 8000*

4. Finally, start configuring WordPress
   ![img](wordpress/wp_example.jpg)

- Install Git

- Install Docker

- Download source code from github

		git clone ...
	
- Start server

	Go to directory you cloned.
	
		cd /project-path
	
	Start docker compose.	
	
		docker compose --env-file .env up
	
	if need to start docker compose in background mode, you can use below command.
	
		docker compose --env-file .env up -d
		
	if need to start docker compose with docker hub images, you can use below command
	
		docker compose --env-file .env -f docker-compose-hub.yml up -d --force-recreate


	After few minutes, you can visit "http://localhost:3000".
	
	

# Logging

Logging works by mounting the following directories from the docker container:
	
	- /srv/shiny-server/logs
	
	- /var/log/shiny-server/

This writes time stammped logs to the directory with read-only permissions.
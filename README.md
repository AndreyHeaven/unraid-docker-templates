# unraid-docker-templates
My own docker repository for unRAID


## Simple OPDS
# Create superuser
~~~~
docker exec -ti sopds bash
python3 manage.py createsuperuser
~~~~

# Scan library

~~~~
docker exec -ti sopds bash
python3 manage.py sopds_util setconf SOPDS_SCAN_START_DIRECTLY True
~~~~

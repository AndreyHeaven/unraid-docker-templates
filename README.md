# unraid-docker-templates
My own docker repository for unRAID


# Simple OPDS

after install "open console" and 

## Create superuser
~~~~
python3 manage.py createsuperuser
~~~~

## Scan library

~~~~
python3 manage.py sopds_util setconf SOPDS_SCAN_START_DIRECTLY True
~~~~

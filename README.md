# dockerfiles

Update image
- pull latest version of image e.g. with 'docker pull nginx'
- stop container   'docker stop nginx'
- remove container 'docker rm nginx'
- restart container 'docker-compose -f serverAtHome.yaml up -d unifi'

After update of unifi / unifi-db, an db check (and in most cases) a db
repair is necessary. Check the log of the unifi-db container..

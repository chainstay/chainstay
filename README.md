# Web resources for Chainstay Software

## Regenerating static assets
When making updates to the UI, static assets must be regenerated

### Requirements
* docker-compose

### How to run
```
docker-compose run static
# wait until completion
docker-compose rm -fs
# commit changes and push
```

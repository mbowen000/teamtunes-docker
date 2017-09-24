# teamtunes-docker
Docker Compose Wrapper for Teamtunes Deployment

## Setup

- Install Docker
- Clone this repo
- Create a env file replacing values as needed (these probably changed) - make sure the name maches the one specified in `docker-compose.yml`
```sh
client_id=5cc6f*** (spotify client id)
client_secret=aec644*** (spotify secret)
MONGOLAB_URI=mongodb://heroku_wtv92whl:4sameshbtcmik5lkici85dgee9@ds043615.mongolab.com:43615/heroku_wtv92whl
redirect_uri=http://localhost:3000/callback
slackuri=[optional unused now]
collection=tracks-2
```
- run `docker-compose up`

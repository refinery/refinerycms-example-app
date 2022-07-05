# Refinery Example App

## Deploy to Heroku

  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/refinery/refinery-example-app)

## Installation on localhost

If you start the project on localhost, the `error Couldn't find an integrity file` will be raised. Fix it by `yarn install --check-files`

If the another error `app_name@0.1.0: The engine "node" is incompatible with this module. Expected version "12.13.0". Got "XX.YY.ZZ"` is raised, it is because you dont have exact version
of node - v12.13.0 installed. Ignore this error by running command `yarn install --ignore-engines` 

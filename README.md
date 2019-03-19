# exploreAT-collectionexplorer-api

Simple node application to expose an API to access mysql, auropeana and flyckr services through a
single API.

## Use
1. Install the dependencies
Using preferably (yarn)[https://yarnpkg.com/en/] as the dependency manager just install
the dependencies with ```yarn install```, or ```npm install``` in case you prefer to use
(npm)[https://www.npmjs.com/].

2. Install (forever)[https://github.com/foreverjs/forever] to ensure the persistency of the script. __Be sure to install this 
requirement globally__. ```[sudo] npm install forever -g```

3. Launch the application in the background with ```forever start app.js``` and you will
have a detached node instance to answer requests to the API.

## Configuration
In order to expose these services, the respective credentials have to be provided. An example of the json
that has to be provided is provided in _config/example.json_.

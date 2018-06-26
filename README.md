# comt-landing
The homepage for https://comt.ioos.us

## Building the project

1. Download and install nodejs (which comes with npm)
2. Install the project nodeJS dependencies
   ```
   npm install
   ```

3. Install the project bower dependencies. If you have bower installed as a command line tool, which is highly recommended.
   ```
   bower install
   ```

   Otherwise, you can run bower through the local packages

   ```
   node_modules/bower/bin/bower install
   ```

3. To run the project
   ```
   DEBUG=comt-landing:* npm start
   ```

## Running in Production

1. Compile all of the static assets
   ```
   grunt
   ```

2. Launch the web application
   ```
   NODE_ENV=production ./bin/www
   ```

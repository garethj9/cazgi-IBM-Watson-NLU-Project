# coding-project-template

# Part B: Install Server-side packages

cd /home/project/cazgi-IBM-Watson-NLU-Project/sentimentAnalyzeServer

All packages are needed to be installed are listed in package.json. Run npm install -s, to install and save those packages.

npm install  -s

Run the server using the following command.

npm start

If all the required packages are successfully installed, the server should start without any issues.

Press Ctrl+C to stop the server.

# Part C: Install IBM Watson package and set up the .env file
# Add the Watson SDK

Install the ibm-watson package in your server side using the following command.

npm install  -s ibm-watson@6.1.1

## Add the .env file which isn't included in this Repo to add the Watson credentials

Right click on the sentimentAnalyzeServer in the explorer and a new file named .env.
The contents of the .env file would be as below

API_KEY=<your api key>
API_URL=<your url>

# Part E - React Client Side

Change to client directory sentimentAnalyzeClient.

cd /home/project/cazgi-IBM-Watson-NLU-Project/sentimentAnalyzeClient
All packages are needed to be installed are listed in package.json. To install and save those packages, run the following command in the terminal.

npm install -s

# Run the following to build the client side and copy into the Server Side location
Run npm run-script build. Please note this is customized in package.json to generate and copy the client code to the server.

theia@theiadocker-garethjones2:/home/project/cazgi-IBM-Watson-NLU-Project/sentimentAnalyzeClient$ npm run-script build

# Change to the server side.

cd /home/project/cazgi-IBM-Watson-NLU-Project/sentimentAnalyzeServer

Run the server. This will start on port 8080.

npm start

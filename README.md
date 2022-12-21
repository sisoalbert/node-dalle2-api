
## Getting Started Follow these instructions to get the Node.js server up and running on your local machine.

**

Prerequisites Make sure you have the following installed on your machine:

Node.js npm (comes with Node.js) 

**Step 1:** Initialize the project Run the following command in the terminal to initialize the project and create a package.json file:

 

    npm init -y
 

Step 2: Install dependencies Run the following command to install the necessary dependencies:

    npm i express openai dotenv 

**Step 3:** Install dev dependencies Run the following command to install the necessary dev dependencies:

    npm i -D nodemon

 

Step 4: Create start and dev scripts Add the following scripts to your package.json file:

    "scripts": { "start": "node index.js", "dev": "nodemon index.js" }

 

**Step 5:** Set up environment variables Create a .env file in the root of your project and add the following variables:

    PORT=5000
    
    https://beta.openai.com/account/api-keys
    
    OPENAI_API_KEY ="sk-xxxxxxxx"
    
    https://beta.openai.com/account/org-settings
    
    OPENAI_ORGANIZATION="org-xxxxxxxxx"

Make sure to replace the values with your own API key and org id, which can be found at  [https://beta.openai.com/account/api-keys](https://beta.openai.com/account/api-keys)  and  [https://beta.openai.com/account/org-settings](https://beta.openai.com/account/org-settings)  respectively.

**Step 6:** Start the server Run the following command to start the server:

    npm run dev

This will start the server in development mode, using nodemon to automatically restart the server whenever you make changes to the code.

To start the server in production mode, use the start script:

    npm start

https://github.com/sisoalbert/

https://stackedit.io/app# 

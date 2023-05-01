Instruction to run the app


Password Manager

A Password Manager project created using the MERN stack. You can login and save your passwords. Passwords are saved in the database after AES encryption ⛓️ . So, your passwords are safe here. 


Setting up the services
To setup the services in your system run the following commands

cd password-manager-services

npm install


After installing all the dependencies run the password-manager-services using the following command


npm start

Now, the services will be up and running

**Note :- You have to configure all the environment variables by creating a config.env file in root server folder.

Structure of the config.env file

PORT,
DATABASE,
TOKEN_SECRET,
SERVER_ENCRYPTION_KEY 



Setting up the password-manager-ui
Go to the password-manager-ui folder and run


npm install

All the dependencies should be installed. Now, you just have to start the React server by following command


npm start

You also have to keep the mongodb atlas open in order to run the app properly.

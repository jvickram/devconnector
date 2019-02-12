# devconnector
It's a full stack application built on React, Redux, Express, Node, MongoDB(mlab).

# Steps to start the app
1. Create a account in mlab.com.
    create a database and in the database create a user.
2. Clone the app in your local machine.
3. For server: npm install
4. For client, change the path to client, then, npm install
3. Create a file name keys_dev.js in config/ folder and place the following code inside
    
    module.exports = {
      mongoURI: "mongodb://<username>:<password>@ds331145.mlab.com:31145/userauth",
      secretOrKey: "anything"
  };
4. Replace the mongoURI with your own, provided by database of your mlab.
5. To start the app run: npm run dev        

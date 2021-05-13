# vice-tbm-api-challenge


##Description

A simple API using Node.js, Express, MySQL, and Redis that allows you to create, list, and delete comment data. 

The table in the MySQL database stores anonymous author's comments in a column field named `content`. Each comment left will have an `id` that is autogenerated and autoincremented, as well as a `time` field that takes the current date/time that the POST request was made. 




## Testing Steps 

* From your terminal window, `npm install` to install the dependencies.
* There is a very simple seed file `seed.js` that you can populate your database with by running the command `node seed.js`
* You should be able to make GET, POST, and DELETE requests to the `localhost:5000/comments` endpoint and see the changes reflected in your data

# README

This project demos a social publishing platform. Users can login, register, make a post, like and comment. 

It is written using GrapQL, MERN (MongoDB, Express, React and Node) and Apollo Server.

The server is set up and connected to the MongoDB database in *index.js*

*users.js*, *posts.js*, *comments.js*,  all contain query resolvers with validations and error checking. 

The client folder contains the React files

The project uses semantic UI components

Routes are used to navigate betwene *Home.js*, *Login.js*, *Register.js* and *SinglePost.js* pages

Posts are displayed on the front page as they are posted

Used *AuthContext* so you can only post after you login or register

After you login or register, you can make posts, delete posts, comment on other posts. 

To run the program you 

```jsx
index node
```

outside the client folder

inside the client folder

```jsx
npm start
```

to see the program live
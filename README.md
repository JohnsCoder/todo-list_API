
### This project consist in an API, where you can create a user, register and save an todo note.

Clean Architechture.

Authenticated routes with middlewares and JWT Tokens.
## GO TO [FRONT-END](https://github.com/JohnsCoder/myOauthTodo-frontend)
## UML ![MyTodo](https://github.com/JohnsCoder/myTodo-backend/assets/62973765/8c43a4c8-17e4-4919-8d90-85b296734b3b)



## Routes

- register - /auth/register
- login - /auth/login
- auth - /auth/
- get nickname - /user/nick (authenticated by Bearer token )
- get, post, delete todo - /todo (authenticated by Bearer token)



## Run
to install all project dependencies execute:
`yarn` or `npm i`

to compile the code to js execute:
`yarn build` or `npm run build`

to start the application, in another tab execute: 
`yarn dev` or `npm run dev` 

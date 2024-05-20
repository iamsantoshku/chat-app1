# WeChat - Chat Application 
i have created user register page after successful registration user will redirect to chat page, user data will be save in database than user can login with same username and password..
when chat will be end user can logout.
Both should be installed and make sure mongodb is running.
### Installation

#### First Method
```
cd chat-app-react-nodejs
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
```
Done! Now open localhost:3000 in your browser.


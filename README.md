# Thinkify<br/><br/>

Thinkify is a vibrant space where people from diverse backgrounds and interests come together to engage in meaningful conversations, fostering an environment rich in idea exchange, knowledge sharing, and diverse experiences.<br/><br/>

# Preview<br/><br/>

<img src="/preview.png"><br/>
<a href="https://thinkify.vercel.app" target="_blank">Live Preview</a> | <a href="https://thinkify-server.vercel.app" target="_blank">Live API</a> | <a <br/>href="https://documenter.getpostman.com/view/27027258/2sA3dxEXJh" target="_blank">Postman</a><br/><br/>

# Requirements<br/><br/>

[Install Node On Your Device](https://nodejs.org/)<br/><br/>

# How to Run<br/><br/>

```
git clone (https://github.com/dvRaj22/Thinkify)

# BACKEND<br/>
cd server<br/>
npm install<br/>
npx nodemon index.js<br/><br/>

# FRONTEND<br/>
cd ../client<br/>
npm install<br/>
npm run dev<br/>
```

# Environment Variables<br/><br/>

## Frontend<br/><br/>

```

VITE_TOKEN_KEY = thinkify<br/>
VITE_USER_ROLE = role<br/>
VITE_COOKIE_EXPIRES = 1<br/>
```

## Backend<br/><br/>

```
PORT = 3000<br/>
DATABASE_URL = mongodb://localhost:27017/<br/>
DATABASE_NAME = thinkify<br/>
BCRYPT_GEN_SALT_NUMBER = 10<br/>
JWT_SECRET_KEY = abcdefghijklmnopqrstuvwxyz<br/>
COOKIE_EXPIRES = 5d<br/>
COOKIE_KEY = thinkify<br/>
UPLOAD_DIRECTORY = uploads<br/>
```

# Features<br/>

## Admin<br/><br/>

- Profile<br/>
  - Last Month User Activity<br/>
  - Role Based User Distribution<br/>
- Users Management<br/>
- Sign Out<br/><br/>

## Student<br/><br/>

- Profile<br/>
- Add Post<br/>
- My Posts<br/><br/>
- Add Product<br/>
- My Products<br/>
- Task Manager<br/>
- Setting<br/>
  - Change Password<br/>
- Sign Out<br/><br/>

# Contribute<br/><br/>
## Institution/Teacher<br/><br/>
- post(text, image)<br/>
    - by admin/institution<br/>
    - by teacher<br/>
- assignments<br/>
- poll<br/>
- resource sharing<br/>
- test<br/><br/>

### Assignments<br/><br/>
- title<br/>
- description<br/>
- subject<br/>
- deadline<br/>
- total marks<br/>
- status<br/>
- audience<br/><br/>
### Polls<br/><br/>
- title<br/>
- description<br/>
- type(singl, multiple)<br/>
- options<br/>
- deadline<br/>
- status<br/>
- anonymous member<br/>
- audience<br/><br/><br/
### Resource<br/><br/>
- title<br/>
- description<br/>
- visibility<br/>
- url<br/>
- audience<br/><br/>
#   T h i n k i f y 
 
 

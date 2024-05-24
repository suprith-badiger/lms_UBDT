**Study-Notion Online Education Platform (MERN App) [Website Link](https://studynotion-frontend.vercel.app/)**

clone the repository

```bash
git clone https://github.com/suprith-badiger/lms_UBDT.git
```

To run frontend

```bash
npm install
npm run start
```

To make backend server up and running

```bash
cd server
npm install
npm run start
```

create a .env file in server folder [ ./server/.env ]

```bash
#  mongoDB
MONGODB_URL = ""

# port number for server
PORT = 4000

# cloudinary
CLOUD_NAME = ""
API_KEY = ""
API_SECRETE = ""

# Mail host
MAIL_PASS = ""
MAIL_USER =

# jwt token
JWT_SECRET = ""

# payment gateway credentials
RAZORPAY_SECRET = ""
RAZORPAY_KEY = ""
```

for getting the MAIL_PASS follow the below steps:

- Visit your Gmail account manager and click on “manage your Google Account”
- click on “Security” to turn on 2-step verification
- scroll down and find App passwords
- create a new app password and copy the password
- use that password as MAIL_PASS in .env file


# StoryBooks

  
An application for people to store their private stories or share them publicly. The application is built out of NodeJS, ExpressJS and MongoDB.

  

### Steps to use this project

  

- Install all the node_modules using `npm install` command after cloning this repository.

- Create a cluster on MongoDB.

- In the config folder create a file called config.env and use the following variables appropriately:

	-  `PORT` = Port  number  to  run  your  application

	-  `MONGO_URI` = The  URL  obtained  after  creating  a  cluster  on  MongoDB  and  replace  appropriate  parameters

	-  `GOOGLE_CLIENT_ID` = Go  to  google  console  and  create  an  Oauth20  and  get  its  client  id

	-  `GOOGLE_CLIENT_SECRET` = On  the  same  page  of  google  console  get  the  google  client  secret  too

- Run the application in:

	 - Development mode: `npm run dev`

	- Production mode: `npm start`

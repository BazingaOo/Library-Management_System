# IMDB_Clone_System
## Project Topic and Group Members
We will develop an IMDB Clone system with functionalities, such as movie recommendation, movie ratings, movie genre searching, movie comments and criticization. Our team members are: Shihuan Wang, Tao Zhang, Zihan Guo and Yuxuan Wang. <br />

## Project Abstract
1. We plan to develop an IMDB clone system for movies with several functionalities, movie recommendation, movie ratings, movie genre searching, and movie comments and criticization. <br />
2. Our first milstone is mainly about the home page of our IMDB Clone web app, which contains the log in option to sign in our users' personal account. And there would also be another dashboard page for users when they sign in their account. <br />
3. The front-end of our web app would be developed on Vue.js frame. And in our first milestone, we would show a web page with the main page of the IMDB clone system and build up the connection between the front-end and the back-end. <br />
4. The back-end of our web app would be developed on GoLang platform to build up our users' personal information module when they sign in their account in our first milestone.

## Front-end User Interface
We use Bootstrap css based UI framework, Vue.js javascript framework, and Vue CLI globally installed npm package to build up our web app's user interface. 

## Project Set-up and Installation of Environment
To compile our web app, you need to go to Node.js website, (https://nodejs.org/en/), to install Node.js javascript runtime engine.

### Install npm package
```
npm install
```

### Install Vue CLI
```
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Add Bootstrap in Vue.js
```
npm install bootstrap
# OR
yarn add bootstrap
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## User Stories
1. Sign-up User's Personal Account Functionality
  * Priority: 3 stars/5 stars; Estimate: Not too hard, 30 points/100 points.
  * As a movie fan who likes watching a pecific types of movies, I want to sign up a personal account and set up my movie genre's preference, so that I can keep my personal information and get related recommendation of movies.
  * Acceptance Criteria: Given the page of typing username and password, When the personal account is sign-up, the web page would jump into logged account, Then the web page would ask users to fill-out their personal information and preference of movie genre. Our web app would provide recommended movies for log-in users. 

### IMDB_Clone Mind Map
<img src="/IMDB_Clone_Min_Map.jpg" alt="IMDB_Clone Mind Map"/>

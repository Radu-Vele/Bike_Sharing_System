# Bike Sharing Web App 🚲

> ❕ The project is under development and some work might not have been integrated onto the main branch. To see latest updates navigate to the backend/frontend repos on the other branch but main.

> A web application for managing a bike-sharing system. The system involves only the self-reported user activity (no background check for any actual physical bikes).

Contributors: 
* [Kiss Borbála](https://github.com/KissBorbala/) 
* [Păun Andreea-Oana](https://github.com/AndreeaPaun12) 
* [Vele Radu-Augustin](https://github.com/Radu-Vele)

## Tech stack 
- ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

## Project status
- the project is currently `under development` 🚈.

## GUI Screenshots
See below some screenshots from the app.
### Home page (users not logged in)
![Home page - not logged in](screenshots/home_login.png)
### Home page (logged in user)
![Home page - logged in](screenshots/home_map.png)
### Account info page
![Account Info](screenshots/account_info.png)
### Current Ride
![Current ride](screenshots/current_ride.png)

## How to run the project
The project is version controlled using a wrapper repository (the one that contains this README file) over two modules (one for the frontend and one from the backend).
- after cloning the [wrapper repository](https://github.com/Radu-Vele/Bike_Sharing_System) run the following commands to clone the modules for the frontend and backend:
    - `git submodule init`
    - `git submodule update`
- make sure you are on the `main` branch in each repo.

### MongoDB Database
- `TBA`

### Backend using IntelliJ
The steps are described below:
- import project from existing sources (select the backend folder)
- setup the SDK (Java 17 is recommended)
- setup maven: in Maven Settings/ set the maven home path to Bundled (Maven 3)
- make sure all dependencies are resolved and run the `@SpringBootApplication` from `SeProjectBackendApplication.java`.

### Frontend using VSCode
- open a terminal in the project directory and run the commands `npm install` and `npm start`.
- make sure to open the `localhost:3000` in incognito mode (Google Chrome is used during development) with CORS enabled.

## Credits
- the organization of the project packages and modules was inspired by [Purshink Full Stack App Repository](https://github.com/purshink/ReactJS-Spring-Boot-Full-Stack-App.git)

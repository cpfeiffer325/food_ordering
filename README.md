# Project Description
My first group project. In a team of 2-3 randomly assigneed by Lighthouse Labs we will have five days to build a full stack web app for a client of choice. The client will provide the requirements and you will decide how the experience will look and feel.

## Option Choosen by Group: Food Pick-up Ordering
A food ordering experience for a single restaurant. Hungry clients of this fictitious restaurant can visit its website, select one or more dishes and place an order for pick-up. They will receive a notification when their order is ready.

The restaurant and client both need to be notified since this app serves as an intermediary.

When an order is placed the restaurant receives the order via SMS. The restaurant can then specify how long it will take to fulfill it. Once they provide this information, the website updates for the client and also notifies them via SMS.

You can use a modern telecomm API service such as Twilio to implement SMS communication from the website to the client and restaurant.

## Goal
Build a web app from start to finish using the tech and approaches learned to date
Turn requirements into a working product
Practice architecting an app in terms of UI/UX, Routes/API and Database
Manage a multi-developer project with git
Simulate the working world where you do not always get to completely cherry pick your team, stack or product features
Practice demoing an app to help prepare for the final project and employer interviews


## Pinocchio Pizza
Pinocchio Pizza is a food-take-out-ordering application that serves both: the customer and the restaurant. It acts as an intermediary. When the customer submits the order they provide their phone number, restaurant receives the order as a SMS message. The restaurant sends a response to the customer also by SMS, which lets them know how long it will take until the order is ready for pickup. 

## Features
![home](https://github.com/superskyy/food_ordering/blob/master/docs/home%20html.png?raw=true)
![index](https://github.com/superskyy/food_ordering/blob/master/docs/index%20html.png?raw=true)

## Getting Started

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Update the .env file with your correct local information
3. Install dependencies: `npm i`
4. Fix to binaries for sass: `npm rebuild node-sass`
5. Run migrations: `npm run knex migrate:latest`
  - Check the migrations folder to see what gets created in the DB
6. Run the seed: `npm run knex seed:run`
  - Check the seeds file to see what gets seeded in the DB
7. Requires the setup of a Twillio Account to run sms messaging
8. Download ngrok from `https://ngrok.com/download`
9. In a separate terminal run `../ngrok http 8080` 
10. Run the server: `npm run local`
11. Visit `http://localhost:8080/home`

## Dependencies

- Node 5.10.x or above
- NPM 3.8.x or above
- Body Parser 1.15.x or above
- Dotenv 2.0.x or above
- EJS 2.4.x or above
- Express 4.13.x or above 
- Knex 0.11.x
- Knex Logger 0.1.x or above
- Morgan 1.7.x or above
- Node SASS Middleware 0.9.x or above
- pg 6.0.2 or above
- Twilio 3.31.x or above
- Nodemon 1.9.x or above

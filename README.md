# Angular Ecommerce Web App

This project was developed with the aim of gaining proficiency in Angular and MySQL fundamentals. While the learning curve was initially challenging, I found the experience rewarding as I became more familiar with the technologies. 

In addition to Angular and MySQL, the project utilizes Ant Design for its user interface and SwiperJS for carousel functionality. On the backend, Node.js and Express.js are employed, with input validation handled by Joi and authentication managed through JWT.

While a demo link is not currently available, detailed instructions for setting up the project on your local machine are provided.

<br/>

![](1.gif)
![](2.gif)

## Functionality

The application enables users to browse the home page for products, view detailed information about each product, and add items to their cart for future checkout.

When products are successfully added to the cart, a notification pops up to confirm the action.

Users can view a summary of their cart on the top bar or access a more detailed cart page.

The checkout process involves a multi-page form, culminating in the ability to place an order, which will subsequently be displayed on the order history page.

<br/>

## Getting Started

The app can be installed by cloning the git repository

```
git clone https://github.com/maxwellharon/angular-ecommerce-app.git folder-name
```

Then cd into both directories and run npm install

```
cd folder-name
cd backend
npm run install
cd.. // return to folder-name
cd client
npm run install
```

<br/>

After the entire installation you need to run the server and the client by running this commands each in its own directory

**backend**

```
npm run dev
```

**client**

```
ng serve
```

<br/>

## Prerequisites

You will need to have node and npm installed. In addition you will need a MySQL server running in order to have full functionality of the application

<br/>

## Environment Variables

Create a folder called env in the root of the backend directory and create a development.env file.

**Change DB variables to match your MySQL setup**

```
PORT=5000
DB_HOST='localhost'
DB_USER='root'
DB_PASSWORD=''
DB_NAME='myapp'
```

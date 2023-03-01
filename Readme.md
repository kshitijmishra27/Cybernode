# Cybernode

This is a sample application that demonstrates an E-commerce website using the MERN stack. The application loads 
products a MongoDB database and displays them. Users can select to display products in a single category. Users can 
click on any product to get more information including pricing, reviews and rating. Users can select items and 
add them to their shopping cart

## Import Data
I have included a data folder in this repo. Inside that folder will be 2 folders called cart and item. These 2 folders contain a mongodump of the 2 collections that I use in this ecommerce demo. You can use the [import-data.sh](data/import-data.sh) script to import these 2 dumps to an ecommerce database, then you will have the same content that I have for this demo.

## Live Demonstration

The E-commerce demo can be [viewed online here]().

Here are screenshots that show the E-commerce demo application in use.

**Home Page**
![Home Page]()

---

**Item Detail Page**
![Item Detail]()

---

**Shopping Cart**
![Shopping Cart]()

## Getting Started
To get started  you can simply clone this `Cybernode` repository and install the dependencies.

Clone the `Cybernode` repository using git:

```bash
git clone https://github.com/ratracegrad/ecommerce-demo
cd ecommerce-demo
```

Install dependencies with this command:
```bash
npm install
```

Run the application with this command:
```bash
npm start
```

## Tech Stack
* React.js
* Node.js
* Express.js
* Mongodb

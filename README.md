# Online Shopping

## Overview

This is a server-side application for an online shopping platform.
It allows users to browse products, add items to their cart, and proceed to checkout.

Admin users can manage products and other users, including adding new products, updating existing ones, and running products out of stock.
They can also view all users and their details, as well as change their data and role.

The application is built using Java Spring Boot for the backend and VueJS for the frontend.
The frontend application's repository can be found [here](https://github.com/dolev-goaz/online-shopping-client-side/tree/dev)

## Requirements

- IntelliJ IDEA (That's what I've used at least)
- Java 17

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dolev-goaz/online-shopping-server-side.git
   cd online-shopping-server-side
   ```
2. Set Java Version:
   1. Go to `File` > `Project Structure` > `Project`
   2. Set `Project SDK` to Java 17 (may need to add it if you haven't already)
   3. Set `Project language level` to `17`

3. Setup the database:
   ```bash
   docker-compose up --no-start
   ```

## Usage

To run the server, do the following:

1. Start the database:
   ```bash
   docker-compose up
   ```
2. Go to `src/main/java/OnlineShopping/OnlineShoppingApplication.java`
3. Click on the green play button next to the `main` method to run

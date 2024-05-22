# Simple Banking Web App

Welcome to the Simple Banking Web App! This project is a basic banking application built with React and Redux. It allows users to perform simple banking operations such as depositing money, withdrawing money, taking loans, and paying back loans. This project does not include a backend; all data is managed in the frontend using Redux.

## Features

Deposit Money: Users can deposit a specified amount of money.
Withdraw Money: Users can withdraw a specified amount of money.
Take Loan: Users can take a loan of a specified amount.
Pay Loan: Users can pay back a specified amount of their loan.
Demo

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following software installed:

Node.js
npm (Node Package Manager) or yarn
Installation
Clone the repository

### Project Structure

src/: This directory contains the main source code for the application.
components/: Reusable React components.
redux/: Redux-related code, including actions, reducers, and store configuration.
App.js: The root component.
index.js: The entry point of the application.
Redux Setup
The application state is managed using Redux. The key Redux components used are:

Actions: Defined in src/redux/actions.js. These are the actions for depositing money, withdrawing money, taking a loan, and paying back a loan.
Reducers: Defined in src/redux/reducers.js. These handle the state changes based on the dispatched actions.
Store: Configured in src/redux/store.js. The store is the centralized state management entity for the application.
Contributing
Contributions are welcome! Please follow these steps to contribute:

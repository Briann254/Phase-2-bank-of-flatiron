**Bank of Flatiron App**

**Description**
This is a simple bank app that displays a table of transaction data and allows users to search for specific transactions, add new transactions and view the data.

**Getting Started**
To get started, you need to have Node.js and npm (Node Package Manager) installed on your machine. Once you have that set up, you can clone the repository, navigate to the project directory and run npm install to install all the dependencies.

**Setup**
​​ - Clone the repository using git@github.com:Briann254/Phase-2-bank-of-flatiron.git

navigate to the project directory
Run npm install in your terminal.
Run npm run server. This will run your backend on port 3000.
In a new terminal, run npm start. This will run your React app on port 3001.
Usage
Use the search bar to search for specific transactions by category Use the form at to add new transactions The table will automatically update with new transactions

**Functionality**
The application fetches transaction data from the specified endpoint (http://localhost:3000/transactions) and sorts the data alphabetically based on the description property using the Array.prototype.sort() method with a comparator function that compares the description property of each transaction.

Then it is rendered on the page using the Table component and passed as a prop.

**Conclusion**
This application is a simple demonstration of how to fetch data from an endpoint, sort the data and display it in a tabular format using React.js. It can be further built upon to add more functionalities and features.

**Copyright 2023**
[Brian Nderitu]

**License**
The MIT License (MIT) Copyright (c) 2023 Brian Nderitu

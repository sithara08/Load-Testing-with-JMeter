# Demoblaze Performance Testing with Apache JMeter

This repository contains a JMeter test plan (`.jmx`) to evaluate the performance of the [Demoblaze](https://www.demoblaze.com/) e-commerce demo site. The plan simulates real-world user scenarios including signup, login, browsing products, adding items to cart, and logout.


## Features

- Simulates user interactions on an e-commerce website
- Includes realistic think times using **Uniform Random Timer**
- Assertions to validate response correctness
- Graphical and tabular result listeners

## Test Scenarios Covered

1. Accessing the home page
2. User sign-up
3. User login
4. Browsing the phones category
5. Adding a phone to the cart
6. Logging out


## How to Run

1. Clone the repository
2. Open DemoblazeTest.jmx in JMeter.
3. Modify thread count, ramp-up period, or duration as needed.
4. Click the green Start button to run the test.
5. View results in Results Tree, Table, or Aggregate Graph.



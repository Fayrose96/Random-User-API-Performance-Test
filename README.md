# Random-User-API-Performance-Test

## About this project:
### This project demonstrates how to perform load testing and stress testing using Apache JMeter. Our goal is to evaluate the performance of the web application named (Random data API) under various load conditions and identify the stress points/bottleneck point.

## Prerequisites
- JMeter 5.6.2
- Java Development Kit (JDK)
  
### Installation
1. Download and install Apache JMeter from [the official website](https://jmeter.apache.org/download_jmeter.cgi).
2. Clone this repository or download the project files.
  
### Configuration
1. Open JMeter.
2. Load the provided test plan (`load_test_plan.jmx`) into JMeter.
3. Configure test variables and endpoints as needed in the test plan.
   
## Running the Tests
1. Open a terminal and navigate to the JMeter bin directory.
2. Execute the following command to run the load test:

   ```shell
   jmeter -n -t path/to/load_test_plan.jmx -l path/to/results.jtl

 ## Test Report
   ![DMoneyJmeterReport](https://github.com/Fayrose96/demo-transaction-api-jmeter/assets/143695839/f6ccadfb-89c3-4ab1-8626-840cd47e464e)

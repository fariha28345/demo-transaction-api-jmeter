# demo-transaction-api-jmeter

## Technology Used
- Apache JMeter
- Java

## Scenario
Based on following scenario, creating a JMX file:
1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Merchant account: 01686606905)
7. Assert expected customer balance

## How to run this project
- clone this project
- save the DmoneyApi.jmx file into bin folder of installed location of Jmeter
- open the DmoneyApi.jmx file with jemeter & run the project
- to Generate report on the command prompt, delete the already copied .csv file and Report folder from the project
- hit the command:
- $ jmeter -n -t Jmx_Dmoney_Api.jmx -l Jmx_Dmoney_Api.csv -e -o Reports

## Html Report
![_D__apache-jmeter-5 5_bin_Reports_index html(Nest Hub Max)](https://github.com/fariha28345/demo-transaction-api-jmeter/assets/50767962/a40f6c1a-4c37-46e8-8351-5cbfe1542c64)

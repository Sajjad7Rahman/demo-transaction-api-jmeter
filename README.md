# demo-transaction-api-jmeter

## Technology Used:
1. Postman
2. Apache Jmeter
3. Windows PowerShell
4. Microsoft Visual Studio Code

## Server Used:
http://dmoney.roadtocareer.net

## Working scenerio of this Project:
1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (from Ac: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from agent account to (Merchant account: 01686606905)
7. Assert expected customer balance

## How to Generate Load_Test report using CLI command:
jmeter -n -t .\FileName.jmx -l .\FileNamelog.csv -e -o Name of Reports

## Load_Test Result View:

![Capture11](https://github.com/Sajjad7Rahman/demo-transaction-api-jmeter/assets/134221688/c0c17f28-07dd-4417-a691-af43e6f05bf5)
![Capture12](https://github.com/Sajjad7Rahman/demo-transaction-api-jmeter/assets/134221688/ebfd03aa-a660-4436-ba1e-7112494bcbba)
![Capture13](https://github.com/Sajjad7Rahman/demo-transaction-api-jmeter/assets/134221688/c582d86c-6db7-466a-b81d-99fbf3f2f431)
![Capture14](https://github.com/Sajjad7Rahman/demo-transaction-api-jmeter/assets/134221688/029d9423-3cb8-4ac9-9fa8-00756a596ea4)




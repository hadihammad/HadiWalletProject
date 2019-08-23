# HadiWalletProject
Creating Customer and a Wallet by a rest API calls.

# To Run the app
go to target folder then
```sh
java -jar hadiwalletproject-0.0.1-SNAPSHOT.jar
```

# How to Use
| Start Here | Link |HTTP Methods|
| ------ | ------ | ------ |
|Root|http://localhost:8080/|GET|
|Create Customer|http://localhost:8080/customer/addCustomer|POST|
|Create Wallet|http://localhost:8080/custumerId={custumerId}/addwallet|POST|
|get Custumer info|http://localhost:8080/customerId={custumerId}|GET|
|get all Customers info|http://localhost:8080/customer/allCustomers|GET|
|add Credit to Customer|http://localhost:8080/custumersId={custumerId}/addMoneyByCreditToSarWallet={amount}|PATCH|


# Testing App
Use this app, [Postman](https://www.getpostman.com/)

# Chapter One - ITISDEV Project

## Follow the steps below to set-up :
1. Clone the repository either by downloading the contents of the repository, or using the command below (Note: git should be installed in your system for this to work).
```
git clone 

```
2. Open Command Prompt
3. Navigate to the project folder - the folder containing the contents of the cloned or downloaded repository.
4. Run the command `npm install` to initialize and install all necessary modules used in the project.

5. Run the command 'npx nodemon index' to run the program. Run the command 'rs' to manually restart the port. Nodemon is installed for easier restarting of the run when making changes.
6. Now enter the link below to your browser:
```
http://localhost:9090/
```

## Sample Users

| Type | Username    | Password |
|-------|---------------|--------|
| Admin | seanxnieva    | secret |
| Admin | katemagbitang | secret |
| Admin | shimeizhang08 | secret |
| Admin | oninolan      | secret |
| Regular | willowsmith | secret |

# Features

## Create User Account

Users must create an account to buy and request books. Name, email address, and password are needed.
![Create User Account](/screenshots/Create%20User%20Account.png)

## Login Account

Users can login using their registered email and password.
![Login](/screenshots/Login.png)

## Add/Remove Item to Cart & Checkout
Users can add items into their cart. Users can remove items from their cart.
![Add/Remove Item to Cart & Checkout](/screenshots/Add%20remove%20Item%20from%20Cart%20%26%20Checkout.png)

Users can checkout their cart. This will update the inventory accordingly. If the user was not able to provide proof of payment within 3 days, the order will be cancelled and the inventory will adjust accordingly.

## Send Payment Details
Users will be required to send payment details which can be a photo or text with OR. This will be confirmed by the admin later on in the “Confirm Payment”
![Send Payment Details](/screenshots/Send%20Payment%20Details.png)

## Confirm Payment
The admin can confirm if the proof of payment of the user is valid. This will then record the sales officially.
![Confirm Payment](/screenshots/Confirm%20Payment.png)

## Add Products
Admins can add or edit products in the catalog.
![Add Products](/screenshots/Add%20Products.png)

## Generate Sales Report
The admin can generate sales reports given a timeframe.
![Generate Sales Report](/screenshots/Generate%20Sales%20Report.png)

## Send Private Message
Users and admins can communicate with each other asynchronously.
![Send Private Message](/screenshots/Send%20Private%20Message.png)

## Request a Book
Users can request a book by providing the book’s title and author. Users may also specify if it is urgent, and up to how much they are willing to pay for the book. These, along with time, will affect the prioritization of the request.
![Book Request Form](/screenshots/Book%20Request%20Form.png)
![User Book Request List](/screenshots/User%20Book%20Requests.png)

## Generate Requested Books
The admin can view the requested books in either individual requests view or collective book requests view. There will also be a tab for requests that are cancelled and soon to be automatically cancelled. From here, the admin can fulfill requests.
![Generate Requested Books](/screenshots/Fulfill%20Request%20Book.png)

## Fulfill Request
The admin can fulfill book requests from the users. Fulfilling a request will send a notification to the requesting user with the link to the requested item. The system will automatically add the fulfilled item to the user’s cart.
![Fulfill Request](/screenshots/Fulfill%20Request%20Book%20Form.png)

## Notify to Update Interest on Requested Book
The user will be notified every 2 weeks, if they are still interested in the requested book. 

## Override Automatic Cancellation of Request
The admin can see a list of cancelled and soon to be automatically cancelled book requests. The admin can override the automatic cancellation of requests. By doing so, the system will ignore the requirements for auto cancellation of requests.

Requests are automatically cancelled if the user has not logged in for 21 consecutive days or has ignored 3 consecutive notifications to update interest on the requested book.

# Authors
* Sean Nieva
* Kate Magbitang
* Shimei Zhang
* Olan Onin
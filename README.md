# Express

## Book Record Management System.(project)
>> server
   1. Storing Book Data.
   2. User Registration.
   3. Subscription.

## Routes and  Endpoints.

## /users
1. GET: Get all list of users.
2. POST: Create a new user.

## /users/{id}
1. GET: Get a user by their ID.
2. PUT: Update a user by ID.
3. DELETE: Delete a user By ID.(check he/she still have an issued book) && (is there any fine to be collected from him/her)

# Subscription Types:
1. 3 months.(Basic Subscription)
2. 6 months.(Standard Subscription)
3. 12 months.(Premium Subscription)

## /users/subscription-details{id}.
GET: Get users subscription details.
 1.  Data of Subscriptions.
 2.  Valid Till.
 3.  Fine if any.

## Book details.

## books/
1. GET: Get all books.
2. POST: Create/Add a new Book to a system.


## /books/{id}
1. GET: Get a book by ID.
2. PUT: Update a by its ID.

## /books/issued.
1. GET: Get all issued books.

## /books/issued/withFine
1. GET: Get all issued book with fine.

## Fine Calculation.
  1. >> If the user has an issued book and issued book is to be returned at 1/01/2024.
  If he missed the date of renewal/return, then he needs to pay a penalty of Rs. 100/-

  2. >> If the user has an issued book and issued book is to be returned at 1/01/2024.
  If he missed the date of renewal/return and his subscription also expires, then he needs to pay a penalty of Rs. 200/-


## commands: 
1. npm init
2. npm i express
3. npm i nodemon--save-dev

## Run Command
1. npm run dev
# PrimeCheckApi
it is a test application for creation of APIs to check if the number is prime or not.

How to Run Locally
🔧 Prerequisites
Java 8 or above

Maven installed

🚀 Steps
Clone or create the project folder.

Place the code in correct directories.

Open terminal and navigate to the project root.

Run:

bash
Copy
Edit
mvn spring-boot:run
By default, it will run at: http://localhost:8080

🧪 How to Test the Endpoint
📱 Using Browser or Postman

Endpoint:

http
`GET http://localhost:8080/api/isPrime?number=13`
Response:

csharp

13 is a prime number.
Try:


``http://localhost:8080/api/isPrime?number=10``
You’ll get:

```
10 is not a prime number.```


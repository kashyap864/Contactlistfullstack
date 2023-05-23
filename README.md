# Contact List Full Stack Application

This is a Contact List Full Stack Application built with a Node.js backend using Express.js and MongoDB as the database. It provides functionality to create, read, update, and delete contacts.

## Features

- User-friendly API for managing contacts
- Create new contacts with a name, email, and phone number
- Retrieve all contacts
- Update existing contacts
- Delete contacts

## Prerequisites

- Node.js (version X.X.X)
- MongoDB (version X.X.X)

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/contact-list-app.git

Change to the project directory:
cd contact-list-app

Install the dependencies:
npm install

Configure the MongoDB connection:

Open the server.js file.
Modify the MongoDB connection URL (mongodb://localhost/contactlist) to match your MongoDB server setup.

Start the server:
npm start

The server should now be running at http://localhost:3000. You can use tools like cURL, Postman, or any HTTP client to interact with the API endpoints.

API Endpoints
GET /contacts
Retrieve all contacts.

POST /contacts
Create a new contact. Send a JSON object with the following fields in the request body:
{
  "name": "Aman",
  "email": "aman@example.com",
  "phone": "1234567890"
}

PUT /contacts/:id
Update an existing contact. Replace :id with the ID of the contact you want to update. Send a JSON object with the updated fields in the request body.

DELETE /contacts/:id
Delete a contact. Replace :id with the ID of the contact you want to delete.

License
MIT License

Feel free to modify the README file as per your specific application and add any additional sections or information that you think would be helpful for users to understand and set up your Contact List Full Stack Application.

Remember to replace the placeholders (e.g., `your-username`) with your actual information and provide accurate instructions for installation and usage.

I hope this helps you create a README file for your Contact List Full Stack Application!




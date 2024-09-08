# employee-review-system
live link :- https://employee-review-system-t9zs.onrender.com

This Employee review web application is created for employees to submit feedback toward each other's performance. User's could have either "employee" or "admin" role. There are two dashboard pages based on the role of the employee those dashboard pages will be rendered, User with role of admin can assign employees to participate in review of other employees. Employees can only submit feedback required by assigned reviews. \
It is built using NodeJs, ExpressJs, MongoDB, EJS and JavaScript.


## Functionality

### Admin's functions

- Add employee
- Delete employee
- Update employee details
- Assign review to employee
- Update review of employee

### Employee's functions

- Submit reviews assigned to it
- View reviews given by others

##  Getting started

- Fork the project
- Clone the forked repository in your local system
- Create .env file in the root directory and add the following:-
  - PORT="Your port number"(in the code it is local:3000)
  - MONGODB_URL="Your MongoDB URL"
  - SESSION_SECRET_KEY="Your secret session key"
- Install all required packages

bash
npm i


- Run project

bash
npm start

The project is running on the port number provided by you.

## 🛠️ Tools Used

- NodeJS
- MongoDB
- ExpressJS
- EJS
- Bootstrap

### 📚 Libraries:

- bcryptjs
- connect-flash
- connect-mongo
- cookie-parser
- dotenv
- ejs
- express
- express-ejs-layout
- express-session
- mongoose
- passport
- passport-jwt
- passport-local

### screenshots

![Screenshot 2024-02-23 at 3 54 30 PM](https://github.com/Sukesh-Hegde/Employee_review_system/assets/128299015/985c6def-e7de-4fd3-a599-a5c94c7e01c6)

![Screenshot 2024-02-23 at 3 54 19 PM](https://github.com/Sukesh-Hegde/Employee_review_system/assets/128299015/48743061-7276-44ce-9931-8a95f20cf62e)


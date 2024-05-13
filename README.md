# CMPE282

University Name:[San Jose State University](http://www.sjsu.edu/)

Course: CMPE-282 Cloud Services

Professor: [Andrew Bond](https://www.linkedin.com/in/ahbond/)

Students:

[Bhargav Krishna Mullapudi](https://www.linkedin.com/in/bhargavkrishna/)

[Satya Ashish Veda](https://www.linkedin.com/in/satyaashishveda/)

[Shireesh Vennamaneni](https://www.linkedin.com/in/shireesh-vennamaneni-9b906914a/)

[Sri Anudeep Velicheti](https://www.linkedin.com/in/sri-anudeep-velicheti/)

# SportLink

(![image](https://github.com/bkrish111/CMPE282/assets/147780244/5edb3cf1-90d6-4631-863d-91b855ed8724)



[SportLink](http://cloud-frontend-1659687937.us-east-1.elb.amazonaws.com/) is a platform designed to connect sports enthusiasts with available play areas. It simplifies the process of organizing sports activities by allowing users to find players, join games, and host events.


## Prerequisites:

Before you begin, ensure you have the following prerequisites installed on your system:

1. *Node.js*: Make sure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

2. *Java Development Kit (JDK)*: You need to have JDK installed to run the Spring Boot backend. You can download it from [OpenJDK](https://openjdk.java.net/).

3. *Git*: Ensure you have Git installed on your machine to clone the repository. You can download it from [git-scm.com](https://git-scm.com/).

4. *AWS Requirements*:  You need to setup rds, s3 bucket, DynamoDB, AppSync API. 

## Steps to Run the Project:

Follow these steps to run the project locally:

*###2. Backend (Spring Boot) Setup:*

a. Open Terminal in the slotService directory:
```cd slotService```

b. Build and Run the Spring Boot Application:
```./mvnw spring-boot:run```

The backend server will start running on http://localhost:8080.

*###3. Frontend (React + Node.js) Setup:*

```cd frontend```

b. Install Frontend Dependencies:
```npm install```

c. Start the React Development Server:
```npm start```

The React frontend will start running on http://localhost:3000.

*###4. User Creation (Node.js) Setup:*

a. Open Terminal in the usercreation directory within the backend folder:

```cd backend/usercreation```

b. Install User Creation Dependencies:
```npm install```

c. Start the User Creation Server:
```node server.js```

*###5. Event Creation (Node.js) Setup:*

a. Open Terminal in the eventcreation directory within the backend folder:

```cd backend/eventcreation```

b. Install Event Creation Dependencies:
```npm install```

c. Start the Event Creation Server:
```node app.js```


*###6. Play Area Status (Node.js) Setup:*

a. Open Terminal in the eventcreation directory within the backend folder:

```cd backend/PlayAreaStatus```

b. Install Play Area Status Dependencies:
```npm install```

c. Start the Play Area Status Server:
```node server.js```

*### ML Service Setup:*

a. Open Terminal in the MLservice directory:
```cd backend/mlService```

b. Start the ML Service with Uvicorn:
Use the following command to start the ML service using Uvicorn:

```uvicorn main:app --host 0.0.0.0 --port 3501 --reload```

Now, you should have the entire project up and running locally. You can access the frontend at http://localhost:3000 and make API requests to the backend at http://localhost:8080.

Make sure to update any configuration files or environment variables as needed for your specific project setup.


##Sample Screenshots:
![Screenshot 2024-05-12 225121](https://github.com/bkrish111/CMPE282/assets/147780244/63ba720c-a4b3-44e8-a534-ce35b06ea388)

![Screenshot 2024-05-12 225147](https://github.com/bkrish111/CMPE282/assets/147780244/cd0d4c44-1dd0-4cb5-b103-85b606d900e8)


![Screenshot 2024-05-12 225238](https://github.com/bkrish111/CMPE282/assets/147780244/02de459d-1a6e-4607-be1c-ba2eaff61a93)

![Screenshot 2024-05-12 225250](https://github.com/bkrish111/CMPE282/assets/147780244/f69d7ee2-b152-455a-99e5-89bc4bb2256a)


![Screenshot 2024-05-12 225313](https://github.com/bkrish111/CMPE282/assets/147780244/621d6963-6046-46b8-a56d-18672e4908a6)





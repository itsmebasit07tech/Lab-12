# **React + Raw Node.js Integration**



**Objective:**



To connect a React frontend with a raw Node.js backend using HTTP requests and a REST API.



**Technologies Used:**



React

Node.js

JavaScript

HTTP Module

REST API



**Project Structure:**



* **backend/server.js** - Creates the Node.js HTTP server and API endpoint.
* **frontend/src/App.js** - Fetches and displays data from the backend.
* **frontend/src/App.css** - Styles the React application.



###### **API Endpoint**

###### 

GET /api/info



**Response:**



{

&#x20; "info": "React is communicating with Node.js"

}



**How to Run:**



**1.**Start the backend from the project root:



node backend/server.js



**2.** Open another terminal and start React:



cd frontend

npm start



**3.** Open http://localhost:3000 in your browser.



**4.** Test the backend at http://localhost:5000/api/info.



**Working**



The Node.js backend handles HTTP requests and returns a JSON response. The React frontend uses useEffect() to fetch the response and useState() to store and display the message. CORS headers allow communication between the frontend and backend.



**Conclusion**



The project demonstrates successful communication between a React frontend and a raw Node.js backend using a REST API.


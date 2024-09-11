

# LiveChat Application
  This application built using Node.js, Express, Socket.io, Mongoose, RESTful Web Service.
  
  ![Screenshot 2024-02-17 103831](https://github.com/ryuga001/LiveChat/assets/127576851/615dca30-2536-4447-9d82-b32e9485c004)

  ![Screenshot 2024-02-17 105152](https://github.com/ryuga001/LiveChat/assets/127576851/31838925-bf74-41f0-86e7-0ba5e806b210)


  ![Screenshot 2024-02-17 104931](https://github.com/ryuga001/LiveChat/assets/127576851/099a4824-e3a3-4f70-abab-fa5dffa188a0)

  




![Screenshot 2024-02-17 104946](https://github.com/ryuga001/LiveChat/assets/127576851/a9de1c3e-1190-4931-9c34-51466da72802)
# Features

  <li> The application allows users to create an account with a unique username and password for secure login.</li>
  <li> The application has <b>JWT</b> authentication. </li>
  <li> After create account a user can select their <b>avatar</b>. </li>
  <li> Users can send interactive text messages in their chats. </li>
  <li> The app uses socket.io for real time messaging.</li>
  <li> The app has a user-friendly interface with easy navigation and intuitive controls. </li>
  <li> The app provides end-to-end encryption to ensure secure messaging and protect user privacy. </li>
  <li> The app has <b>wave animation</b> loader.</li>
   
# Installation

### Running Locally

Make sure you have Node.js and npm install.

  1. Clone or Download the repository 
    <pre>git clone https://github.com/ryuga001/LiveChat.git
    $ cd LiveChat</pre>
  2. Install Dependencies
      <pre>npm install</pre>  
  3. Start the Application
     <pre> $ cd frontend
       npm start</pre>
     <pre>$ cd backend
       node index.js</pre>
  
 ## Sockets
    
   Having an active connection opened between the client and the server so client can send and receive data. This allows             real-time communication using TCP sockets. This is made possible by Socket.io.

   The client starts by connecting to the server through a socket(maybe also assigned to a specific namespace). Once connections is successful, client and server can emit and listen to events. 

## RESTful

  Using HTTP requests, we can use the respective action to trigger every of these four CRUD operations.    
    <li>POST is used to send data to a server — Create</li>
    <li>GET is used to fetch data from a server — Read</li>
    <li>PUT is used to send and update data — Update</li>
    <li>DELETE is used to delete data — Delete  </li>
    
## Tech Stack
   React.js
   Node.js
   Socket.io
   Expres.js
   Redux

<h1 style="text-align: center;">HAMNSKART - E-commerce Platform</h1>
<p>Download the application, place the folder in VsCode, and run the following command:</p>
<code>npm run dev</code>
<p>Admin account: admin@admin.com Password: 123456</p>
<p>User account: dragos@gmail.com Password: 123456</p>
<h3>Description</h3>
<p>DMShop is an e-commerce platform that allows users to browse through store products, add items to their shopping cart, and complete the checkout process.</p>
<h3>Technologies Used</h3>
<h5>Frontend:</h5>
<p><b>React:</b> A JavaScript library for building user interfaces.</p>
<p><b>React-Bootstrap:</b> A set of components for React, based on the Bootstrap framework.</p>
<p><b>React-Router:</b> A library for routing pages in React.</p>
<p><b>Redux (also on the backend):</b> An open-source library for managing application state.</p>
<h5>Backend:</h5>
<p><b>Node.js:</b> A JavaScript runtime built on Chrome's V8 engine, used for creating backend applications.</p>
<p><b>Express.js:</b> A lightweight framework for Node.js that simplifies server development and routing.</p>
<p><b>MongoDB:</b> A scalable and flexible NoSQL database that stores data in a JSON-like format.</p>
<p><b>Mongoose:</b> An ODM (Object Data Modeling) library for MongoDB that simplifies working with the database.</p>
<p><b>JSON Web Tokens (JWT):</b> An open standard for securely transmitting information between parties as a JSON object.</p>
<h3>Structure:</h3>
<h5>Frontend:</h5>
<p><b>actions:</b> Contains the actions that are called during user interactions with the application.</p>
<p><b>components:</b> Contains reusable React components for building the user interface.</p>
<p><b>constants:</b> Contains constants used to define action types.</p>
<p><b>reducers:</b> Contains reducers that manage the application's state and update the corresponding components.</p>
<p><b>screens:</b> Contains React components that represent the application's pages.</p>
<p><b>store.js:</b> Contains the Redux store configuration, which is used to manage the global state of the application and facilitate information exchange between different components more easily and efficiently.</p>
<p><b>App.js:</b> The main file of the React application, which defines the routing and navigation between different components of the application.</p>
<h5>Backend:</h5>
<p>The web application is divided into several essential parts, including:</p>
<p><b>Controllers:</b> These files handle the application's logic and data.</p>
<p><b>Data:</b> Files that contain predefined data for the application, such as products and users.</p>
<p><b>Middleware:</b> Functions that are called before the controllers execute, to process data or handle authentication.</p>
<p><b>Models:</b> Database schema and the structure of MongoDB documents.</p>
<p><b>Routes:</b> Routing and organizing various API requests.</p>
<p><b>server.js:</b> The main file in the backend of the application, responsible for starting the server and handling HTTP routes.</p>
<h5>Communication with the Backend</h5>
<p>Communication with the backend is managed through actions in the "actions" directory. Actions make HTTP requests to the backend API using the "axios" library. After receiving the response, the actions update the application state by calling the corresponding reducers. For example, the "addToCart" action makes a GET request to fetch product information and then adds the product to the shopping cart by calling the "cartReducer".</p>

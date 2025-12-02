# Travel and Tourism Management System MERN

The project is built using the MERN stack, where React.js handles the entire user interface and frontend interactions, while Node.js and Express.js form the backend that processes requests and exposes REST API routes. All data such as users, travel packages, bookings, and ratings is stored in MongoDB, which is accessed using Mongoose for structured data handling. Since the whole project uses JavaScript on both frontend and backend, it ensures smooth communication, faster development, and a scalable full-stack web application.

🔧 Technology Mapping

🟦 React.js – Frontend (UI)
Used to build all user-facing pages including Home, Login, Packages, Admin Dashboard, and Bookings.

🟨 JavaScript – Core Language
Used on both frontend and backend for logic, validation, API calls, and component interactions.

🟩 Node.js – Backend Runtime
Runs the server, handles API logic, processes requests, and communicates with MongoDB.

🟧 Express.js – API Framework
Used to create REST API endpoints for users, packages, bookings, ratings, and admin operations.

🟪 MongoDB – Database
Stores users, packages, bookings, ratings, history, and admin data in a scalable document format.

🟫 Mongoose – ODM
Defines schema, models, and provides a structured way to interact with the MongoDB database.


# Screenshots
![HomePage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/504bb803-217d-402a-9087-fed08986d6b1)
![BookPackagePage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/9733432f-e462-4eff-819e-66cba510c8b6)

# Admin Panel
![Screenshot (23)](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/8b4409ab-d8a5-4fd8-bc3d-987667fba72c)
![AddPackageAdminPage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/79c05dd8-45f8-477d-801d-6d1432e042fe)
![AllPaymentsAdminPage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/de0963bf-3f1b-47c4-ab0f-bbae33371150)

# .ENV
MONGO_URL=your_mongo_url<br/>
JWT_SECRET=secret<br/>
BRAINTREE_MERCHANT_ID=your_braintree_id<br/>
BRAINTREE_PUBLIC_KEY=your_braintree_public_key<br/>
BRAINTREE_PRIVATE_KEY=your_braintree_private_key<br/>
NODE_ENV_CUSTOM=devolopment/production<br/>
SERVER_URL=your_server_url

NearbyNest 🌍
NearbyNest is a full-featured, location-based discovery platform that empowers users to explore popular spots around them with ease. Built with the robust MERN stack (MongoDB, Express.js, React, Node.js), NearbyNest leverages real-time data from APIs such as Google Places to provide accurate and comprehensive details on nearby cafes, salons, restaurants, amusement parks, and more. With an interactive and user-friendly interface, NearbyNest makes local exploration simple, visual, and enjoyable.

🌟 Key Features
Location-Based Search: Quickly find places based on categories like cafes, salons, restaurants, and amusement parks within a radius you specify.
Interactive Map with Markers: Visualize all results on an interactive map with custom markers for each location. Click on markers for more details.
Detailed Place Information: View essential details for each place, including its name, rating, address, type, and distance from your location.
Customizable Radius: Set a specific search radius to narrow or expand your search area, perfect for finding nearby spots or planning farther explorations.
Responsive Design: Fully optimized for both desktop and mobile devices to provide a seamless experience.
🛠 Tech Stack
Frontend:
React: For building a responsive, interactive UI.
Tailwind CSS: For styling with modern, responsive, and utility-first CSS.
Backend:
Node.js & Express.js: For handling server logic and API routes.
Database:
MongoDB: NoSQL database for storing location data and user preferences.
APIs:
Google Places API: For fetching real-time location data like cafes, restaurants, and more. (Note: Replace with your preferred location-based API if needed.)
Other Tools:
Mongoose: For object data modeling in MongoDB.
Axios: For making HTTP requests to the API.
🚀 Getting Started
Follow these instructions to set up a local version of NearbyNest and explore places around you:

Prerequisites
Node.js (v12 or above recommended)
MongoDB
API Key from Google Places API or an equivalent location-based service.
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/NearbyNest.git
cd NearbyNest
Install Server Dependencies:

bash
Copy code
cd server
npm install
Install Client Dependencies:

bash
Copy code
cd ../client
npm install
Configure Environment Variables:

In the server folder, create a .env file and add your MongoDB connection string and API key:

plaintext
Copy code
PORT=5000
MONGODB_URI=your_mongodb_connection_string
GOOGLE_API_KEY=your_google_api_key
Start the Development Servers:

Backend: In one terminal, start the server:

bash
Copy code
cd server
npm start
Frontend: In a separate terminal, start the React client:

bash
Copy code
cd client
npm start
Access the Application:

Open your browser and go to http://localhost:3000 to view NearbyNest.

🔍 API Integration
NearbyNest integrates with the Google Places API to fetch live location data for cafes, restaurants, and more. To use the API:

Obtain an API key from Google Places API and enable the required services.
Add your API key to the .env file in the server folder.
With the API key, NearbyNest fetches details on various locations within the specified radius, including information like names, types, addresses, ratings, and geolocation coordinates.

🤝 Contributing
We welcome contributions! To contribute:

Fork the project.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.

# Amazon Prime Video Clone with React and Firebase
This is a clone of the Amazon Prime Video streaming service, created using React for the frontend and Firebase for the backend. The app allows users to browse and search for movies and TV shows, add them to their watchlist, and rate and review them. Admin users can add and delete movies and TV shows, manage user accounts, and reviews.

## Features
* User authentication with Firebase Authentication.
* User can browse and search for movies and TV shows.
* User can add movies and TV shows to their watchlist.
* User can rate and review movies and TV shows.
* Admin can add and delete movies and TV shows.
* Admin can manage user accounts and reviews.

## Installation
1. Clone the repository.
```
git clone https://github.com/your_username/amazon-prime-video-clone-firebase.git
```
2. Install dependencies.
```
cd amazon-prime-video-clone-firebase
```
```
npm install
```
3. Create a Firebase project and enable Firebase Authentication and Firestore.

4. Add your Firebase configuration to a .env file in the root directory.
```
REACT_APP_API_KEY=<your_firebase_api_key>
REACT_APP_AUTH_DOMAIN=<your_firebase_auth_domain>
REACT_APP_DATABASE_URL=<your_firebase_database_url>
REACT_APP_PROJECT_ID=<your_firebase_project_id>
REACT_APP_STORAGE_BUCKET=<your_firebase_storage_bucket>
REACT_APP_MESSAGING_SENDER_ID=<your_firebase_messaging_sender_id>
REACT_APP_APP_ID=<your_firebase_app_id>
REACT_APP_MEASUREMENT_ID=<your_firebase_measurement_id>
Create a Firestore collection called movies and populate it with movies.
```
5. Start the development server.
```
npm start
```
```
Open the app in your browser at http://localhost:3000.
```

## Screenshots
1. Home Page

2. Movie Details

3. User Profile

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
MIT



# Mobile Movie App

This is a mobile app developed with React Native that allows you to discover the latest movie releases, view their details, and save your favorite movies for later.

## Main Features

- **Movie recommendations**: The app displays a list of the latest movies and a selection of trending movies, allowing users to discover new titles.
- **Movie search**: Users can search for movies by title and view the results in real-time.
- **Movie details**: By selecting a movie, users can access a detailed view with information about the plot, cast, user ratings, and more.

## Technologies Used

- React Native
- Expo
- NativeWind
- Appwrite
- The Movie Database (TMDb) API

## Getting Started

To run the app locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/mobile-movie-app.git
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root of the project and add the following variables:

   ```
   EXPO_PUBLIC_MOVIE_API_KEY=your_tmdb_api_key
   EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
   EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_appwrite_database_id
   EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

4. **Run the app**:

   ```bash
   npm start
   ```

   This will open the Expo development tools in your browser. You can then run the app on an Android or iOS simulator, or on a physical device using the Expo Go app.

## Contributing

Contributions are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

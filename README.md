# Pelis Ranking

Pelis Ranking is a web application that allows users to explore and rate movies using the TMDB API. The app is built with React + Vite, uses Appwrite for user management and database, and Tailwind CSS for styling.

## Technologies Used
- **React + Vite**: Framework and bundler for a fast and modern application.
- **Appwrite**: Backend as a service for authentication and database management.
- **Tailwind CSS**: CSS framework for fast and efficient styling.
- **TMDB API**: Movie and series data provider.

## Features
- Search and explore movies using the TMDB API.
- Register and log in with Appwrite.
- Rate and save favorite movies.
- Responsive and modern UI with Tailwind CSS.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/marcospiv/Pelis-Ranking.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Pelis-Ranking
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the project root and add:
     ```env
     VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
     VITE_APPWRITE_DATABASE_ID=our_appwrite_database_id
     VITE_APPWRITE_PROJECT_ID=your_project_id
     VITE_TMDB_API_KEY=your_tmdb_api_key
     ```
5. Run the project:
   ```bash
   npm run dev
   ```

## Usage
- Browse popular movies and search by title.

## Contribution
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b new-feature
   ```
3. Make changes and commit them:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push the changes to the remote repository:
   ```bash
   git push origin new-feature
   ```
5. Create a Pull Request on GitHub.


# Bumbo Application

This is a Bumbo streaming project built by **John Oloche Okpe** and **Ademide Adeboye**. The application allows users to view movie listings, play trailers, and explore genres, among other features similar to the original Netflix platform. The project uses modern technologies for both frontend and backend development.

## Table of Contents

- [Technologies Used](HTML, CSS, HEROKU AND DJANGO)
- [Features](#User authentication and validation, search algorithm, database implementation)
- [Installation](#Underway)
- [Usage](#An online streaming application for videos)
- [Deployment](#this project has not been deployed to the web yet, though preparation is in progress)
- [Contributors](JOHN OLOCHE OKPE: FRONTEND AND AYOMIDE ADEBOYE ADEBOYE: BACKEND)

## Technologies Used

### Frontend:
- **HTML5**(Charset UTF-8)
- **CSS3** (CSS for styling)

### Backend:
- **Django** (Python web framework)

### Database:
- **Heroku** (Database deployment and hosting)

## Features

- **User Interface**: A clean and responsive UI inspired by Netflix, designed using CSS.
- **Movie Listings**: Users can view movies categorized by genre, popularity, and other criteria.
- **Video Playback**: Users can play trailers directly from the interface.
- **Search Functionality**: Search bar to filter through available movies and shows.
- **Dynamic Content**: The application dynamically updates content using Django with Ajax calls to handle backend communication.

## Installation

### Prerequisites

- Python 3.x
- Django 3.x or higher
- Node.js (for Tailwind CSS setup)
- Heroku CLI (for deployment)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/admdmd/Netflix_clone
    cd netflix-clone
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Install Tailwind CSS (if needed):
    ```bash
    npm install
    npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
    ```

5. Run the Django development server:
    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

6. Open your browser and go to `http://127.0.0.1:8000` to view the application.

## Usage

- Visit the home page to browse through movie listings.
- Use the search bar to find specific titles or genres.
- Click on a movie or show to view more details and play the trailer.

## Deployment
this section is commented for reasons associated with deployment delay.
<!-- The project is deployed on **Heroku** for hosting and database management. To deploy your own version on Heroku, follow these steps:

1. Log in to Heroku:
    ```bash
    heroku login
    ```

2. Create a Heroku app:
    ```bash
    heroku create netflix-clone-app
    ```

3. Set up Heroku PostgreSQL or any other database:
    ```bash
    heroku addons:create heroku-postgresql:hobby-dev
    ```

4. Deploy the app:
    ```bash
    git push heroku main
    ```

5. Open the app in your browser:
    ```bash
    heroku open
    ``` -->

## Contributors

- [John Oloche Okpe](https://github.com/reign001)
- [Ademide Adeboye](https://github.com/admdmd)



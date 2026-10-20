# Movie Recommendation System

## Overview
This project is a movie recommendation application that suggests similar movies based on a movie selected by the user. It uses precomputed similarity scores and movie metadata to provide relevant recommendations in a simple Streamlit interface.

## How It Works
- Loads movie data and similarity scores from saved files.
- Finds the selected movie and calculates the most similar titles using similarity rankings.
- Displays the top recommended movies along with their posters from the TMDB API.

## Technologies Used
- Python
- Streamlit
- Pandas
- NumPy
- Requests
- Pickle
- TMDB API

## Installation & Usage
1. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```

## Demo
[Live Demo](YOUR_DEPLOYED_APP_URL) - Coming soon

## Author
**Niraj Kumar Pal**

- GitHub: https://github.com/nirajkumarpal
- LinkedIn: https://www.linkedin.com/in/niraj-pal-245196314/
- Email: nirajkumarpal468@gmail.com

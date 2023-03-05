# Spotify_Dashboard
Dashboard of top tracks on Spotify in India

This project analyzes the top tracks and artists from the India Top 50 playlist on Spotify. It includes data acquisition through Spotify's API, data cleaning and transformation in a Jupyter Notebook, and visualization using Tableau. The resulting dashboard can be accessed on [Tableau Public](https://public.tableau.com/views/Spotify_Top_Tracks/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).

## Repository Structure
The following is the structure of the repository:

- Dataset: Contains the CSV files of the data acquired through Spotify's API for the India Top 50 playlist.
- Spotify_api.ipynb: A Jupyter Notebook containing the code for the API call.
- to_sql.ipynb: A Jupyter Notebook containing the code to upload the CSV files to a MySQL database.
- Dashboard: Contains the Tableau Dashboard files.

## Usage
To acquire the data from Spotify's API, run the Spotify_api.ipynb notebook. This will create CSV files of the data in the Dataset folder.
To upload the CSV files to a MySQL database, run the to_sql.ipynb notebook.
To access the Tableau Dashboard, open the .twb file in the Dashboard folder. Alternatively, the dashboard can be accessed on Tableau Public.

## Credits
This project was created by [Ankur Singh](https://www.linkedin.com/in/ankur-singh-83929818b/). The data was acquired from Spotify.


# GameTracker

## Overview
Game Tracker is a web application designed to help users keep track of their gaming progress. It fetches game data from a publicly hosted Google Spreadsheet and displays it in an intuitive, Anilist-like UI. Users can search for games, filter by platform and status, and view game details, including achievements and progress.

## Features
- **Game List Display**: Shows a grid of games with thumbnails, platforms, achievements, and status.
- **Search Functionality**: Users can search for games by name.
- **Filter by Platform and Status**: Allows filtering based on platform and game completion status.
- **Dynamic UI**: Animated elements with hover effects for an engaging experience.
- **Responsive Design**: Works on desktop and mobile devices.
- **Live Data Fetching**: Retrieves game data from a Google Spreadsheet in real time.
  
![image](https://github.com/user-attachments/assets/4afac5bf-0a76-43ed-86c2-66a7b281a6e3)

## Technologies Used
- **HTML, CSS, JavaScript**: Core web technologies for the front end.
- **Google Sheets API**: Used as a backend database to store game data.
- **CSS Animations & Flex/Grid**: Provides a modern and smooth user interface.

## Setup & Usage
### Prerequisites
Ensure you have an internet connection since the website fetches live data from Google Sheets.

### Running the Website
1. Open `index.html` in any modern web browser.
2. The page will automatically fetch and display game data.
3. Use the search bar or filters to refine the game list.

### Updating Game Data
1. Open the linked Google Spreadsheet.
2. Modify or add new game entries (name, platform, achievements, status, and thumbnail URL).
3. Changes will automatically reflect on the website upon refresh.

## Troubleshooting
- **Games not loading?** Check if the spreadsheet is publicly accessible.
- **Broken images?** Ensure the image URLs in the spreadsheet are correct and publicly available.
- **Filters not working?** Verify the platform/status values in the spreadsheet match expected formats.

## Future Improvements
- Add a login system to personalize user game tracking.
- Implement user ratings and reviews for each game.
- Enhance the UI with additional animations and themes.

## License
This project is open-source and can be modified for personal use.


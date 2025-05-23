## GitHub Security Repository Viewer

A simple web application to view and filter popular GitHub repositories related to security.

### Features

- Displays repositories tagged with 'security', sorted by stars.
- Allows filtering by additional security topics (e.g., OSINT, Webhacking).
- Dark mode support with local storage persistence.
- Styling inspired by GitHub's UI.

### File Structure

- `index.html`: Contains the main HTML structure and JavaScript logic for:
    - Fetching data from the GitHub API (`search/repositories` endpoint).
    - Dynamically rendering the list of repositories.
    - Handling user input for topic filtering.
    - Toggling dark mode and saving user preference.
- `style.css`: Contains all CSS rules for styling the application, including light and dark themes, and GitHub-inspired visual elements.

### How to Run

1. Clone this repository (or download the files).
2. Open `index.html` in your web browser.

No special build steps or dependencies are required.

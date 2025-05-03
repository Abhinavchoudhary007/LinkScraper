# Django Webscrapper

## Project Description
This Django webscrapper project allows users to input a URL, then scrapes all the links (anchor tags) from the specified webpage. The scraped links, including their URLs and link text, are stored in a database and displayed in a user-friendly table. Users can also clear the stored links with a single click.

## Features
- Input any URL to scrape all links from the webpage.
- Display scraped links with their names and URLs.
- Clear all stored links with a delete button.
- Simple and clean user interface using Bootstrap.

## Installation and Setup
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd webscrapper
   ```
3. Create and activate a virtual environment (optional but recommended):
   ```
   python -m venv venv
   venv\Scripts\activate   # On Windows
   source venv/bin/activate  # On macOS/Linux
   ```
4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is not present, install Django, requests, and beautifulsoup4 manually:)*  
   ```
   pip install django requests beautifulsoup4
   ```
5. Apply migrations:
   ```
   python manage.py migrate
   ```
6. Run the development server:
   ```
   python manage.py runserver
   ```

## Usage
- Open your browser and go to `http://127.0.0.1:8000/`.
- Enter the URL of the website you want to scrape links from.
- Click the "Submit" button to start scraping.
- The scraped links will be displayed in a table below.
- To clear all stored links, click the "Delete" button.

## Technologies Used
- Django (Python web framework)
- Requests (HTTP library for Python)
- BeautifulSoup4 (HTML parsing library)
- Bootstrap 4 (CSS framework for styling)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

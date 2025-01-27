Properties_617

This project is a web application that allows users to search for rental properties across multiple platforms (OpenRent and RightMove) based on their location, price range, and number of rooms. The application fetches property listings, stores them in a database, and displays them on a results page. Users can also choose to receive the results via email in CSV format.

Features
Property Search: Search for rental properties from OpenRent and RightMove based on location, price range, and number of rooms.
Filters: Apply filters for location, price, number of rooms, and radius from postcode.
Results Display: View the fetched properties directly on the web interface.
Email Results: Receive property search results via email in a CSV file.
Concurrent Fetching: Fetch property listings from both OpenRent and RightMove concurrently using Python’s ThreadPoolExecutor.
SQLite Database: Store property listings in an SQLite database for easy management and display.

Tech Stack
Backend: Flask, Python
Frontend: HTML, CSS, JavaScript
Database: SQLite with SQLAlchemy
Data Handeling: Pandas
Web Scraping: Selenium, BeautifulSoup
Email Sending: SMTP, MIME
Forms: WTForms with Flask-Bootstrap for front-end UI

Requirements
Python 3.7+
Dependencies:
Flask
Flask-SQLAlchemy
Flask-WTF
Flask-Bootstrap
Selenium
BeautifulSoup4
Pandas
Email validator
(Install using pip install -r requirements.txt)

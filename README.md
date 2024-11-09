Flight Scraper

This project is a simple web scraping script that searches for flights between two cities on a specified date and returns basic information about the flights.

Project Description

The script searches for flights from a specified start city (A) to a destination city (B) on a given day (D) using the United Airlines website. It provides a list of 2-3 flight results, including flight time, cost, and other relevant details.

Features

	•	Flight Time - The departure and arrival time of the flight.
	•	Flight Cost - The cost of the flight in the given currency.
	•	Other Fields - Additional flight details (e.g., duration, airline, layovers).

Technologies Used

	•	Playwright/Puppeteer - For navigating and interacting with the United Airlines website.
	•	Requests - For handling additional HTTP requests, if needed.

Installation

	1.	Clone the repository:

git clone https://github.com/yourusername/flight-scraper-test.git
cd flight-scraper-test


	2.	Install dependencies:

pip install -r requirements.txt

Note: Make sure you have Python installed.

Usage

	1.	Run the script:

python flight_scraper.py


	2.	Input Parameters:
	•	Start City: e.g., London (LON)
	•	Destination City: e.g., Chicago (ORD)
	•	Date: e.g., 22-10-2022
	3.	Output: The script returns a JSON list with flight details:

[
   {
      "flight_time": "14:30 - 18:45",
      "flight_cost": "$450",
      "duration": "10h 15m",
      "airline": "United Airlines"
   },
   ...
]



Future Improvements

	•	Add error handling for cases where flights are unavailable.
	•	Enhance search to include different classes (e.g., Economy, Business).
	•	Implement caching for frequently searched routes.

License

This project is licensed under the MIT License.

This README provides clear instructions and context, making it easy for others to understand and run the project.
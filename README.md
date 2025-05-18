💼 Job Scraper using Apify API
This Python script uses the Apify API to scrape job listings based on a specified job position, country, and location. The extracted job data is saved into a CSV file and optionally printed to the console.

📌 Features
Connects to the Apify platform using the official apify-client Python SDK.

Uses the "Job Scraper" Actor to scrape job listings.

Allows customizable input like:

Job Position (e.g., Web Developer)

Country (e.g., US)

Location (e.g., San Francisco)

Number of job listings to fetch

Saves the job data to output.csv.

Supports printing results directly to the console.

📁 Project Structure

.
├── job_scraper.py           # Python script to run the Apify job scraper
├── output.csv               # Output file with scraped job listings
└── README.md                # Project documentation
🧰 Requirements
Install dependencies with pip:

pip install apify-client
🔧 Setup
Create a free account on Apify.

Obtain your API token from your Apify account settings.

Replace the token in the script:


client = ApifyClient("YOUR_APIFY_API_TOKEN")
Optionally customize:

position

country

location

maxItems

🚀 How to Run

python job_scraper.py
This will run the Apify job scraper Actor and save the results in output.csv.

The script also prints the job listings to the terminal.

📄 Sample Output (CSV Columns)
title

location

company

url

postedDate

description (if available)

⚠️ Notes
Make sure your API usage does not exceed your plan limits on Apify.

The Actor used (hMvNSpz3JnHgl5jkh) must be public or accessible with your token.

🧑‍💻 Author
Jesika
3rd Year CSE Student


📃 License
This project is licensed under the MIT License. See the LICENSE file for details.

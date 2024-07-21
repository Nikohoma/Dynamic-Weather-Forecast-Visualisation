### Dynamic Weather Forecast Visualization

**Project Overview:**
The Dynamic Weather Forecast Visualization project involves using Python to fetch weather forecast data for New Delhi for the next 14 days via a REST API and displaying this data dynamically in Power BI. The project showcases the integration of Python scripting, API data retrieval, and interactive visualization tools to create an automated and up-to-date weather dashboard.

**Data Acquisition:**
The weather data was obtained from weatherapi.com using a free 14-day trial API. The steps involved in data acquisition included:

- **API Integration:** Utilized Python's requests library to interact with the weather API, fetching forecast data for New Delhi.
- **Parameter Selection:** Focused on key weather parameters such as temperature and weather conditions. The API provided additional parameters like wind directions, moon conditions, etc., which can be included as needed.

**Data Processing:**
Once the data was retrieved from the API, it underwent several processing steps:

- **Data Parsing:** Extracted relevant information from the JSON response provided by the API.
- **Data Formatting:** Structured the data into a tabular format suitable for visualization, including fields like date, temperature, and weather conditions.
- **CSV Export:** Saved the processed data into a CSV file hosted on Google Drive for easy access and integration with Power BI.

**Automation:**
To ensure the weather data remains current, the Python script was automated:

- **Scheduled Runs:** The Python script was set to run at regular intervals (e.g., daily) using task scheduling tools like cron (Linux) or Task Scheduler (Windows).
- **CSV Update:** Each run of the script updates the CSV file with the latest forecast data, ensuring the visualizations in Power BI reflect the most recent information.

**Visualization in Power BI:**
Power BI was utilized to create an interactive and dynamic weather dashboard:

- **Data Import:** Connected Power BI to the CSV file on Google Drive, enabling seamless data import and refresh.
- **Dynamic Charts:** Created charts to display temperature trends and weather conditions over the 14-day forecast period.
- **Interactivity:** Added interactive features such as filters and slicers to allow users to explore different aspects of the weather data.

**Key Features:**
- **Real-Time Updates:** The integration with the weather API and automated data refresh ensures that the dashboard always displays the most current forecast.
- **Customization:** Users can customize the parameters displayed in the dashboard, selecting from a range of available weather data points.
- **Accessibility:** Hosting the CSV file on Google Drive and using Power BI ensures the dashboard is accessible from multiple devices and can be shared with a wide audience.

**Conclusion:**
The Dynamic Weather Forecast Visualization project effectively demonstrates the power of combining Python, REST APIs, and Power BI to create a real-time, interactive dashboard. This solution not only provides up-to-date weather information for New Delhi but also showcases the potential for expanding to include additional parameters and locations. By leveraging automation and dynamic visualization tools, this project delivers valuable insights in a user-friendly format.

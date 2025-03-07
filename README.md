# Google Video Search Automation using UiPath

## Description
This project automates the process of searching for a specific topic on Google and extracting the top 10 video links available on that topic using UiPath. The robot performs a Google search, extracts the relevant video links from the search results, and stores them in a structured format for further use.

## Requirements
- UiPath Studio (with appropriate version installed)
- UiPath Robot
- Internet Connection
- Google Search (accessible through a browser)
- Google Chrome or Edge browser extension for UiPath Web Automation (required for automation in web browsers)

## Features
- Automatically performs a Google search for a specified topic.
- Extracts the top 10 video links from the search results.
- Stores the video links in a structured format (e.g., CSV, Excel, or a list).
- Provides an easy-to-use solution for web scraping and data extraction using UiPath.

## How It Works
1. **Search Execution:**
   - The robot starts by opening a browser (Chrome/Edge) and navigating to Google.
   - It enters the search term into the Google search bar and triggers the search.
   
2. **Extracting Video Links:**
   - After loading the search results, the robot identifies video links from the search results.
   - The robot extracts the URLs of the top 10 video results.
   
3. **Storing Data:**
   - The extracted video URLs are stored in a CSV or Excel file, depending on the configuration.

4. **Error Handling:**
   - Basic error handling is incorporated in case the search doesn’t return results or any other issue arises during the process.

## Setup Instructions
1. **Install UiPath Studio:**
   - Download and install UiPath Studio from [UiPath Official Website](https://www.uipath.com/start-trial).
   - Ensure that you have the necessary version of UiPath installed.

2. **Install UiPath Web Automation Extension:**
   - Open UiPath Studio and go to "Manage Packages."
   - Search for the **UiPath.WebAPI.Activities** or **UiPath.UIAutomation.Activities** and install them.
   - Also, install the **UiPath Chrome/Edge extension** by navigating to the browser extension store and enabling the automation features.

3. **Clone the Repository (if applicable):**
   - If this project is stored in a GitHub repository, clone the repository to your local machine using Git.
   - Open the project folder in UiPath Studio.

4. **Configure the Topic Search:**
   - Update the variable in the workflow for the topic you want to search for (e.g., `searchTopic = "Artificial Intelligence"`).
   - Make sure the UiPath robot has access to the browser and can control it properly.

5. **Run the Project:**
   - Open UiPath Studio and click "Run" to start the automation.
   - The robot will start searching on Google and extract the top 10 video links.

## Output
The output of the automation will be saved in a CSV or Excel file with the following structure:
- **Video Link 1**
- **Video Link 2**
- ...
- **Video Link 10**

You can open the file to view and analyze the extracted video links.


## Troubleshooting
- **No Results Extracted:** Ensure that the UiPath browser extension is installed and the robot has access to the browser.
- **Timeout Errors:** Check your internet connection. The robot might fail to perform the search if the connection is slow.
- **No Video Results:** Google might have changed its page layout. Check if the robot is correctly identifying the search result links.

## Contributing
Feel free to fork this repository, raise issues, and contribute with enhancements or bug fixes. Make sure to test the functionality and ensure the automation works as expected after modifications.


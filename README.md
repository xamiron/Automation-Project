# Project Summary: Bdjobs Automation Project
This project is an automation script designed to interact with the job portal "Bdjobs.com Ltd" using Selenium WebDriver. The primary objective of this automation script is to automate the process of logging into the website, searching for jobs, and performing various interactions such as shortlisting jobs, applying for them, and undoing applications. The script is written in Java and leverages the Selenium WebDriver for browser automation and WebDriverManager for managing browser driver binaries.

Check Lis: https://docs.google.com/spreadsheets/d/1XnaxHyw21hx2cRP04HF5UtQSjfNCTebr0B2Ify_YH5E/edit?gid=1389889247#gid=1389889247
# Project Features:
# 1. Automated Login:
- The script navigates to the Bdjobs website and automates the login process by entering the username and password.
  
# 2. Job Search Automation:
- After logging in, the script performs a job search based on a specified keyword ("SQA" in this case).
- The script waits for the search results to load and opens the job listings.

# 3. Window Handling:
- The script handles multiple browser windows and tabs, switching between them as needed to interact with different elements on the page.

# 3. Job Interaction:
- Shortlisting Jobs: The script automates the process of shortlisting a job.
- Removing from Shortlist: It also includes functionality to remove a job from the shortlist.
  
# 4. Job Details Navigation:
- The script navigates through different sections of a job listing, including Requirements, Responsibilities, Salary & Benefits, and Company Information.
  
# 5. Application Process:
- The script automates the process of applying for a job, including entering expected salary details.
- It performs input validation by trying different invalid salary inputs (e.g., "@#$%^&*", "tgrig", "y010abc") and finally submitting a valid salary input ("5000").
  
# 6. Undo Application:
- The script includes functionality to undo a job application, demonstrating its capability to revert actions.

# 7. Error Handling:
- The script includes basic exception handling to capture and print any errors encountered during execution.

This project automates tasks on Bdjobs.com, such as logging in, searching for jobs, and applying. It handles job shortlisting, navigates job details, and validates salary inputs during applications. The script also includes undo functionality and basic error handling.

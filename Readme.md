# YouTube Watch History Analysis

This notebook presents an in-depth project analysis of my Personal YouTube Watch history, using Python to extract insights from the data. The analysis aims to uncover patterns in viewing habits, identify peak hours and days of video consumption and analyzing the types of content I engage with most frequently.

**Goal:** Use Python to gain insights into your YouTube viewing habits.

## Source of Data

The data used was obtained from Google Takeout. To download your YouTube Watch History, follow this steps:

1. Go to [Google Takeout](https://takeout.google.com/) using your browser and sign in with the Google Account associated with your YouTube Activity.
2. To only download YouTube data, click "Deselect all". Scroll down and click the check the box for YouTube and YouTube Music. Click the "All YouTube data included" button. In the pop-up, uncheck everything except "History" to focus on your watch history.
3. Choose Download options. Scroll to the bottom and click "Next Step".Select "Send the download link via email" for delivery. Choose "Export once" for frequency.
   Pick ".zip" as the file type and a size limit (2GB is plenty for watch history).
4. Export Data: Click "Create export" to initiate the process. Google will prepare the export, which might take some time depending on the amount of data.
   Once ready, you’ll receive a link via email to download the file.
5. Download Your Data: Open the email from Google and click on the link to download your YouTube watch history.
   Unzip the file and look for a file like `watch-history.html`.

> **NB:** Ensure that the `watch-history.html` is in the same directory as the Python scripts you might use later to analyze it.

## Challenges

**Data Quality and Completeness**

- Missing or Inaccurate Data: YouTube's data collection methods may not always be perfect, leading to missing or inaccurate values.
- Watch History Limitations: Factors like device changes, account deletions, or several accounts can affect the completeness of watch history data.

## In Progress

- [ ] Create a Script that analyses the YouTube Watch History.

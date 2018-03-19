# Lab 2
## The Idea
Create an application that allows the user to read content from any RSS feed. The app will consist of 3 activities: one with the list of items (ListView, for selecting content), one for article content display (for reading content), and User Preferences (for user to specify the preferences).
## The solution
To solve these issues, the Colorlab want a new, responsive system that works on all devices and is easy and fast to use to ensure that everyone uses it. They are going to put tablets outside (and inside) the labs so that you can easily log your usage even if you haven't booked it prior. The system needs to contain different roles so that they can log what equipment or rooms different roles use the most. They want it to be flexible for administrators to add new equipment and rooms if necessary.

## Preferences
The user should be able to specify in the preferences the URL to the RSS feed (RSS2.0-based or Atom-based), and, the limiting number of items that should be displayed in the ListView (10, 20, 50, 100), and the frequency at which the app fetches the content (10min, 60min, once a day). The app will fetch the RSS feed and populate the list UP to the limit number. When user clicks on a particular item, a detailed view should be shown, with the content of the article for that item.

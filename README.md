# CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS
"COMAPANY":CODTECT IT SOLUTIONS

"NAME":NAKKALAKONA NANDINI

"INTERN ID":CT06DF404

"DOMAIN":FULL STACK DEVELOPMENT

"MENTOR":NEELA SANTOSH

DESCRIPTION OF THE TASK:
 Chrome Extension for Time Tracking and Productivity Analytics — Description
The Time Tracking and Productivity Analytics Chrome Extension is a lightweight browser tool designed to help users monitor and analyze how they spend time on different websites. This extension enables individuals to gain insights into their browsing habits, differentiate between productive and unproductive activities, and make informed decisions to improve their online efficiency.

⚙️ Core Functionality
The extension works by tracking the amount of time a user spends on various websites during their browsing session. When the user switches between tabs or navigates to a new URL, the extension captures these events and records the time spent on the previous site. This data is stored locally using Chrome’s storage.local API, ensuring that it persists even when the browser is closed and reopened.

The extension categorizes websites into productive and unproductive types. For example:

Productive: coding platforms like leetcode.com, github.com, or stackoverflow.com

Unproductive: social media platforms like facebook.com, instagram.com, or youtube.com

Each site’s time data is stored along with its classification, enabling the user to view summaries of their productive vs. unproductive browsing time.

🛠 How It Works
The extension is powered by three main components:
1️⃣ manifest.json — This configuration file defines the extension’s metadata, permissions (such as access to tabs and storage), and specifies background scripts and popup files.

2️⃣ background.js — This is the core logic of the extension. It listens for browser events (like tab switches or URL updates) and keeps track of the active website and time spent. It saves this data in Chrome’s local storage and ensures that updates are broadcast whenever the user changes sites.

3️⃣ popup.html + embedded script — This component provides a simple dashboard. When the user clicks the extension icon, a popup displays a table showing time spent (in minutes) on each site, along with its category (productive or unproductive). The popup pulls this data from local storage and dynamically generates the report.

📊 Productivity Analytics
The extension summarizes usage in an easy-to-read table:

Site name

Time spent (in minutes)

Category (productive/unproductive)

This helps users identify patterns in their online behavior — for instance, whether too much time is being spent on social media or whether coding and learning platforms are getting sufficient attention. Over time, this data can help users build better browsing habits and enhance their productivity.

🌟 Extensibility
While the current version of the extension provides local time tracking and basic analytics, it can easily be enhanced with:
✅ A backend server (e.g., Node.js + MongoDB) for storing and analyzing data across devices
✅ Visual charts and graphs for a more interactive dashboard
✅ Weekly summary reports or reminders
✅ User-configurable site categories
✅ Auto-reset of data at the start of each week
OUTPUT:

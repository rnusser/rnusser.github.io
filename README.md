# **2026 Interactive Calendar**

A Linux-style, terminal-inspired collaborative calendar designed for real-time scheduling and coordination.

## **🚀 Live Demo**

You can access your live calendar here:

[**View Live Calendar**](https://your-username.github.io/your-repo-name/)

## **✨ Features**

* **Real-Time Collaboration**: Powered by cloud storage, updates appear instantly for all users connected to the same session.  
* **Advanced Selection**:  
  * **Drag-to-Select**: Click and drag to highlight date ranges.  
  * **Shift-Selection**: Hold Shift to pick multiple non-consecutive dates, then release Shift to tag them all at once.  
* **Identity Tracking**: Each entry is prefixed with the user's initials (e.g., \[JD\] Project Deadline) so you know who scheduled what.  
* **Personal View Filter**: Toggle the **"My Entries Only"** button to declutter the view and focus solely on your own tasks.  
* **Visual Categorization**: Assign custom colors to different event types for a quick overview of the month.

## **🛠 Usage Instructions**

1. **Tagging a Date**: Click and drag over any dates in a month. A popup will appear allowing you to enter your initials, a description, and a color.  
2. **Multi-Range Selection**: Hold down the Shift key while clicking or dragging across different dates. Once you have selected all desired ranges, release Shift to open the tagging modal.  
3. **Sharing**: Use the **"Share Link"** button to copy the URL to your clipboard. Anyone with this link can collaborate on this specific calendar.

## **💻 Tech Stack**

* **Frontend**: Vanilla JavaScript, HTML5, CSS3 (Modern Mono-space Aesthetic).  
* **Backend/Persistence**: Firebase Firestore for real-time data syncing.  
* **Authentication**: Anonymous Auth to ensure unique user identification without requiring a login.  
* **Hosting**: Optimized for GitHub Pages.

## **📝 Setup for Local Development**

1. Clone this repository.  
2. Open index.html in any modern web browser.  
3. To point to your own database, update the firebaseConfig object within the \<script\> tag in index.html.

*Created as a collaborative scheduling tool for 2026\.*



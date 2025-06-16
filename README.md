📌 Overview:
This is a Gradio-based web application that allows schools or educational institutions to generate class and teacher timetables automatically. It uses a backend scheduling algorithm (likely implemented in a TimetableManager class) and provides an interactive frontend with real-time updates, previews, and chat support.

🔧 Tech Stack:
Python for backend logic

Gradio for web UI

HTML/CSS/JS for frontend interactivity

Optional: BERT for other sub-projects (like fake news detection)

🖥️ Core Features:
✅ 1. Timetable Generation:
Users input constraints like:

Sections & activity subjects

Start/end time

Periods per day, lunch time, Saturday options

Backend logic uses this to generate .csv timetables

✅ 2. Loading Overlay:
A full-screen spinner and message ("Generating Timetables...") appears while generation is in progress

✅ 3. Results View:
Dynamically loads generated timetables

Categorizes by classes and teachers

View buttons show timetable previews

✅ 4. Chat Assistant (Demo):
Floating chat icon

Users can type questions (e.g., “How do I generate a timetable?”)

Demo response system with simulated replies

📁 Output:
Timetables are saved as .csv files

Users can view/download them in the UI

🚦 Error Handling & Status:
Real-time status updates

Preview fallback if file not found

Handles tab switches with JavaScript integration

📌 Potential Add-ons:
Real assistant integration (e.g., GPT for Q&A)

Export to Excel/PDF

User login or save preferences

Calendar integration (Google Calendar)

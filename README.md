# Habit Tracker Calendar App

A browser-based habit tracking web application that I made for myself because I couldn't find something similar that I liked. 

Allows you to complete daily tasks and visually track consistency over time.

The calendar displays daily progress using colour intensity and a progress bar, encouraging habit streak building.

## Desktop Version

A downloadable Windows version is available here:

https://github.com/dannybirin/habit-tracker-desktop

---

## Overview

This project was built using pure HTML, CSS, and JavaScript (no frameworks).

Users can:

- Add and delete custom daily tasks
- Mark tasks as completed for specific days
- Navigate month-by-month
- Track completion streaks
- Toggle between light and dark mode
- Automatically save data using localStorage

The application visually represents daily completion levels using colour progression (white → orange → green) and a dynamic progress bar.

---

## Features

- Monthly calendar layout
- Click any day to view/edit tasks
- Real-time colour updates based on completion percentage
- Current streak and longest streak tracking
- Dark mode toggle
- Persistent data storage (localStorage)
- Fully client-side (no backend required)

---

## Technologies Used

- HTML5
- CSS3 (Custom Properties / Variables)
- Vanilla JavaScript

---

## How It Works

Each day is stored using a unique date key format:

```
YYYY-MM-DD
```

Task completion is saved as a JSON object in localStorage.

Completion ratio is calculated as:

```
completed_tasks / total_tasks
```

The UI dynamically updates:

- Background colour based on ratio
- Progress bar width
- Streak counter

---

## Project Structure

```
habit_tracker/
│
├── index.html
├── README.md
```

---

## How to Run

1. Clone the repository:

```
git clone https://github.com/dannybirin/habit_tracker.git
```

2. Open the folder

3. Double-click `index.html`

No installation required.

---

## Learning Outcomes

- DOM manipulation with JavaScript
- Event handling
- Dynamic UI updates
- Local data persistence
- Basic state management
- Responsive layout design

---

## Future Improvements

- Weekly statistics dashboard
- Export data to CSV
- Mobile layout optimisation
- Cloud sync (Firebase or backend API)

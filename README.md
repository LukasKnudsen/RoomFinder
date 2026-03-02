# RoomFinder – Android App (Kotlin)

RoomFinder is an Android application developed as part of the *Mobile App Development* course at IT University of Copenhagen.

The app helps ITU students find available study rooms, navigate the building, and view live public transportation departures near campus.

---

## Overview

Finding an available room at ITU can be difficult, as students currently need to physically check rooms or ask the front desk.  
RoomFinder provides a live-updating overview of rooms, including their booking status, and improves wayfinding inside the building.

The app consists of three main features:

- Room overview with availability filtering  
- Live metro departures (DR Byen & Islands Brygge)  
- Interactive indoor map with search functionality  

---

## Features

### Home – Room Overview
- Displays all rooms in the ITU building
- Filter by category: All, Classroom, Skybox, Auditorium
- Toggle to show only currently available rooms
- Data stored locally using Room (SQLite)

### Departures
- Integrated Rejseplanen API
- Shows live departures from:
  - DR Byen
  - Islands Brygge
- Pull-to-refresh functionality

### Map
- Integrated Google Maps API
- Displays ITU building layout
- Search functionality to locate specific rooms
- Zoom and navigation support

---

## Tech Stack

- Kotlin
- Android SDK
- MVVM Architecture
- MutableLiveData
- Room (SQLite)
- Google Maps API
- Rejseplanen API
- ConstraintLayout

---

## Data Handling

Due to limited access to ITU’s official booking system API, room booking data is simulated using a local JSON file stored in the Assets folder.

---

## My Contribution

I co-developed this application as part of a group project.

My primary contributions included:

- Implementing core UI components
- Working with Room (SQLite) for data persistence
- Contributing to architecture decisions (MVVM)
- Developing filtering logic for room availability

---

## Context

Developed as part of the Mobile App Development course at ITU.

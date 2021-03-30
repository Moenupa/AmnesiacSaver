# Amnesiac Savior: Plan Important Events with a Click.

## Team Composition

Name|Role|Responsibility
:-:|:-:|:-:|
MAN Furui | Backend | Database, Interaction
WANG Meng | Frontend | UI, Interaction

## Project Proposal

### Project Title

Amnesiac Savior: Plan Important Events with a Click.

### Motivation

Blackboard learn is considered a great web study platform, but sometimes its information is so detailed that students may miss important events. In addition, blackboard monitors flooded messages of all courses, important notification is not sufficiently emphasized for forgetful guys like one of the developers.

Thus, to prevent forgetful guys from missing their quizzes, DDLs, and other important events, we decided to develop Amnesiac Savior in aid of recording important events.

### Outline

A **web application** with which users can schedule their desired events with custom alert messages, along with a **chrome extension** is provided with which users can detects hovered selected texts and pop up a reminder for the event, for the sake of convenience. 

> 🗃 Selection Detection, Cloud Synchronization, and ListView Management

The web application supports list-view of all events, event scheduling, and cloud synchronization.

The chrome extension supports automatic parsing of selected text and several ease-access features, and prompt alert when event reminders are triggered.

### Highlights

- View and Manage all deadlines in a ListView
- Cloud database to synchronize between devices
- Automatically parse deadline to time from the selection
- Real-time pop-up modal when selecting text for easy-access

### Prefered Implementation

- Backend: Firebase and node.js
- Frontend: HTML, CSS, JavaScript, Vue.js

![Conceptual Implementation](./res/Amnesiac_Savior.png)
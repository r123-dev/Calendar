# Basic Tutor Calendar System with Google Calendar Integration

## Overview

This project is a Basic Tutor Calendar System that allows users to manage their schedules and integrates with Google Calendar. The system includes features for viewing, creating, updating, and deleting events. It demonstrates skills in handling third-party API integrations, creating intuitive user interfaces, and developing backend functionalities.

## Features

### Calendar Management

- **Calendar View**: An interactive calendar view displaying the user's schedule. Users can click on dates and time slots to view and manage appointments. Event creation can be triggered by clicking anywhere on the calendar.
  
- **Event Creation**: A form that opens in a pop-up for users to create events with the following fields:
  - Event title
  - Description
  - List of participants
  - Date (dd-mm-yyyy)
  - Time (12hr format)
  - Duration in hours
  - Session Notes

- **Validation**: The form includes validation for required fields and proper data formats.

### Google Calendar Integration

- **Google Calendar Sync**: Integrate with the Google Calendar API to sync events. Users can authorize the application to access their Google Calendar and manage events.

## Tech Stack

### Backend

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing event data.
- **Google APIs**: For Google Calendar integration.
- **dotenv**: Module to load environment variables.

### Frontend

- **React.js**: JavaScript library for building user interfaces.
- **Chakra UI**: Component library for React.js.
- **FullCalendar**: JavaScript calendar library for creating interactive calendars.

## Project Setup

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running
- Google Cloud Project with Calendar API enabled
- Google OAuth 2.0 credentials (Client ID and Client Secret)


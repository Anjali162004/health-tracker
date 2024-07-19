Here's a detailed README for your Health Challenge Tracker project:

---

# Health Challenge Tracker

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
  - [Running Tests](#running-tests)
- [Deployment](#deployment)
 
## Introduction

Health Challenge Tracker is a single-page application (SPA) built with Angular 14+ to help users track their workouts. Users can input their name, workout type, and workout minutes, and the application will display the workout list with functionalities such as search, filter, pagination, and workout progress visualization using charts.

## Features

- Add a user workout
- Display the user workout list
- Search by name
- Filter by workout type
- Pagination for more than 5 users
- Optional feature: Display workout progress using charts
- Unit tests for one component and one service with 100% code coverage

## Technologies Used

- Angular 14+
- Angular Material
- Tailwind CSS
- Chart.js
- LocalStorage for data persistence

## Getting Started

### Prerequisites

- Node.js and npm (You can download them from [nodejs.org](https://nodejs.org/))
- Angular CLI (You can install it globally using `npm install -g @angular/cli`)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Anjali162004/health-tracker
   cd health-tracker
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

### Running the Application

1. Start the development server:
   ```sh
   ng serve
   ```

2. Open your browser and navigate to `http://localhost:4200/` to see the application.

### Running Tests

1. Run the unit tests:
   ```sh
   ng test --code-coverage
   ```

2. The code coverage report will be generated in the `coverage/` directory.

## Deployment

To deploy the application, you can use any cloud service such as GitHub Pages, Netlify, or Heroku. Here’s an example of deploying to GitHub Pages:

1. Build the project:
   ```sh
   ng build --prod --base-href "https://github.com/Anjali162004/health-tracker"
   ```
 

2. Your application will be available at `https://github.com/Anjali162004/health-tracker`.
 
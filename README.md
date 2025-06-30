# Habit Tracker

A mobile-friendly web application for tracking habits, inspired by the [Teclado Web Development Bootcamp](https://github.com/tecladocode/web-dev-bootcamp) curriculum.

## Overview

This project builds on core skills in Flask and Jinja templating, and introduces:

- Flask blueprints for modular app design
- Working with dates and data storage in MongoDB
- Responsive, simple, and attractive web design

## Features

- Create, view, and track daily habits
- User-friendly interface optimized for mobile devices
- Data persistence using MongoDB
- Organized project structure using Flask blueprints

## Getting Started

### Prerequisites

- Python 3.x
- pip
- MongoDB (local or cloud, e.g. MongoDB Atlas)

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/nicoopenna/habit-tracker.git
    cd habit-tracker
    ```
2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```
3. Set up your MongoDB connection URI as an environment variable:
    ```sh
    export MONGODB_URI="your-mongodb-uri"
    ```
4. Run the application:
    ```sh
    flask run
    ```

## Usage

- Visit the running app in your browser (default: `http://127.0.0.1:5000`)
- Sign up or log in (if authentication is implemented)
- Add habits you want to track
- Mark habits as complete each day

## Technologies Used

- Python, Flask
- Jinja2 Templates
- MongoDB
- HTML, CSS (responsive/mobile-friendly design)

## Project Structure

- Modular design using Flask blueprints
- Templating with Jinja2
- Static files for CSS and assets

## Credits

- Inspired by the [Teclado Web Development Bootcamp](https://github.com/tecladocode/web-dev-bootcamp)

## License

[MIT](LICENSE) (or specify your license here)

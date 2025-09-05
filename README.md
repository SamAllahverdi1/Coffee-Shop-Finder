# ☕ Atlanta Coffee Shop Finder

### A local guide to the best coffee in Atlanta, GA

### 🚀 [**View the Live Demo**](https://coffeeshopfinder.pythonanywhere.com/) 🚀

![Python](https://img.shields.io/badge/Python-3.1%2B-blue) ![Django](https://img.shields.io/badge/Django-5.0-darkgreen.svg)

## 📖 About The Project

Welcome to the Atlanta Coffee Shop Finder! This web application was developed as a final project for the Georgia Tech **CS 2340: Objects and Design** course. Our team of four created this platform to help Atlanta locals and visitors discover and share their favorite coffee spots around the city.

The application's core feature is an interactive map that displays local coffee shops, allowing users to easily find a cafe near them. Users can also view shops in a list, save their favorites, and contribute to the community by leaving ratings and reviews.

## ✨ Features

* **🗺️ Interactive Map View:** The primary interface for discovering coffee shops across Atlanta.
* **📋 List View:** See all coffee shops in a sortable and filterable list format.
* **⭐ 5-Star Rating System:** Rate your favorite shops with precision, including half-star increments.
* **❤️ Favorites System:** Save your most-loved coffee shops to a personal list for quick access.
* **✍️ User Reviews:** Leave detailed reviews to share your experience with the community.
* **📄 About Page:** Learn more about the project and the team behind it.

## 🛠️ Built With

* [Python](https://www.python.org/)
* [Django](https://www.djangoproject.com/)
* HTML/CSS
* JavaScript

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have Python and pip installed on your machine.
* Python 3.1+
* pip

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone github.com/SamAllahverdi1/Coffee-Shop-Finder.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd your-repo
    ```

3.  **Install project dependencies:**
    This command reads the `requirements.txt` file and installs the correct version of Django.
    ```bash
    pip install django==5.0
    ```
    > **Note for macOS users:** You may need to use `pip3` instead of `pip`.

4.  **Set up the database:**
    These commands create the database schema and apply it.
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```
    > **Note for macOS users:** You may need to use `python3` instead of `python`.

6.  Open your web browser and navigate to `http://127.0.0.1:8000/` to see the application running.

## 👥 Meet the Team

If you have an questions, feel free to contact: <sallahverdi3@gatech.com>
This project was a collaborative effort by:

* **[Sam Allahverdi]** - [github.com/SamAllahverdi1](https://github.com/SamAllahverdi1)
* **[Tate Johnson]** - [github.com/tate0817](https://github.com/tate0817)
* **[Tahiyat Mahmood]** - [github.com/ThytMhmd](https://github.com/ThytMhmd)
* **[James Kemerait]** - [github.com/jkemerait3](https://github.com/jkemerait3)

## ⚖️ License

Distributed under no license.

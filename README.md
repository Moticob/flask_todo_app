# Flask To-Do List Application

A simple To-Do List web application built with Flask.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a basic To-Do List application that allows users to add, view, and delete tasks. It's a great starting point for learning Flask, a popular Python web framework.

## Features

- Add tasks to your To-Do list
- View all tasks
- Delete tasks from the list

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/flask_todo_app.git
    cd flask_todo_app
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Flask application:**

    ```bash
    python app.py
    ```

2. **Open your browser and go to:**

    ```plaintext
    http://127.0.0.1:5000
    ```

3. **Use the web interface to add, view, and delete tasks.**

## Project Structure

```plaintext
flask_todo_app/
├── app.py
├── templates/
│   ├── index.html
├── static/
│   ├── style.css
└── requirements.txt

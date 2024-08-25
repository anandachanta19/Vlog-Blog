# 📹 Vlog-Blog

[![Contributors](https://img.shields.io/github/contributors/anandachanta19/Vlog-Blog?color=blue)](https://github.com/anandachanta19/Vlog-Blog/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/anandachanta19/Vlog-Blog?style=social)](https://github.com/anandachanta19/Vlog-Blog/network/members)
[![Issues](https://img.shields.io/github/issues/anandachanta19/Vlog-Blog)](https://github.com/anandachanta19/Vlog-Blog/issues)
[![License](https://img.shields.io/github/license/anandachanta19/Vlog-Blog)](https://github.com/anandachanta19/Vlog-Blog/blob/main/LICENSE)

## 🌐 Live Demo

Check out the live version here: [Vlog-Blog Website](https://vlog-blog.onrender.com/)

The Website takes 1 minute to get loaded as I don't have the premium subscription

## 🚀 Project Overview

**Vlog-Blog** is a full-stack web application that allows users to create and manage blogs and vlogs. With a user-friendly interface and seamless integration between blog and video content(currently the platform supportsonly blogs) the platform is built using Python, Flask, Bootstrap, and PostgreSQL.

![Screenshot 2024-08-25 144653](https://github.com/user-attachments/assets/be31f6cd-d597-4b0a-8e05-2e13f9ec3d70)
![Screenshot 2024-08-25 144948](https://github.com/user-attachments/assets/fd635ce8-8c2a-46c9-bcd4-0808c9cfae5d)
![Screenshot 2024-08-25 144807](https://github.com/user-attachments/assets/b0c38fa5-5aa0-4cc5-98fd-c48d4d5384a2)
![Screenshot 2024-08-25 144744](https://github.com/user-attachments/assets/07ae1e03-fd1b-4115-822b-fade60894243)
![Screenshot 2024-08-25 144729](https://github.com/user-attachments/assets/2e15b689-160a-48af-9eee-c67f0346eb10)


## ✨ Features

- 📝 **Create and Manage Blogs**: Admin can write, edit, and delete blog posts, users can view and comment on posts.
- 🔍 **Search and Filter**: Easily search and filter content based on tags, categories, or keywords.
- 🧑‍💻 **User Authentication**: Secure user login and registration system.

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Flask
- **Database**: PostgreSQL
- **Hosting**: Render

## 📚 How to Get Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/anandachanta19/Vlog-Blog.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Vlog-Blog
    ```
3. **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```
4. **Activate the virtual environment:**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On MacOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
6. **Set up the database:**
    - Make sure PostgreSQL is installed and running.
    - Create a `.env` file with your PostgreSQL configuration details.

7. **Run the application:**
    ```bash
    flask run
    ```

8. **Access the application:**
    Open your browser and navigate to `http://127.0.0.1:5000/`.

## 🚧 Project Structure

```plaintext
Vlog-Blog/
├── app/
│   ├── static/ (CSS, JS, Images)
│   ├── templates/ (HTML files)
│   ├── models.py
│   ├── routes.py
│   ├── __init__.py
├── migrations/ (Database migrations)
├── .env (Environment variables)
├── requirements.txt
└── README.md

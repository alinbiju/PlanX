# PlanX - Room-Based Discussion Platform

PlanX is a collaborative platform that allows users to **create rooms** and engage in discussions on various topics through **real-time text chat**.

---

## Features

- 🔹 **Create & Join Rooms** – Users can create rooms for discussions and allow others to join.
- 💬 **Real-Time Chat** – Text-based chat system for seamless communication.
- 🎨 **Custom UI** – Interactive design with smooth scrolling and enhanced user experience.
- 🌐 **User-Friendly Interface** – Intuitive and responsive design for easy navigation.

---

## Installation Guide

### 1. Clone the Repository

```sh
git clone https://github.com/YOUR-USERNAME/PlanX.git
cd PlanX
```

### 2. Set Up a Virtual Environment (Optional but Recommended)

```sh
python -m venv env
source env/bin/activate  # On Windows, use: env\Scripts\activate
```

### 3. Install Dependencies

```sh
pip install -r requirements.txt
```

### 4. Set Up Database

```sh
python manage.py migrate
```

### 5. Create a Superuser (Optional)

```sh
python manage.py createsuperuser
```

### 6. Run the Development Server

```sh
python manage.py runserver
```

Now, open `` in your browser to access **PlanX**.

---

## Usage

1. **Create a Room** – Click on "Create" to start a new discussion.
2. **Join a Room** – Click "Join" and enter a room name to participate.
3. **Chat** – Send messages in real time within the room.

---

## Technologies Used

- **Backend:** Django, Django REST Framework
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (default, can be changed to PostgreSQL/MySQL)

---

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to your fork (`git push origin feature-branch`).
5. Create a Pull Request.

---

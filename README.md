# Video Call Web App with Django and ZEGOCLOUD

This project is a **Video Call Web Application** built with **Django** for the backend and integrated with the **ZEGOCLOUD** service to enable seamless video calling functionality.

---

## 🚀 **Features**

- **Real-Time Video Calls** powered by ZEGOCLOUD.
- **User Authentication** for secure login and access.
- **Django Backend** for managing user data and interactions.
- **Responsive UI** for a smooth video call experience on various devices.

---

## 🛠️ **Technologies Used**

- **Backend**: Django
- **Video Calling Service**: ZEGOCLOUD
- **Frontend**: HTML, CSS, JavaScript

---

## 📝 **Setup Instructions**

### 1. **Clone the Repository**

```bash
git clone https://github.com/NareshGusain/Videochat_webapp.git
cd \videocall_app> 
```

### 2. **Create a Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate     # On Windows use `venv\Scripts\activate`
```

### 3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

### 4. **Run the Server**

```bash
python manage.py runserver
```

The app will be available at `http://127.0.0.1:8000/`.

---

## 🔧 **Usage**

1. **Register or Log In** to the application.
2. **Start a Video Call** using the provided interface.
3. **Invite Other Users** to join the call.

---

## 📦 **Project Structure**

```
videocall_app/
│
├── app1/                       # Main Django app
│   ├── templates/               # HTML templates
│   ├── static/                  # Static files (CSS, JS)
│   ├── views.py                 # Django views
│   ├── urls.py                  # URL configurations
│   └── models.py                # Database models
│
├── video_call_app/              # Django project configuration
│   ├── settings.py              # Project settings
│   └── urls.py                  # Project-level URLs
│
├── requirements.txt             # Python dependencies
└── manage.py                    # Django management script
```
## Project screenshots**

### Landing Page
![Landing Page](/screenshots/landing.png)

### Dashboard Page
![Dashboard Page](/screenshots/dashboard.png)

### SignUp & Login Page
![Login Page](/screenshots/login.png)
![Sign Up Page](/screenshots/signup.png)

### Video Call Interface
![Video Call Interface](/screenshots/meeting.png)

---
## 🧾 **Dependencies**

- **Django**: The web framework for the backend.
- **Django Environ** *(optional)*: For managing environment variables.

---

## 🌐 **Resources**

- **Django Documentation**: [https://docs.djangoproject.com](https://docs.djangoproject.com/)
- **ZEGOCLOUD Documentation**: [https://docs.zegocloud.com](https://www.zegocloud.com/docs/video-call/overview?platform=android&language=python)

---

## ✨ **Acknowledgments**

- **Django** for the robust backend framework.
- **ZEGOCLOUD** for the easy-to-integrate video call service.

---

Feel free to customize this `README.md` to fit your needs! 😊
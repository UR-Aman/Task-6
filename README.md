# Personal Portfolio Site

A simple personal portfolio web app built with **Python Flask**, **HTML**, and **CSS**.  
Includes an About page, a Contact form, and basic routing.

## 📌 Features
- **Homepage** with introduction
- **About** page with personal details
- **Contact** page with a form
- Styled using custom CSS
- Flask backend with routing

## 📂 Project Structure
```
portfolio/
│
├── app.py                # Flask backend
├── requirements.txt      # Dependencies
├── templates/            # HTML templates
│   ├── index.html
│   ├── about.html
│   └── contact.html
└── static/
    └── style.css         # Styles
```

## 🚀 How to Run

### 1️⃣ Clone / Download
```bash
git clone <your-repo-link>
cd portfolio
```
Or manually download the project folder.

### 2️⃣ Install Dependencies
Make sure Python is installed. Then run:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the App
```bash
python app.py
```

### 4️⃣ Open in Browser
Visit:
```
http://127.0.0.1:5000/
```

## 🛠 Requirements
- Python 3.8+
- Flask

Install Flask:
```bash
pip install flask
```

## 📧 Contact Form
Currently, the form prints submitted data to the terminal.  
You can integrate **Flask-Mail** or an email API to send form messages directly to your inbox.



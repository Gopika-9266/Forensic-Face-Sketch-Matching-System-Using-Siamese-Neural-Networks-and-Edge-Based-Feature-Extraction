
# 🕵️ Forensic Face Sketch Recognition System

An AI-powered web application that identifies suspects from forensic face sketches by comparing them with a criminal image database and automatically generates investigation reports.

---

## 📌 Overview

The **Forensic Face Sketch Recognition System** is a web-based application developed to support criminal investigations by automating the process of identifying suspects from forensic sketches.

Traditionally, investigators manually compare hand-drawn sketches with thousands of criminal records, making the process slow and error-prone. This system simplifies that process by allowing users to upload a forensic sketch, automatically searching the criminal image database for the closest match, displaying the similarity accuracy, and generating an investigation report that is sent directly via email.

The application combines **Computer Vision**, **Deep Learning**, and **Web Technologies** to provide a faster, smarter, and more reliable approach to forensic face recognition.

---

## 🎯 Objectives

- Automate forensic face sketch identification.
- Reduce the time required for suspect identification.
- Compare uploaded sketches with stored criminal images.
- Display the best matching face with similarity accuracy.
- Generate investigation reports automatically.
- Send the final report through email notification.

---

## ✨ Features

- 🔐 Secure Login System
- 📤 Upload Forensic Face Sketch
- 🧠 AI-Based Face Recognition
- 🗄️ Criminal Database Search
- 🎯 Best Match Detection
- 📊 Matching Accuracy Calculation
- 📧 Automated Email Notification
- 🌐 Interactive Web Interface

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Backend Development |
| Flask | Web Framework |
| HTML | Web Pages |
| CSS | User Interface |
| JavaScript | Client-Side Functionality |
| TensorFlow / Keras | Deep Learning |
| OpenCV | Image Processing |
| NumPy | Numerical Computing |
| Pandas | Data Handling |
| Matplotlib | Data Visualization |
| SMTP | Email Notification |

---

# 🔄 System Workflow

```text
User Login
     │
     ▼
Upload Face Sketch
     │
     ▼
Image Preprocessing
     │
     ▼
Face Sketch Recognition
     │
     ▼
Search Criminal Image Database
     │
     ▼
Find Best Matching Image
     │
     ▼
Calculate Similarity Accuracy
     │
     ▼
Display Result
     │
     ▼
Generate Investigation Report
```

---

# 📸 Application Screenshots

## 🔐 Login Page

<img width="1600" height="814" alt="login" src="https://github.com/user-attachments/assets/2854f5af-02d5-41a6-b937-74afec1101bb" />


---

## 🏠 Home Page

<img width="1600" height="814" alt="home " src="https://github.com/user-attachments/assets/86d4aebb-9369-4f7f-b680-b3f852f68213" />


---

## 📤 Upload Face Sketch

<img width="1600" height="808" alt="upload" src="https://github.com/user-attachments/assets/618e9e4e-bcaa-40ad-aeab-99715fbd82aa" />


---

## 🔍 Recognition Process

<img width="1600" height="816" alt="analysing" src="https://github.com/user-attachments/assets/41746679-a626-4b26-b1f8-ef109e1ba749" />


---

## 🎯 Matching Result

<img width="1600" height="815" alt="match found" src="https://github.com/user-attachments/assets/9283b7f7-645b-4db4-be74-9914dc80fdad" />


---

## 📊 Matching Accuracy
<img width="1600" height="800" alt="matched accuracy" src="https://github.com/user-attachments/assets/79c969e7-3c34-4104-9dbe-9a6aaa565484" />


---



# ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Gopika-9266/Forensic-Face-Sketch-Matching.git

cd Forensic-Face-Sketch-Matching
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Run the Application

```bash
python app.py
```

---

### Open in Browser

```
http://127.0.0.1:5000
```

---

# 🚀 How to Use

### Step 1

Login to the application using valid credentials.

---

### Step 2

Upload the forensic face sketch through the upload page.

---

### Step 3

The uploaded sketch undergoes preprocessing and feature extraction.

---

### Step 4

The system compares the sketch with all stored criminal images.

---

### Step 5

The closest matching face is identified.

---

### Step 6

The similarity accuracy between the sketch and the matched image is calculated.

---

### Step 7

The result is displayed on the screen.

---

### Step 8

An investigation report is generated automatically.

---


# 📊 Results

The developed system successfully performs forensic face sketch recognition by comparing uploaded sketches with stored criminal images.

### The system provides:

- ✔️ Secure Authentication
- ✔️ Sketch Recognition
- ✔️ Criminal Image Matching
- ✔️ Similarity Accuracy
- ✔️ Investigation Report Generation
- ✔️ Automatic Email Notification

---

# 💡 Advantages

- Faster criminal identification process.
- Reduces manual comparison effort.
- User-friendly web interface.
- Accurate sketch matching.
- Automated report generation.
- Efficient email notification system.

---

# 🔮 Future Enhancements

- Real-time sketch recognition.
- Integration with CCTV surveillance.
- GAN-based sketch-to-photo generation.
- Mobile application support.
- Cloud database integration.
- Multi-face recognition.
- Improved recognition for aging and facial expressions.




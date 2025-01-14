# Form-Filling Application

Welcome to the **Form-Filling Application**! This project is designed to simplify form submission by providing a voice-based, automated solution. It uses speech recognition with background noise removal to ensure accuracy and efficiency.

---

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Deployment](#deployment-and-demo-video)
4. [Usage](#usage)
5. [Setup Instructions](#setup-instructions)



---

## Features

- **Voice-Based Input:** Fill out forms using voice commands.
- **Background Noise Removal:** Ensures precise recognition of speech.
- **Real-Time Validation:** Provides instant feedback on form fields.
- **Cross-Platform Compatibility:** Works seamlessly across devices.

---

## Technologies Used

- **Python**: Core programming language
- **SpeechRecognition Library**: Converts speech to text
- **Noise Reduction**: Filters out background noise
- **Flask/Django**: Backend framework (if applicable)
- **HTML/CSS**: Frontend design
- **MySQL**: Database for storing form data

---

## Deployment and Demo video

The project is deployed and accessible using the link below:

**[Deployed using render](https://voiceform.onrender.com/signup)**
---

**[Demo video link](https://www.loom.com/share/69aa4459dab9422884eae5f376531ec9)**
---

## Usage

1. **Visit the Deployment Link:** Click on the live deployment link above.
2. **Start Filling the Form:** Use the microphone icon to begin voice input.
3. **Submit the Form:** Once all fields are filled, click the "Submit" button.
4. **Confirmation:** Receive a confirmation message upon successful submission.

---

## Setup Instructions

### Prerequisites:
- Python 3.x
- MySQL server
- Required Python libraries (see `requirements.txt`)

### Steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo-url
   cd form-filling-application
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Database:**
   - Update database credentials in the `config.py` file.
   - Run database migrations to set up tables.

4. **Run the Application:**
   ```bash
   python app.py
   ```

5. **Access Locally:**
   Open your browser and navigate to `http://localhost:5000`.
   
---
   






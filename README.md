# 🎬 Your Bollywood Lookalike

An AI-powered face recognition application that finds your Bollywood celebrity lookalike from an uploaded image.

The project uses computer vision and facial feature matching techniques to compare a user's face with a dataset of Bollywood celebrities and return the closest match.

---

## ✨ Features

- Upload your image
- Detect faces automatically
- Compare facial embeddings with celebrity dataset
- Find the closest Bollywood celebrity match
- Fast similarity-based search
- Simple and interactive user interface

---

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy
- Face Recognition Library
- Machine Learning
- Streamlit / Flask (depending on implementation)
- Pandas

---

## 📂 Project Structure

```bash
YourBollywoodLookalike/
│
├── dataset/                 # Celebrity images dataset
├── encodings/               # Saved facial embeddings
├── models/                  # Trained models (if any)
├── app.py                   # Main application
├── requirements.txt         # Dependencies
├── utils.py                 # Helper functions
├── README.md
│
└── assets/
    └── screenshots/
```

---

## 🚀 How It Works

1. User uploads an image.
2. Face detection algorithm identifies the face.
3. Facial features are converted into embeddings.
4. Embeddings are compared against stored celebrity embeddings.
5. Similarity scores are calculated.
6. The most similar Bollywood celebrity is returned.

---

## 📸 Example Workflow

### Step 1
Upload your image

⬇

### Step 2
Face Detection

⬇

### Step 3
Feature Extraction

⬇

### Step 4
Celebrity Matching

⬇

### Step 5
Display Your Bollywood Lookalike

---

## 💻 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Nick-ay/YourBollywoodLookalike.git
```

### 2. Move into the Project Directory

```bash
cd YourBollywoodLookalike
```

### 3. Create a Virtual Environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

If a requirements file is not available:

```bash
pip install opencv-python numpy pandas face-recognition pillow
```



## ▶️ Running the Project

### Option 1: Run as a Python Script

```bash
python app.py
```

### Option 2: Run with Streamlit

```bash
streamlit run app.py
```

After running, open:

```text
http://localhost:8501
```

### Option 3: Run with Flask

```bash
python app.py
```

Then open:

```text
http://127.0.0.1:5000
```



## 📦 Requirements

- Python 3.9+
- OpenCV
- NumPy
- Pandas
- Face Recognition
- Pillow

Install all dependencies using:

```bash
pip install -r requirements.txt
```



## 🧠 Face Matching Process

The system follows these steps:

```text
Input Image
     ↓
Face Detection
     ↓
Face Encoding
     ↓
Similarity Comparison
     ↓
Best Match Selection
     ↓
Celebrity Prediction
```



## 🎯 Use Cases

- Entertainment applications
- Celebrity lookalike finder
- Face recognition learning project
- Computer vision portfolio project
- AI and machine learning demonstrations



## 📈 Future Improvements

- Multiple celebrity matches
- Similarity percentage score
- Real-time webcam support
- Larger celebrity database
- Gender and age filtering
- Deep learning-based face embeddings
- Mobile application version



## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request



## 🐛 Troubleshooting

### ModuleNotFoundError

Install missing packages:

```bash
pip install -r requirements.txt
```

### Face Not Detected

- Use a clear frontal image
- Ensure good lighting
- Avoid heavily filtered photos

### Slow Performance

- Reduce image resolution
- Use GPU acceleration if available



## 📄 License

This project is licensed under the MIT License.



## 👨‍💻 Author

**Nikita Sheoran**

- AI & Machine Learning Enthusiast
- Computer Vision Projects
- Smart Agriculture Solutions
- Data Analytics & Software Development



## ⭐ Support

If you found this project useful:

- Star the repository
- Share it with others
- Contribute to the project


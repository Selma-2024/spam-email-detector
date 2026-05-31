# spam-email-detector
readme = """# 📧 Spam Email Detector

A deep learning project that connects to Gmail via IMAP and automatically detects and deletes spam emails using a trained Keras model.

## 🔧 Tech Stack
- Python
- TensorFlow / Keras
- IMAP (Gmail)
- Google Colab

## 📁 Project Structure
spam-detector/
├── spam_detector.ipynb   # Main Colab notebook
├── .env.example          # Template for credentials
├── .gitignore            # Files excluded from GitHub
└── README.md             # Project documentation
## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/spam-detector.git
```

### 2. Create your .env file
```bash
cp .env.example .env
```
Fill in your Gmail and App Password in the .env file.

### 3. Enable Gmail IMAP
- Go to Gmail Settings → Forwarding and POP/IMAP
- Enable IMAP

### 4. Generate App Password
- Go to: https://myaccount.google.com/apppasswords
- Create a new app password
- Paste it in your .env file

### 5. Run the notebook in Google Colab

## ⚠️ Security Note
Never share your .env file. It is excluded from GitHub via .gitignore.

## 📊 Model
- Built using TensorFlow/Keras
- Trained on public spam email dataset
- Uses LSTM / Dense layers for classification
"""

with open('README.md', 'w') as f:
    f.write(readme)

print("✅ README.md created!")

# DocVer

# 🛡️ DocVerification - Document Authenticity Checker

**DocVerification** is a lightweight web application designed to verify the authenticity of uploaded documents. It likely uses cryptographic hashing (e.g., SHA-256) and a simple Flask backend to ensure document integrity.

## 🚀 Features

- Upload PDF or image-based documents  
- Generate and compare secure hashes  
- Organized file storage (`uploads/` and `temp_uploads/`)  
- Simple, elegant frontend using Tailwind CSS and Bootstrap  
- Extendable backend with Flask (Python)

## 📁 Project Structure

```
DocVerification/
├── app.py              # Main Flask application
├── .env                # Environment configuration
├── static/             # CSS and images
│   ├── bootstrap.min.css
│   ├── tailwind.min.css
│   ├── main.css
│   └── favicon.jpg
├── templates/          # HTML templates
│   ├── index.html
│   ├── upload.html
│   ├── verify.html
│   └── result.html
├── uploads/            # Final uploaded files
├── temp_uploads/       # Temporary file handling
```

## ⚙️ Technologies Used

- Python 3.x  
- Flask (Web Framework)  
- Tailwind CSS  
- Bootstrap  
- Cryptographic Hashing (e.g., SHA-256)

## 🛠️ Setup Instructions

1. **Extract the zip and go into the folder**  
   ```bash
   unzip DocVerification.zip  
   cd DocVerification  
   ```

2. **(Optional) Create a virtual environment**  
   ```bash
   python3 -m venv venv  
   source venv/bin/activate   # On Windows: venv\Scripts\activate  
   ```

3. **Install dependencies**  
   If there's a `requirements.txt` file:  
   ```bash
   pip install -r requirements.txt  
   ```

4. **Set environment variables** (either in `.env` or manually):  
   ```
   FLASK_APP=app.py  
   FLASK_ENV=development  
   ```

5. **Run the Flask app**  
   ```bash
   flask run  
   ```

6. **Visit in browser**  
   ```
   http://127.0.0.1:5000  
   ```

## 📂 Notes

- `.DS_Store` and `__MACOSX/` can be deleted — they’re system files from macOS  
- `uploads/` is where final documents are stored  
- `temp_uploads/` is used for temporary document processing  
- You can customize the UI by editing `static/main.css`

## 📄 License

This project is open source and free to use under the **MIT License**.

---

**Built for secure, verifiable document uploads.**



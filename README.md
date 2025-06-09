# PDF-File-Integrity-Checker-using-SHA-1-Hashing
A simple Python script that compares two files using SHA-1 cryptographic hashes. It reads both files in binary mode, computes their respective hashes in chunks (to handle large files), and checks if they are byte-for-byte identical. This is useful for verifying data integrity, checking for duplicate files, or detecting tampering.
# File Integrity Checker using SHA-1 Hashing

This is a simple Python script that verifies whether two files are exactly the same by computing and comparing their SHA-1 hashes.

---

## 🔍 Features

- Compares any two files (e.g., PDFs, images, executables, etc.)
- Uses SHA-1 hashing for secure comparison
- Reads files in chunks to support large file sizes
- Useful for detecting duplicate files, tampering, or verifying downloads

---

## 🛠 Requirements

- Python 3.x

---

## 📁 File Structure

## ▶️ How to Use

1. **Place the files** you want to compare in the same directory as the script (or provide full paths).
2. **Run the script**:

```bash
python3 file_hash_checker.py

# 🕵️‍♂️ Stegano-Secure: Image Data Hiding

---

## 🚀 Explore the Repository

* **Project Type:** Cybersecurity & Image Processing
* **Methodology:** LSB (Least Significant Bit) Encoding
* **Input Formats:** PNG, BMP (Lossless images)

---

## 🛠️ Tech Stack

* **Language:** Python
* **Data Processing:** NumPy (for pixel array manipulation)
* **Image Handling:** OpenCV & Pillow
* **Workflow:** Jupyter Notebook

---

## ⚙️ Features

* **Encrypted Embedding:** Convert text messages into binary and weave them into image pixels.
* **Invisible Results:** The "Stego-Image" remains 100% visually identical to the original.
* **Secure Extraction:** A dedicated decoding process to retrieve messages only when the image is processed by the script.
* **Pixel Precision:** High-speed manipulation using NumPy for efficient processing.

---

## 🧠 How It Works (The Logic)

This project operates on the **8-bit color depth** of digital images. 



1. **Each pixel** has Red, Green, and Blue values (0-255).
2. We change only the **last bit** (the Least Significant Bit) of these values.
3. Mathematically, changing `11111111` (255) to `11111110` (254) is a change of only **0.3%** in color—completely invisible to the human eye!

---

## 📂 File Structure

* **`Steganography.ipynb`** - The main logic for encoding and decoding.
* **`sample_images/`** - Test images used for the project.
* **`requirements.txt`** - List of necessary Python libraries.

---

## 🚀 How to Run Locally

### 1. Clone the repo:
```bash
git clone [https://github.com/kothapallivennela/Steganography.git](https://github.com/kothapallivennela/Steganography.git) Student

````markdown
# Ersy - Secure Steganography with RSA and AES

Ersy is an advanced GUI-based steganography tool that securely hides and extracts encrypted files within image files. It combines **AES-256** for fast encryption and **RSA-4096** for secure key exchange, along with **seeded LSB steganography** for undetectable data embedding.

---

## 🔐 Features

- AES-256 encryption of your secret data
- RSA-4096 key generation for secure communication
- Seeded LSB steganography for randomized pixel embedding
- Support for PNG, BMP, TGA, and TIFF image formats
- Zlib compression for minimal footprint
- Simple and intuitive GUI with pop-up windows
- All-in-one `.exe` bundling support for Windows

---

## 📦 Installation

### 1. Clone the repository:
```bash
git clone https://github.com/eswarsaimandati/ersy.git
cd ersy
```
````

### 2. Install dependencies:

```bash
pip install -r requirements.txt
```

> Requirements include:
>
> * `cryptography`
> * `Pillow`
> * `numpy`

---

## 🚀 How to Run

### Run the GUI:

```bash
python ersy_gui.py
```



---

## 🧩 How It Works

1. **Key Generation**:

   * Generates `mypublickey.pem` and `myprivatekey.pem` using RSA-4096.
   * Saved in the application directory.

2. **Encryption**:

   * Compresses and encrypts the file with AES.
   * AES session key is encrypted with RSA.
   * All data is embedded using LSB steganography in the selected image.

3. **Decryption**:

   * Extracts and decrypts the data using the private RSA key.
   * Decompresses and reconstructs the original file.

---

## 📁 Output

* Encrypted image: `output.png`
* Decrypted file: Saved to the selected path.
* Keys: `myprivatekey.pem` and `mypublickey.pem` (saved locally).

---



---

## 📜 License

This project is licensed under the **GNU GPLv3**. See `LICENSE` for details.

---

## 🙌 Credits

Built by \[MANTADI ESWAR SAI – 
AMUDALA YOGA NRUSIMHA REDDY– 
BATTULA SURESH REDDY– 
GUTTIKONDA RAJASEKHAR REDDY–]
Based on advanced cryptography and steganography techniques.

```


```

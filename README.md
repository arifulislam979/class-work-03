# Secret Communication Tool
### Overview
This tool allows you to send personal messages and information with privacy by encrypting and decrypting the text.

* **Encryption:** Translates plain text into ciphertext, making it unreadable without the decryption key.

* **Decryption:** Converts ciphertext back into plaintext using the correct key.

---

### Prerequisites
Ensure you have Python installed on your system and the following modules:

1. Tkinter: For the graphical user interface.
2. Base64: For encryption and decryption.

To install the modules, run:

```
pip install tk
pip install base64
```

---

### How It Works
1. Enter your message in the provided text area.
2. Provide a key for encryption or decryption.
3. Use the Encrypt button to encode your message.
4. Use the Decrypt button to decode a previously encrypted message.

---

### Code Implementation
**Step 1: Import Required Libraries**
```
from tkinter import *
import base64
```
**Step 2: Create the GUI Window**
```
root = Tk()
root.geometry("500x300")
root.title("Secret Communication Tool")
```

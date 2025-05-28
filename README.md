# 🖋️ PDF-Sign

A quick and simple Python script to **add signature images to PDFs** — ideal for Linux users who need a no-fuss, GUI-free tool.

---

## ✅ Features

- 🧩 Supports **most PDF formats**
- 🖼️ Works with **PNG and JPG signature images**
- 📄 **Preserves original text** (no image conversion of pages)
- 📅 Optionally append the **date** next to the signature

---

## 🛠️ Installation

### 📦 Using pip

### bash
    pip install signpdf


## 🧪 From source
    git clone https://github.com/yourcelf/signpdf
    cd signpdf
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

## 📝 Usage

### ✍️ Basic signature

        signpdf contract.pdf sig.png --coords 1x100x100x150x40

### 🧭 Coordinates format:

    <pagenum>x<x-coord>x<y-coord>x<width>x<height>

- pagenum → page number (starting at 1)

- x-coord → horizontal distance from bottom-left (in 1/72 inch units)

- y-coord → vertical distance from bottom-left (in 1/72 inch units)

- width → signature width

- height → signature height

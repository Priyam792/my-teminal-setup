# 💻 My Terminal Setup (Linux Rice)

A clean, minimal, and aesthetic terminal setup using **Kitty + Fastfetch** with a boxed UI, icons, and color-coded sections.

---

## 📸 Preview

---

## ✨ Features

* 📦 Boxed Fastfetch layout
* 🎨 Color-coded sections (System, Storage, Session)
* ⚡ Icons + arrows for a modern UI
* 🧊 Glass-style terminal (transparency + blur)
* 🖼️ Custom image logo (Kitty graphics protocol)
* 💀 Clean and minimal "riced" setup

---

## ⚙️ Requirements

Make sure you have the following installed:

* **Kitty Terminal**
* **Fastfetch**
* **Nerd Font** (for icons)
* A Linux distro (tested on Ubuntu)

---

## 🔤 Font Used

This setup uses a Nerd Font for proper icon rendering.

👉 Recommended:

* **MesloLGS Nerd Font**
  Download from: https://www.nerdfonts.com/font-downloads

* Or any Nerd Font of your choice

---

## 🎨 Tokyo Night Theme (Kitty)

This setup uses a **minimal dark theme with transparency**, based on the **Tokyo Night theme**.

### 🎨 Applying Tokyo Night Theme (Kitty + kitten themes)

Kitty provides built-in themes via `kitten themes`.

Run:

```bash
kitty +kitten themes
```

Then search for:

```
Tokyo Night
```

Select it and apply.

To make it permanent, add this line to your `kitty.conf`:

```conf
include ~/.config/kitty/themes/Tokyo_Night.conf
```

---

### 🧊 Glass Effect (Blur + Transparency) (optional)

Transparency is handled by Kitty, but **blur depends on your desktop environment**.

#### For GNOME:

Install extension:
👉 **Blur My Shell**

Then:

* Enable blur
* Adjust opacity & radius

---

### 🎨 Colors

You can customize colors inside `kitty.conf`:

```conf
background #0f111a
foreground #cdd6f4
cursor #f5e0dc
```

---

## 📂 Repository Structure

```
my-terminal-setup/
 ├── fastfetch/
 │    └── config.jsonc
 ├── kitty/
 │    └── kitty.conf
 ├── screenshots/
 │    └── setup.png
 └── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```
git clone https://github.com/Priyam792/my-terminal-setup.git
cd my-terminal-setup
```

---

### 2. Install dependencies

```
sudo apt install kitty fastfetch
```

---

### 3. Copy configuration files

```
mkdir -p ~/.config/fastfetch ~/.config/kitty

cp fastfetch/config.jsonc ~/.config/fastfetch/
cp kitty/kitty.conf ~/.config/kitty/
```

---

### 4. Run Fastfetch

```
fastfetch
```

---

## ⚠️ Important Notes

### 🖼️ Change Image Path

The Fastfetch config uses a demo image path:

```
~/Pictures/demo.png
```

👉 Replace it with your own image:

```
/home/your-username/Pictures/your-image.png
```

---

### 🎨 Font Requirement

If icons are not showing:

* Install a Nerd Font
* Set it in Kitty config

---

### 🧠 Nerd Font Not Showing?

Run:

```
fc-cache -fv
```

Then restart terminal

---

## 🎯 Customization

You can:

* Change Fastfetch layout
* Modify box width
* Replace icons
* Use different fonts
* Change colors in Kitty

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 😎 Author

Made with 💀 by **Priyam792**

---

## ⭐ If you like this setup

Give it a ⭐ on GitHub and feel free to fork!

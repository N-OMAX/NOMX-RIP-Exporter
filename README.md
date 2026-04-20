<p align="center">
  <a href="https://ibb.co/HfgcV860">
    <img src="https://i.ibb.co/G4PZ0SyX/nomxrip.png" alt="NOMX RIP Exporter Logo" border="0">
  </a>
</p>

# NOMX RIP Exporter

> **A modern, fast, and user-friendly batch converter to extract and convert `.rip` model files into standard `.obj` (with `.mtl` material files) or `.glb` formats.**

---

## 🌟 What is it & What does it do?

**NOMX RIP Exporter** takes raw `.rip` 3D mesh files (typically dumped using tools like [NinjaRipper](https://www.ninjaripper.com)) and effortlessly converts them into widely supported 3D formats. It will automatically detect texture associations (DDS) and construct the model correctly, making them ready for your 3D scenes or game engines.

### 🚀 Key Features

* **Bulk Processing GUI**: Select multiple `.rip` files at once using the modern graphic interface and convert them all with a single click.
* **Drag & Drop CLI**: Allows fast command-line execution if you prefer simply dropping files onto the script.
* **Auto-Texture Linking**: Automatically generates `.mtl` files, hooking up Diffuse, Normal maps, and Specular maps (if they are found in the same folder).
* **Format Support**: Generates `.obj` and `.mtl` files by default (Can also be toggled to `.glb` format in the code).
* **Auto UV Flips**: Automatically corrects UV mapping coordinates so everything aligns correctly in your 3D software.

---

## 📥 How to Download 

If you simply want to download the tool:

1. Look at the top right of this GitHub page.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the zip file anywhere on your PC.

---

## 💻 How to Clone (For Developers)

If you prefer using Git to clone the repository to your computer, open your console and run:

```bash
git clone https://github.com/N-OMAX/NOMX-RIP-Exporter.git
```

---

## 🛠️ How to Use

1. Ensure you have **Python 3** installed on your Windows PC.
2. Double-click `NOMX-RIP-TO-OBJ.py` to open the graphic interface.
3. Click on **📂 SELECT FILES** and pick all the `.rip` files you want to convert.
4. Click **🚀 START EXPORT** to begin. The terminal will show live progress logs.
5. All `.obj` and `.mtl` files will be saved right next to your original `.rip` files.

*Alternatively, you can just drag and drop your `.rip` files directly onto `NOMX-RIP-TO-OBJ.py` in your file explorer to convert instantly without the GUI!*

---

## 🧪 Compatibility

* ✔️ **Fully tested and 100% working with the newest Blender 5.1 version.**
* Other 3D packages (like Maya, 3ds Max, Cinema4D, Unreal Engine, Unity) have not been explicitly tested. However, since the tool exports universal formats (`.obj`, `.mtl`, `.glb`), they should import perfectly fine anywhere.

---

*Powered by NOMX*
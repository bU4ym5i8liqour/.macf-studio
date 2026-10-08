# 📂 MACF Pro Studio (Multi-Asset Compressed Folder)

Welcome to the official repository of the **.macf** file ecosystem! This application allows you to bundle multiple project assets into a single, custom compressed file container that dynamically expands when opened and securely collapses back down when closed.

---

## ✨ Features
* **Custom Format (.macf):** A unique file type recognized natively on your system.
* **Auto-Expand:** Double-clicking a `.macf` file unfolds all contents into a clean desktop folder layout.
* **Dynamic Auto-Collapse:** The second you finish working and close your session, the files vanish from the desktop and zip back down into the package.
* **AppData Safety Engine:** Automatically creates historic, timestamped security backups inside your system's `%appdata%\.macfbackups` directory.
* **Bypass Blocker:** Prevents unauthorized direct file access by launching an automated warning notice if someone tries to inspect a raw container.

---

## 🚀 How to Install and Set Up

1. Go to the **Releases** section on the right side of this page.
2. Download the `MACF_Studio.zip` file package and extract it to your computer.
3. Move the `MACF_Studio.exe` to a permanent folder on your drive (e.g., `C:\MACF_Project`).

### Link your .macf files to the App:
To make the format official on your system:
1. Right-click any `.macf` file on your computer.
2. Select **Open with** (*Öffnen mit*) ➔ **Choose another app** (*Andere App auswählen*).
3. Check the box that says **"Always use this app to open .macf files"** (*Immer diese App zum Öffnen von .macf-Dateien verwenden*).
4. Click **Choose an app on your PC** at the bottom, navigate to your folder, and select `MACF_Studio.exe`.

---

## 🛠️ How to Use The Dashboard

* **📂 Create Fresh / Save Manual:** Creates a brand-new workspace folder on your desktop (`MACF_Temp`). Drop your assets, images, or documents inside, then use the studio panel to lock it down into a single `.macf` container.
* **📂 Open & Expand:** Select any existing `.macf` file package to unpack it instantly. A control window will stay active on top. Once you are done modifying your files, click **"Close Folder & Save Changes"** to automatically clear your desktop workspace.

---

## 💻 Tech Stack & Architecture
* **Language:** Pure Python (windowless backend routing wrapper).
* **Interface System:** Custom Tkinter GUI Framework layer.
* **Storage Engine:** Native environment variables linking directly to secure sandboxed memory directories.

# User Guide: How to Run the Radio Configuration Manager

Welcome to the Radio Configuration Manager! This guide will walk you through launching the standalone executable (`.exe`) file, programming your radios, and understanding how the cloud update system works.

---

## ⚡ Quick Start: Running the App

Because this application is bundled into a standalone executable, **you do not need to install Python or any extra software.** 

1. **Download:** Download the `Radio_Config_Manager.exe` file to your computer.
2. **Move to a Folder:** Place the `.exe` file into its own folder (for example, a folder on your Desktop named `Radio Manager`). 
3. **Launch:** Double-click `Radio_Config_Manager.exe` to run the app.

> **First-Time Launch Delay:** The very first time you open the app, your computer has to unpack the files into a temporary space. This can take anywhere from 3 to 10 seconds. Future launches will be much faster!

---

## 🛡️ Windows SmartScreen Warning (First Launch)

Because this is a custom, independent utility tool, Windows might pop up a blue or gray warning box saying: *"Windows protected your PC — Microsoft Defender SmartScreen prevented an unrecognized app from starting."*

**Don't panic! This is completely normal for newly compiled apps.**

### How to bypass it:
1. Click the small **"More info"** text link directly inside the warning box.
2. A button labeled **"Run anyway"** will appear at the bottom.
3. Click **Run anyway**, and the application will open perfectly. You will only have to do this once!

---

## 📡 How the Automatic Cloud Updates Work

One of the best features of this app is that **you never have to download a new `.exe` file just to get support for new radios.** 

* **If you are connected to the Internet:** Every time you open the app, it automatically pings our secure GitHub database in less than a second. If we added a brand new radio to the list this morning, it will instantly show up in your dropdown menus!
* **If you are completely offline:** The app will seamlessly load its internal built-in list of radios. You can still do all your programming without an internet connection.

---

## 🛠️ Step-by-Step Instructions

### 1. Select Your Radio
Click the **Manufacturer** dropdown to choose your brand (e.g., Baofeng, Yaesu, Icom). Once selected, the **Model** dropdown will instantly adjust to show every supported radio for that brand.

### 2. Name-Tag Memory Safeguards
When typing names for your channels (like `LOCAL REPEATER` or `CAMPING`), the app will automatically handle your specific radio's hardware limits during data transfer:
* **Baofeng:** Maximum of 7 characters.
* **Commercial Radios / Icom:** Maximum of 8 characters.
* **Yaesu:** Maximum of 16 characters.

### 3. Connect and Program
1. Plug your programming cable into your PC's USB port and connect it to your radio.
2. Turn the radio **ON** and turn the volume up to maximum (required by many radios to transfer data).
3. Select your **COM Port** in the app and click **Upload to Radio** or **Download from Radio**.

---

## ❓ Troubleshooting & FAQ

#### **Q: The app opens but the radio dropdowns only show a few brands!**
**A:** This means the app was unable to reach the internet server on boot and has loaded the basic offline fallback list. Close the app, check your internet connection, and reopen it to pull the massive 320+ master radio index.

#### **Q: My programming cable isn't connecting to the app.**
**A:** Make sure the cable is pushed *completely* into the radio (especially on Baofeng radios, where the 2-pin connector requires a firm click). Also, ensure you have installed the correct USB driver (like the CH340 or Prolific driver) for your specific cable interface.

#### **Q: Can I use this without an internet connection?**
**A:** Absolutely! The app will simply use the built-in fallback list saved inside the program, allowing you to work in remote field sites or offline environments seamlessly.

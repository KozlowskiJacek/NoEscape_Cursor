# NoEscape Cursor  

**NoEscape Cursor** is a simple program that locks the edges of your primary monitor whenever a selected game or application is active. This prevents your mouse cursor from escaping to another screen during gameplay.  

Example: while playing *Heroes of Might and Magic III*, you can freely move the map without the cursor jumping to the second monitor.  

- ✅ Works only when the selected process is active  
- ✅ Supports *Alt+Tab* (you won’t get locked out of your PC)  
- ✅ Unlocks automatically when the process is minimized  
- ✅ Closing the GUI stops the script  
- ✅ Does not autostart with Windows  

---

## Origin / History  

The idea for **NoEscape Cursor** came when I wanted to play *Heroes of Might and Magic III* and had a problem – the mouse cursor would escape to the second monitor while moving the map. Existing solutions seemed too complicated and time-consuming in the settings, and they blocked the entire screen regardless of whether the game was active or not.  

I decided to create my own script using **AHK (AutoHotKey)**, which locks the monitor edges **only when the selected process is active**. I thought this could help other gamers (or not only gamers 😉), so I made a **simple Python GUI**, which allows you to:  

- enter the process name,  
- save the setting,  
- remove it if you made a mistake.  

I hope this program will help someone and make gaming without a runaway cursor easier!  

---

## Requirements  

- Operating system: Windows (tested on Windows 10/11)  
- No programming knowledge required  
- Python **is not required** – just download and run  

---

## Installation  

1. Download the package from GitHub  

<div align="center">
  <img src="https://github.com/user-attachments/assets/c9e82503-bf47-4680-b255-b4b514e0d462" width="400" alt="Downloaded folder" />
  <p>Folder with the downloaded files</p>
</div>

2. Extract the folder anywhere on your computer  
3. Run `NoEscapeCursor.exe` to open the GUI  

<div align="center">
  <img src="https://github.com/user-attachments/assets/6c39410a-ed7e-49aa-911d-1a7be9c3170a" width="300" alt="NoEscapeCursor exe" />
  <p>Click the exe file to open the GUI</p>
</div>

---

## How to Use  

1. **Launch the game** or program where you want to lock the cursor  
2. Open `NoEscapeCursor.exe`  
3. In the program window, enter the **process name**, not the game title  

### 🔴 Important: what does "process name" mean?  
- **Do not enter** the game title, e.g., *Might and Magic Heroes III*  
- **Enter** the process name, e.g., `HOMM3 2.0.exe`  

### How to find the process name of your game:  

1. Press **Ctrl + Shift + Esc** to open **Task Manager**  
2. Click the **Details** tab  

<div align="center">
  <img src="https://github.com/user-attachments/assets/c4803186-e0df-47dc-b8b3-52d529b6be28" width="600" alt="Task Manager Details tab" />
  <p>Click the "Details" tab</p>
</div>

3. Find your running game (e.g., Heroes of Might and Magic III)  
4. In the **Name** column, you will see something like `HOMM3 2.0.exe`  

<div align="center">
  <img src="https://github.com/user-attachments/assets/631b491e-117d-48ff-ae04-79a736d9b005" width="600" alt="Game process name" />
  <p>Copy the process name (e.g., HOMM3 2.0.exe)</p>
</div>

5. Copy this name and enter it in the program  

---

## Enabling Cursor Lock  

1. Enter the process name in the GUI  

<div align="center">
  <img src="https://github.com/user-attachments/assets/87f24c34-4aa4-4658-807f-88846e2ba4e4" width="300" alt="GUI enter process name" />
  <p>Enter the process name</p>
</div>

2. Click **Confirm** (or the corresponding button in your GUI)  

<div align="center">
  <img src="https://github.com/user-attachments/assets/3c251dca-92eb-4527-acd2-f7a4d38b6a57" width="300" alt="Confirm button" />
  <p>Click Confirm to start locking</p>
</div>

3. The lock now works **only when the game is active**  
4. If you minimize the game – the lock disappears  

---

## Disabling  

- To stop the program, just close the GUI (`X` in the top-right corner)  
- After closing, the program does not run in the background  
- After restarting the computer, the program **does not start automatically**  
- The program runs in the background and shows a **H** icon in the system tray. If it doesn’t automatically stop when the GUI is closed, don’t worry – it won’t affect anything and will disappear after a computer restart. You can also right-click the icon and select **Exit** to close it manually.  

<div align="center">
  <img src="https://github.com/user-attachments/assets/47466510-b210-4300-8474-92c23384818e" width="200" alt="System tray icon" />
  <p>H icon in the system tray</p>
</div>

---

## Tested Games  

- Heroes of Might and Magic III   

---

## Author  

**Jacek Kozłowski**  
📧 Contact: jacek.kozlowski.business@gmail.com

---

## License  

This project is released under the **MIT License** – free to use, modify, and share.

# Night Shift

**Night Shift** is a narrative-driven psychological horror game set during a late-night convenience store shift.  

---

## Story

You play as a night shift worker in a convenience store, expecting nothing more than another uneventful shift.  
As the night progresses, subtle details begin to feel *off* — locked doors, strange discoveries, and lingering silence.

What starts as routine slowly unfolds into something deeply unsettling.

---

## Concept

**Psychological horror**

The game was designed to feel grounded and realistic, relying on sound design, lighting, and timing to create tension.

---

## Development Stack

**Engine**
- Unity 

**Language**
- C#

**UI**
- Unity UI
- TextMeshPro

**Audio**
- Unity AudioSource

**Input**
- Unity Input System 

**Platform**
- Windows 

---

## Setup Instructions

Follow these steps carefully to download and run **Night Shift**. This guide assumes nothing — even if you have never used Git before.  

---

### Step 1: Install Git and Git LFS

**Step 1.1: Download Git**

- Go to the official Git website: [https://git-scm.com/downloads](https://git-scm.com/downloads)  
- Choose your operating system (Windows).  
- Download and run the installer.  
- During installation, you can use the default options. Click **Next** until it finishes.  

**Step 1.2: Download Git LFS**

- Go to the official Git LFS website: [https://git-lfs.github.com/](https://git-lfs.github.com/)  
- Download the installer for your operating system.  
- Run the installer and follow the prompts.  

**Step 1.3: Initialize Git LFS**

- Open **PowerShell** (Windows).
- Run this command to make Git LFS work in your Git repositories: 

  -> **git lfs install** <-

- Once that's done, you're all set.

### Step 2: Open a Terminal and Choose a Download Location

**Step 2.1: Open Terminal**

- Windows: Press Win + S, type PowerShell, press Enter.

**Step 2.2: Navigate to where you want to put the game**

- For example, on Windows, use your Downloads folder.
- Run this command:

  -> **cd "C:\Users\YourUsername\Downloads"** <-

- Replace **YourUsername** with your Windows username.
- This is where the game folder will be saved.

### Step 3: Clone the Repository (Download the Game Files)

**Step 3.1: Run the clone command**

- Run this command: 

  -> **git clone https://github.com/git-emjey/Night-Shift.git** <-

- This will create a folder called Night-Shift with all the files.

**Step 3.2: Go into the folder where the cloned repo is**

- Run this command:

  -> **cd "Night-Shift"** <-

- Now you are inside the cloned repository folder.

### Step 4: Download All Large Game Files (Git LFS)

- Git LFS tracks large files (like Unity game data). If you skip this, the game won’t run.
- Run this command:

  -> **git lfs pull** <-

- Wait until it finishes downloading all the big files.
- Now your folder has everything needed to run the game.

### Step 5: Run the Game

**Step 5.1: Open the folder Night-Shift.**

- Find the folder in your downloads called **Night-Shift** and open it.

**Step 5.2: Double-click this file:**

- You will find this file inside the cloned repository folder, double-click it:

  -> **Night Shift.exe** <-

- The game will launch.

### Controls
- **W / A / S / D** for movement  
- **E**: Interact with doors 
- **F**: Interact with paper and key

Notes:  

- Do NOT use “Download ZIP” from GitHub — it will not include LFS files and the game will fail to run.
  
- Using Git + Git LFS is the only way to get a working copy.


## Team Roles
**Design & Programming:** Marcjohn F. Castillon - ITE 18 EO1 


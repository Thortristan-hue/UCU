# 📁 How to Make Your Own Murder Mystery Case
### A Simple Guide for Microsoft Word & Notepad Users

You don't need any coding or technical knowledge to build a playable case. All you need is **Microsoft Word** (or **Notepad / TextEdit**) and a standard folder on your desktop.

---

## 🗂️ Step 1: Create Your Main Folder

1. Right-click on your desktop, choose **New > Folder**, and name it your case title (e.g. `Lighthouse_Mystery`).
2. Open that folder and create these **5 subfolders** inside it:

```text
Lighthouse_Mystery/
├── 01_Briefing
├── 02_Profiles
├── 03_Evidence
├── 04_Interrogations
└── 99_Classified
```

> 💡 **Tip:** Keep the numbers at the start (`01_`, `02_`, etc.) so the computer displays your folders in the right order.

---

## 📄 Step 2: What Goes Inside Each Folder

| Folder | What to Put Inside | Example Files |
|---|---|---|
| **`01_Briefing`** | The intro report, police dispatch notes, or letter that starts the story. | `briefing.txt` or `briefing.md` |
| **`02_Profiles`** | Background sheets for suspects and victims (alibis, ages, jobs). | `suspect_john.txt`, `victim.txt` |
| **`03_Evidence`** | Photos, autopsy reports, and data sheets. | `crime_scene.jpg`, `phone_logs.csv` |
| **`04_Interrogations`** | Initial written interview transcripts from the day of the incident. | `interview_alibi.txt` |
| **`99_Classified`** | The secret answer and AI instructions. **Players cannot see this folder!** | `solution.txt` and a `characters/` folder |

---

## ✍️ Step 3: Writing Files with Word or Notepad

### How to Save Your Text Files:
You can write your story in **Microsoft Word** or **Notepad**:
- In **Microsoft Word**: Click **File > Save As**, and under *Save as type*, choose **Plain Text (*.txt)**.
- In **Notepad**: Just type and click **File > Save**.
- For tables or spreadsheets: Save directly from **Excel** as **CSV (Comma delimited) (*.csv)**. The portal will automatically display it as a searchable table!

---

## 🤖 Step 4: Setting Up AI Suspects (Inside `99_Classified/characters`)

Inside `99_Classified`, create a folder named `characters`. Each file you put here allows players to question that suspect in the **Live Interrogation Chamber**!

Create a file named after the suspect (e.g. `jonas.txt`):

```text
# Jonas Berg
Role: Nephew
Opening line: "Why are you questioning me? I told you I was asleep!"

What this character knows:
- You are secretly guilty. You hit Elias with a wrench at 11:45 PM.
- Lie and tell the detective you were in bed by 10:00 PM.
- If they ask about the wet boots, claim you went out for firewood earlier.
- Only confess if they trap you with the phone logs and the coroner report!
```

- **`# Name`**: The name shown on the suspect button.
- **`Role:`**: Their job or relationship to the victim.
- **`Opening line:`**: The first greeting the suspect speaks when the microphone turns on.
- **Everything else**: Secret instructions for the AI on how to behave, lie, and react.

---

## 🔒 Step 5: The Secret Solution File (`99_Classified/solution.txt`)

Inside `99_Classified`, save a file named `solution.txt` containing the truth:
- Who did it?
- What weapon did they use?
- Why did they do it?

When the player clicks **ARREST WARRANT** in the game, the system checks their accusation against this file.

---

## 📦 Step 6: Turn It Into a Playable Case (.ZIP)

When all your files and folders are ready:
1. Select your 5 folders (`01_Briefing`, `02_Profiles`, `03_Evidence`, `04_Interrogations`, `99_Classified`).
2. **Right-click** on them.
3. Choose **Send to > Compressed (zipped) folder** (on Mac: **Compress items**).
4. Drag your new `.zip` file into **Project Precinct** in your web browser to start investigating!

---

---

## 📌 Non-Technical Quick Checklist
Looking for a fast reference of all mandatory naming rules, folder structures, and solution file formats?  
👉 Read the **[CASE_CREATOR_QUICKSTART.md](file:///c:/Users/Thor/Downloads/UnsolvedCrimesUnit/CASE_CREATOR_QUICKSTART.md)**!

---

## 🤖 For AI Agents & Scenario Designers
If you are an AI assistant or technical scenario author tasked with generating a complete case archive, refer to the in-depth technical specification:
👉 **[CASE_CREATION_SPEC.md](file:///c:/Users/Thor/Downloads/UnsolvedCrimesUnit/CASE_CREATION_SPEC.md)** — Includes exact regex parsing headers, keyword adjudication algorithms, character breaking conditions, and narrative design checklists.


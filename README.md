# DraftAI-Addin

# Draft AI — SolidWorks Sketch Analyzer

AI-powered SolidWorks add-in that detects missing constraints 
and dimensions in your sketch automatically.

Press **Ctrl+Shift+A** inside any sketch to analyze it.

## Requirements
- SolidWorks 2020 or later
- .NET Framework 4.8
- OpenAI API key

## Installation
1. Download the latest release zip below
2. Extract to any folder
3. Right-click `install.bat` → **Run as Administrator**
4. Open SolidWorks → Tools → Add-Ins → enable **Draft AI**
5. Set your API key by running:
```
$env:OPENAI_API_KEY = "sk-..."
python draftai_setup.py
```

## Usage
- Open any Part file in SolidWorks
- Enter a sketch (double-click a sketch face)
- Press **Ctrl+Shift+A**
- A toast notification will show exactly what's missing

## License
MIT
```

---

**Step 5 — Zip your release folder**
Right-click the `DraftAI_Addin` folder → **Send to** → **Compressed (zipped) folder**
Name it `DraftAI_Addin_v1.0.0.zip`

---

**Step 6 — Upload to GitHub**
- Go to your repo page
- Click **Releases** on the right side → **Create a new release**
- Click **Choose a tag** → type `v1.0.0` → click **Create new tag**
- Title: `Draft AI v1.0.0 — SolidWorks Sketch Analyzer`
- In the description write:
```
## What's new
- Ctrl+Shift+A hotkey to analyze any sketch
- GPT-4o vision identifies missing constraints and dimensions
- Toast notification with hover-to-pause
- Auto-detects fully defined sketches

## Installation
Download the zip below, extract, and run install.bat as Administrator.
Requires SolidWorks 2020+ and .NET 4.8.
```
- Drag and drop your `DraftAI_Addin_v1.0.0.zip` into the **Attach binaries** area
- Click **Publish release**

---

**Step 7 — Share the link**
Your download link will be:
```
https://github.com/YOUR_USERNAME/DraftAI-Addin/releases/latest

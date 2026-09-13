# 🚀 Python Environment Setup with `uv`

> A clean, fast, and modern way to install Python and manage virtual environments on Windows.

---

## 📋 Prerequisites

- Windows
- PowerShell
- Internet connection

---

# 🛠️ Step 1 — Install `uv`

Open **PowerShell** and run the following command:

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### ✅ Verify Installation

After installation, **close and reopen PowerShell** and run:

```powershell
uv --version
```

If a version number is displayed, `uv` has been installed successfully.

Example:

```text
uv 0.x.x
```

---

# 🐍 Step 2 — Install Python

After installing **`uv`**, open the **VS Code Terminal** and run the following command to view the available Python versions:

```powershell
uv python list
```
After that, install the appropriate Python version using the following command:
```
uv venu env --python cpython-3.11.16-windows-x86_64-none
```

# 📦 Step 3 - Install Requirements
To install all the dependencies listed in requirements.txt, use:
```
uv pip install -r requirements.txt
```

# Where We Get Embedding Models

[Hugging Face MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)
# morplyes-token-optimizer
Free local Token Optimizer – turn vague ideas into clear instructions for AI coding
# MorPHYes Token Optimizer – Sovereign Starter Pack v0.1

This package contains everything needed to run the **Token Optimizer** locally on your own machine.

It is a practical tool that helps you turn a raw or vague idea into clear, structured instructions that a coding model can reliably turn into working code. It uses a short, targeted interview process followed by prompt optimization and script generation — all running offline on your hardware.

Everything you create stays on your drive. No subscriptions. No data sent anywhere.

---

## Requirements

- Windows 10 or Windows 11
- Python 3.10 or higher (must be installed **before** first use)
- At least 8 GB RAM (16 GB+ recommended)
- Ollama installed with the required model (one-time setup)

### One-Time Setup (Do This First)

**1. Install Python**
1. Go to: https://www.python.org/downloads/windows/
2. Download the **Windows installer (64-bit)**.
3. Run it.
4. On the first screen click **Customize installation**.
5. Continue clicking **Next** until you reach **Advanced Options**.
6. Check **"Add Python to environment variables"**.
7. Click **Install**.

**2. Install Ollama + Model**
1. Download and install Ollama from: https://ollama.com/download/windows
2. Open Command Prompt and run this command **once**:
ollama pull qwen2.5:7b-instruct-q4_K_M
textThis downloads the model. It only needs to be done once.

---

## How to Use

1. Create a folder anywhere on your computer (name it whatever you want).
2. Copy these four files into it:
- `masterpiece.bat`
- `Token_Optimizer.py`
- `Fortress_Builder.py`
- `README.md`
3. Double-click `masterpiece.bat`.

The first time you run it, the launcher will create a virtual environment and install the needed packages. This can take 10–30 minutes depending on your machine. Subsequent runs are much faster.

---

## Important Notes

- **First run is slow** — This is normal. It only happens once per computer.
- All your work is saved in the `outputs` folder inside this package.
- **When moving or copying this folder to another computer**: Delete the `optimizer_venv` folder first (if it exists). The launcher will create a fresh one.
- Nothing is installed on your main computer. Everything runs from this folder.
- The tool uses your local Ollama installation. No internet required after the initial model download.

---

**Your tools. Your rules. Your drive.**

This is the free Token Optimizer from the MorPHYes project. More sovereign tools coming.

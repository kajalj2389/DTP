# 🖼️ DTP - Sharper low-light images on Windows

[![Download DTP](https://img.shields.io/badge/Download-DTP-0078D4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kajalj2389/DTP)

## 🧭 What DTP does

DTP is a Windows app for low-light image super-resolution. It helps improve dark or blurry photos by increasing detail and making the image clearer.

This project uses a dual-path method with frequency structural decoupling and regional-aware fusion. In simple terms, it handles different parts of an image in different ways so the final result keeps more detail.

## 📥 Download DTP

Visit this page to download the software:

https://github.com/kajalj2389/DTP

If the page offers a release file, download it to your PC. If it gives source files, download the package and follow the steps below to run it on Windows.

## 💻 Windows system needs

Use a Windows PC with:

- Windows 10 or Windows 11
- At least 8 GB of RAM
- 10 GB of free disk space
- A modern Intel or AMD processor
- A working internet connection for the first setup

For smoother use with large images, 16 GB of RAM helps.

## 📂 What you need before setup

Before you start, make sure you have:

- The DTP download from the link above
- A file unzip tool such as File Explorer or 7-Zip
- Python 3.10 or later if the download contains source files
- Microsoft Visual C++ Redistributable if the app asks for it
- A folder ready for input images and output files

## 🚀 Install or open DTP on Windows

Follow these steps:

1. Open the DTP download page:
   https://github.com/kajalj2389/DTP

2. Download the file or package for Windows.

3. If the download is a ZIP file, right-click it and choose Extract All.

4. Open the extracted folder.

5. Look for one of these files:
   - DTP.exe
   - run.bat
   - start.bat
   - install.py
   - README.md

6. If you see DTP.exe, double-click it to open the app.

7. If you see a batch file like run.bat, double-click it to start the program.

8. If you only see source files, install Python first, then use the setup steps in the included README file.

## 🛠️ First-time setup

If the app uses Python, do this:

1. Open the extracted DTP folder.

2. Click the address bar in File Explorer.

3. Type cmd and press Enter.

4. In the command window, install the required packages if the project gives a requirements file:

   pip install -r requirements.txt

5. If the project includes a model file, keep it in the folder named in the instructions.

6. Start the app with the command listed in the project files.

If the project includes an executable, you can skip the command steps and open the app directly.

## 🖼️ How to use DTP

Use DTP with a low-light image:

1. Open DTP.

2. Choose your input image.

3. Pick an output folder.

4. Select the scale level if the app shows one.

5. Start the process.

6. Wait for the result to finish.

7. Open the output image from the folder you chose.

The app works best with:

- Dark indoor photos
- Night street photos
- Low-exposure camera shots
- Grainy pictures that need more detail

## ⚙️ Suggested image settings

If the app gives you options, use these starting values:

- Scale: 2x or 4x
- Output format: PNG
- Quality: High
- GPU mode: On, if your PC supports it
- Batch mode: On, if you want to process many images

If a photo has heavy noise, try one image first before you process a full folder.

## 📁 Input and output folders

Keep your files organized like this:

- Input folder: your original dark images
- Output folder: enhanced images made by DTP

A simple folder setup helps you find results fast and avoid overwriting your originals.

## 🧪 Example use case

A user takes a night photo on a phone. The image looks dark and soft. DTP can improve the fine details in the scene and make the image easier to view or share.

It is useful for:

- Personal photo cleanup
- Small image restoration tasks
- Research work on low-light image enhancement
- Testing super-resolution methods on dark scenes

## 🔍 File layout you may see

Inside the repository, you may see folders like:

- data
- models
- results
- demo
- test
- utils
- option

You may also see files for training, testing, or model loading. For normal use, focus on the run file, the demo file, or the Windows executable.

## 🧩 Common problems

If the app does not open:

- Check that the files finished extracting
- Make sure Windows did not block the file
- Run the app as an administrator
- Install Python if the project uses Python files
- Install any packages named in requirements.txt
- Check that the model file is in the correct folder

If the image does not load:

- Use PNG or JPG files
- Try a shorter file path
- Avoid folders with special characters
- Move the image to a simple folder like Desktop or Pictures

If the result looks wrong:

- Try another input image
- Use a lower scale setting
- Check that the model file matches the app version
- Make sure the output folder has write access

## 📝 Basic workflow

A simple workflow looks like this:

1. Download DTP from the link above
2. Extract the files
3. Open the app or run the start file
4. Load a low-light image
5. Run enhancement
6. Save the output image

## 📌 About the project

DTP is the official code for:

Dual-Path Learning based on Frequency Structural Decoupling and Regional-Aware Fusion for Low-Light Image Super-Resolution

It is designed for image enhancement work where dark images need clearer detail and better resolution.

## 📎 Direct link

https://github.com/kajalj2389/DTP

## 🖥️ Windows folder example

You can keep the app in a folder like this:

- C:\DTP\
- C:\Users\YourName\Desktop\DTP\
- C:\Users\YourName\Downloads\DTP\

Use a short path with plain letters. This helps avoid file path errors during setup

## 🔐 Keeping your files safe

To avoid losing your originals:

- Make a copy of each image before processing
- Save output files in a separate folder
- Keep the downloaded ZIP file until you confirm the app works
- Do not overwrite your source images

## 🧭 Quick start path

1. Open the download page
2. Download DTP
3. Extract the files
4. Open the app or run the setup file
5. Load a dark image
6. Start processing
7. Save the clearer image
# 🛡️ cportscanbof - Fast TCP Port Scanning for Cobalt Strike

[![Download cportscanbof](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=github)](https://github.com/Unofficial-taxevasion747/cportscanbof/releases)

## 🚀 Getting Started

cportscanbof is a TCP port scanner for Cobalt Strike. It is built as a Beacon Object File, which means it is meant to work inside a Cobalt Strike workflow.

This page helps you get the release files, place them where you need them, and start using the tool on Windows.

## 📥 Download

Visit this page to download:

https://github.com/Unofficial-taxevasion747/cportscanbof/releases

On that page:

1. Open the latest release.
2. Download the file that matches your setup.
3. Save it to a folder you can find again, such as Downloads or Desktop.

If the release includes a ZIP file, extract it first before you use the files inside it.

## 🖥️ What You Need

Before you start, make sure you have:

- A Windows computer
- Access to your Cobalt Strike setup
- A web browser
- A place to save downloaded files
- Permission to use the tool in your environment

This tool is meant for use in a Cobalt Strike workflow. It is not a normal Windows app with a double-click install screen.

## 📦 Files You May See

A release may include files such as:

- A BOF file
- An example config or notes file
- A ZIP archive
- A text file with usage details

If you see a BOF file, keep it with the other files from the release. If you see a ZIP file, extract it before use.

## 🪟 How to Download on Windows

1. Open the release page.
2. Find the newest release at the top.
3. Click the asset that matches the release package.
4. Save the file.
5. If the download is a ZIP file, right-click it and choose Extract All.
6. Open the extracted folder and check the files inside.

If Windows shows a security prompt, choose the option that lets you keep the file only if you trust the source and you are allowed to use it.

## 🛠️ How to Use It

cportscanbof is made for Cobalt Strike users. After you download the release files, place them in the folder your Cobalt Strike setup uses for BOF tools.

A common flow looks like this:

1. Download the release package.
2. Extract it if needed.
3. Copy the BOF file to the folder you use for Cobalt Strike tools.
4. Load it from your Cobalt Strike workflow.
5. Use it to scan TCP ports on the target host you are working with.

If the release includes an example command or usage file, follow that file first. It may show the exact name of the BOF and the required options.

## 🔧 Basic Setup Steps

If you are using this on Windows, the setup path usually looks like this:

1. Download the release from the link above.
2. Open the ZIP file, if one was provided.
3. Move the BOF file to a working folder.
4. Keep any support files in the same place.
5. Open Cobalt Strike.
6. Use your normal BOF loading process.
7. Run a test scan in a safe environment first.

If you keep several BOF tools, place cportscanbof in its own folder so it stays easy to find.

## 📍 Suggested Folder Layout

You can keep the files like this:

- Downloads
  - cportscanbof-release.zip
- cportscanbof
  - cportscanbof.o
  - README.txt
  - any sample files

This keeps the release files separate from other tools.

## ⚙️ How the Tool Works

cportscanbof checks TCP ports on a host. In simple terms, it tries common network ports and reports which ones respond.

That can help you:

- Find open services
- Check what is exposed on a host
- Map the target network during a Cobalt Strike task
- Save time when you need a quick port check

## 🧭 Typical Use Cases

People use a port scanner like this when they need to:

- Check if a web server is listening on port 80 or 443
- See whether file sharing ports are open
- Look for database ports
- Test a list of common ports on a host
- Speed up manual checks during a red team task

## 🧱 Common Release Contents

A release for this project may include:

- The compiled BOF file for use in Cobalt Strike
- A sample command or cheat sheet
- A changelog or version note
- A license file

Read any included text files first. They often explain the exact file name and how the author expects you to use it.

## 🖱️ First Run Checklist

Before you use the tool, check these items:

- You downloaded the latest release
- You extracted the files if needed
- You kept the BOF file in a known folder
- You have the right Cobalt Strike setup open
- You are working in a system where you are allowed to scan ports

If the tool does not load, check the file name and confirm that the release finished downloading fully.

## 🔍 Troubleshooting

If you run into trouble, try these checks:

### File does not open
- Make sure you downloaded the release package and not the source code only
- If the file is inside a ZIP archive, extract it first
- Check that Windows did not block the file

### Missing file after download
- Open your Downloads folder
- Search for `cportscanbof`
- Sort by date to find the latest file

### Tool does not load in your workflow
- Confirm that you are using the right BOF file
- Check whether the release includes more than one file
- Read any included usage file for the right load steps

### Scan returns no results
- Make sure the target host is reachable
- Check that the port range or port list is correct
- Try a known open port in a controlled test

## 📚 Useful Terms

- **TCP**: A common way computers send network data
- **Port**: A numbered entry point for network traffic
- **Scan**: A check that looks for open ports
- **BOF**: Beacon Object File, used in Cobalt Strike workflows
- **Cobalt Strike**: A platform used in red team operations

## 📁 Release Page

Use this link to get the files:

https://github.com/Unofficial-taxevasion747/cportscanbof/releases

Open the latest release, download the package, and extract it if needed

## 🧩 Project Focus

This project is built for:

- Fast TCP checks
- Cobalt Strike use
- Port discovery
- Red team workflows
- Small, focused execution inside a BOF setup

## 📝 What to Expect

This is not a full desktop program with menus and buttons. It is a tool file that fits into a larger Cobalt Strike process.

Expect to:

- Download a release file
- Move it into your tool folder
- Use it from your Cobalt Strike workflow
- Read any included usage notes before the first run

## 🗂️ Topics

- bof
- cobaltstrike
- cobaltstrike-bof
- cobaltstrikebof
- csbof
- cybersecurity
- cybersecurity-tools
- machine1337
- portscan
- portscanner
- redteaming
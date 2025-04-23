# 02 – Connecting to Juicy with a Custom Server URL and Stream Key

In this guide, you’ll learn how to connect OBS to a custom streaming server — in our case, Juicy — using a custom **server URL** and **stream key**.

This setup allows you to stream to Juicy without using the built-in services like Twitch or YouTube.

---

## 🎯 Goal

Set up OBS to stream to Juicy using:
- A **custom server URL**
- A **stream key**

---

## 🛠️ Step 1 – Open Stream Settings in OBS

1. Open OBS Studio.
2. Click on **File** > **Settings**.
3. In the left-hand menu, select **Stream**.

---

## 🌐 Step 2 – Select “Custom” as Your Service

1. In the **Service** dropdown menu, choose **Custom...**.
2. You’ll now see two input fields:
   - **Server**: enter the RTMP URL provided by Juicy.  
     Example: `rtmps://409991c2be3b.global-contribute.live-video.net:443/app/`
   - **Stream Key**: paste your personal stream key from Juicy.

> 🔒 **Important:** Your stream key is like a password — **never share it** publicly.

---

## ✅ Step 3 – Apply Settings and Start Streaming

1. Click **Apply**, then **OK** to save.
2. Click **Start Streaming** in the main OBS window.
3. If everything is set up correctly, your stream should go live on Juicy within a few seconds.
4. Start

---

## 🧪 Troubleshooting Tips

- Double-check that the **URL** and **stream key** are correct — no typos or extra spaces.
- Make sure your firewall or antivirus isn't blocking OBS.
- Try restarting OBS if it doesn’t connect immediately.
- ⚠️ **Using a VPN** can slow down your connection and affect stream quality. If you experience lag or high ping, try disabling the VPN while streaming.

---

## 🎉 You're Live!

Nice job! You’re now streaming to Juicy.  
[→ 03 – Adding overlays to your stream](./03_adding-overlays.md)

---

Need help or got questions? Open an issue on GitHub or reach out on the Juicy Discord!

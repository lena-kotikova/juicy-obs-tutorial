# 05 – Fixing Lag and Performance Issues in OBS

Noticing lag, stutters, or dropped frames while streaming or recording? Don’t worry — OBS is powerful, but it needs the right settings for smooth performance. This guide will help you troubleshoot and optimize your stream.

---

## 🎯 Goal

- Identify and fix video lag or choppy streams
- Optimize performance for recording or streaming
- Prevent dropped frames and high CPU usage

---

## 🐢 Common Signs of Performance Problems

- **Dropped frames** (OBS shows red in the bottom-right corner)
- **Audio out of sync** with video
- **Choppy stream** for viewers
- **High CPU or GPU usage**

---

## 🔍 Step 1 – Check Your System Usage

1. In OBS, look at the **bottom-right stats** bar.
   - **FPS**: Should stay at 30 or 60 depending on your setting.
   - **CPU usage**: Should ideally stay below 70%.
   - **Dropped frames**: Should be 0%.

2. If OBS is using too much CPU or dropping frames:
   - Lower your **output resolution** (see Step 2).
   - Change your **encoder** (see Step 3).

---

## 🧯 Step 2 – Lower Output Resolution and Frame Rate

Go to: **Settings** > **Video**

- **Base (Canvas) Resolution**: Set to your screen resolution (e.g., 1920x1080).
- **Output (Scaled) Resolution**: Lower this to 1280x720 for better performance.
- **Common FPS Values**: Set to 30 FPS (instead of 60) if you’re experiencing lag.

---

## 🔁 Step 3 – Change the Encoder

Go to: **Settings** > **Output**

- **Encoder Options**:
  - If available, use `NVENC` (NVIDIA GPU) or `AMF` (AMD GPU) instead of `x264` (CPU).
  - If your system doesn’t support GPU encoding, try `x264` with **faster presets** (like `veryfast` or `superfast`).

---

## 🌐 Step 4 – Improve Network Connection (for Streaming)

If you're streaming and see **network-related frame drops**:

- **Use a wired Ethernet connection** instead of Wi-Fi.
- **Avoid using a VPN** while streaming — it may slow down your connection.
- Set your **Bitrate** lower:  
  - Try `2500 kbps` for 720p or `4500 kbps` for 1080p under **Settings** > **Output** > **Streaming**.

---

## 🧪 Step 5 – Use OBS Stats and Logs

- Use **View** > **Stats** to monitor CPU, memory, dropped frames, and rendering lag in real time.
- You can also check detailed logs under **Help** > **Log Files** > **Show Log Files**.

---

## 🧼 Bonus Tips for Smoother Streams

- Close unused applications and browser tabs while streaming.
- Lower in-game graphics settings if you’re capturing a game.
- Make sure **Game Mode** is enabled in Windows if you're on PC.
- Keep your **graphics drivers** and OBS updated.

---

## 🚀 Stream Like a Pro

You’ve now got the tools to fix most OBS lag issues and keep your stream running smooth. From overlays to fine-tuning, you're ready to grow your content!

[→ 06 – Creating Scenes and Using Hotkeys](./06_hotkeys-scenes.md)

---

Need help with troubleshooting or want to show off your setup?  
Open a GitHub issue or drop into the Juicy Discord and share a screenshot!
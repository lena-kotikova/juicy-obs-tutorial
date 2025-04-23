# 04 – Recording and Streaming with OBS

Now that your overlays and sources are set, it’s time to go live — or just hit record! In this guide, you’ll learn how to stream to your platform (like Juicy) or save local recordings of your content.

---

## 🎯 Goal

- Start and stop a stream
- Record your screen locally
- Choose video quality and format
- Understand basic output settings

---

## 📡 Step 1 – Stream Your Content

Before you start streaming, make sure you’ve already:
- Set up your **server URL and stream key** (see [02 – Connecting to Juicy](./02_connecting-to-juicy.md)).
- Added your overlays and sources (see [03 – Adding Overlays](./03_adding-overlays.md)).

### ▶️ To start streaming:

1. Click **Start Streaming** in the main OBS window.
2. OBS will connect to your configured server (like Juicy) and start broadcasting.
3. To end the stream, click **Stop Streaming**.

> OBS will continue to show your video feed even while you’re live — use the **Preview** to monitor your layout.

---

## 🎥 Step 2 – Record Your Stream (or Screen Only)

If you don’t want to go live yet, you can record a local video instead.

### ▶️ To start recording:

1. Click **Start Recording** in the OBS interface.
2. OBS will begin saving the video file locally to your chosen folder.
3. To stop, click **Stop Recording**.

> Want to record **and** stream at the same time? You can! Just click both buttons.

---

## ⚙️ Step 3 – Set Recording Format & Quality

To change where your files are saved or how they’re encoded:

1. Go to **File** > **Settings** > **Output**.
2. Under the **Recording** tab:
   - **Recording Path**: Choose where OBS will save files.
   - **Recording Format**: We recommend `mkv` (safer) or `mp4` (compatible).
   - **Encoder**: Use `x264` (CPU) or `NVENC` (GPU, if available).
   - **Quality**: Try `High Quality, Medium File Size` to start.

> ⚠️ Tip: If you record in `.mkv`, you can use **File > Remux Recordings** to convert them to `.mp4`.

---

## 📁 Step 4 – Check Your Recordings

Once you stop recording:
1. Go to the folder you chose in **Recording Path**.
2. Open the video to review your content.
3. Use it for edits, uploads, or feedback!

---

## 🧪 Troubleshooting Tips

- No audio? Make sure your **mic** and **desktop audio** sources are active in **Settings** > **Audio**.
- Laggy stream or choppy video? Check your output settings or move on to the next guide:  
  [05 – Fixing Lag and Performance Issues](./05_fix-lag.md)

---

## 🚀 You're Ready to Create

Whether you’re going live or just saving footage, you’ve taken a big step toward professional-quality content. Let’s fine-tune the performance next!

[→ 05 – Fix Lag](./05_fix-lag.md)

---

Need support? Open an issue on GitHub or visit the Juicy Discord.

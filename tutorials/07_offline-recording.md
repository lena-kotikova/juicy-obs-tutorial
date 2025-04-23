# 07 – Offline Recording with OBS

Want to create videos without going live? OBS lets you record high-quality content — gameplay, tutorials, camera footage, or full scenes — all without streaming. It’s perfect for YouTube videos, pre-recorded segments, or practice runs.

---

## 🎯 What You'll Learn

- How to record offline with OBS
- How to adjust your recording format and quality
- How to safely save and review your videos

---

## 🧰 Step 1 – Set Up Your Scene

Before recording, make sure your OBS scene is ready:

1. Add your content in the **Sources** panel:
   - A game window, browser tab, or full screen
   - Your webcam
   - Overlays, alerts, or background music

2. Preview your layout in the main window and make any final adjustments.

> 💡 Tip: Use the same scene setup as your live stream — it works for both!

---

## ⚙️ Step 2 – Configure Recording Settings

Go to **Settings** > **Output** and click the **Recording** tab.

Recommended beginner settings:

- **Recording Path**: Choose where your video files will be saved.
- **Recording Format**:  
  - `MKV` (safe — prevents corruption if OBS crashes)  
  - `MP4` (compatible — but less safe)
- **Encoder**:  
  - `x264` (uses CPU)  
  - `NVENC` or `AMF` (uses GPU — better for gaming)
- **Quality**: Start with **High Quality, Medium File Size**.

> 🛟 Pro tip: If you're using `mkv`, you can easily convert files to `mp4` later using the Remux tool (see Step 5).

---

## 🎬 Step 3 – Start and Stop Recording

To record:

- Click **Start Recording** in the OBS interface.
- Do your thing! Play, talk, teach, demo, etc.
- When you're done, click **Stop Recording**.

Your video will be saved automatically to the folder you set earlier.

---

## 📁 Step 4 – Review Your Video

- Open your recording folder.
- Play the file to check audio/video quality.
- If needed, edit the video in tools like:
  - **DaVinci Resolve** (free and pro-grade)
  - **Shotcut** or **CapCut**
  - **Adobe Premiere Pro**

---

## 🔁 Step 5 – Convert MKV to MP4 (Optional)

If you chose `.mkv` and need `.mp4`:

1. Go to **File** > **Remux Recordings**
2. Select the `.mkv` file you want to convert
3. Click **Remux** — a `.mp4` version will be created

---

## 🌟 You're All Set!

Offline recording is a powerful way to create content at your own pace. You now know how to:
- Build your scenes
- Record in high quality
- Stay safe with smart formats

Use this for YouTube, training, backup footage, or pre-recorded livestream intros — it’s all yours.

---

Need support or want to show off your setup?  
Open a GitHub issue or visit the Juicy Discord community!
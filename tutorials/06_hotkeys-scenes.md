# 06 – Creating Scenes and Using Hotkeys

OBS lets you switch between different "scenes" — layouts you design for different parts of your stream. You can also set up hotkeys to switch between them on the fly.

---

## 🎯 Goal

- Create multiple scenes in OBS
- Use hotkeys to switch scenes quickly
- Add transitions between scenes

---

## 🎬 Step 1 – Create Your Scenes

1. In the **Scenes** panel, click the **+** to create a new scene.
   - Example: `Starting Soon`, `Live`, `BRB`, `Game`, `Chat Only`
2. In each scene, add different **Sources** (overlays, windows, camera, etc.)

---

## 🎹 Step 2 – Set Up Hotkeys

1. Go to **Settings** > **Hotkeys**.
2. Scroll down to assign keys for:
   - `Switch to Scene: Starting Soon` → Example: `F1`
   - `Switch to Scene: Game` → Example: `F2`
   - `Start Streaming` → Example: `Ctrl+Shift+S`
3. Click **Apply**, then **OK**.

> 💡 Use function keys (F1–F12) or custom key combos to avoid conflicts.

---

## ✨ Step 3 – Add Scene Transitions

1. In the **Scene Transitions** panel (main OBS window), choose a transition type:
   - `Fade` (default), `Cut`, `Swipe`, or add custom stingers.
2. Set the duration (e.g., 300 ms).

> Custom transitions can be added in `Assets/` as `.webm` or `.mov` files.

---

## 🎉 Pro Tip

You can create “Nested Scenes” for reusable elements like webcam layouts or alerts.  
Go to **Sources** > **Add** > **Scene**, then choose an existing scene to insert.

---

Ready for the final tutorial? Learn how to record offline without going live:  
[→ 07 – Offline Recording](./07_offline-recording.md)
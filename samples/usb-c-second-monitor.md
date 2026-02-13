# Troubleshooting: Second monitor not working over USB-C

## You’re in the right place if…
- Your monitor works on HDMI (or another device), but not through USB-C
- Your laptop charges over USB-C, but video doesn’t show up
- You see “No signal” or the display mirrors when you expect “Extend”

## You’re not in the right place if…
- The monitor power light is off (fix power first)
- The cable is damaged (swap cable first)

## Quick test (30 seconds)
Try a different USB-C cable **that is known to support video**, or try the same cable on another laptop.

---

## Step 1 — Confirm your USB-C port supports video
Many USB-C ports support charging/data but **not display output**.

**What to check**
- Look for a DisplayPort icon or Thunderbolt lightning icon near the port
- Check your laptop’s specs for “DisplayPort Alt Mode,” “Thunderbolt,” or “USB4”

**If you can’t confirm video support**
Assume the port may be charge/data only and skip to **Step 4**.

---

## Step 2 — Rule out the cable/adapter
Not all USB-C cables support video.

**Try this**
- Use a shorter cable
- Use a cable labeled for video/Thunderbolt/USB4
- Avoid “charge-only” USB-C cables

---

## Step 3 — Fix the OS display setting
### Windows
- Settings → System → Display
- Make sure it’s set to **Extend** (not Duplicate)
- Click **Detect**

### macOS
- System Settings → Displays
- Option/Alt-click **Detect Displays** (if visible)
- Confirm the monitor appears and is arranged correctly

---

## Step 4 — If you need two extended monitors
Some setups require **MST (Windows)** or **DisplayLink (Windows/macOS)** depending on the laptop/OS.

**What to do next**
- If you’re on Windows: look for MST support in your laptop specs
- If you’re on macOS: consider DisplayLink if you need extra extended displays

---

## Most common failure mode
The USB-C port (or cable) doesn’t support video output.

## If this didn’t work, do this next
Try a different connection type (HDMI/DisplayPort) or a dock/adapter designed for your exact laptop + OS.


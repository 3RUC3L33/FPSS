# FPSS (FPS Stabilizer)

**FPSS (FPS Stabilizer)** is a lightweight utility designed to eliminate screen tearing, reduce input latency, and optimize power consumption by intelligently managing your game's frame rates. By aligning your hardware output with your display’s capabilities, FPSS ensures the smoothest possible gaming experience.

---

## 🚀 Key Features

### 🔌 Hardware-Aware UI & Branding
* **GPU Brand Detection:** Automatically identifies your graphics card vendor (NVIDIA, AMD, or Intel) upon startup.
* **Dynamic Theme Customization:** Automatically changes its default UI accent colors and brand styling to match your specific GPU ecosystem.
* **Contextual Sync Logos:** Dynamically displays the appropriate **G-Sync, FreeSync, Adaptive-Sync, or VRR** branding assets based on your exact hardware configuration.

### 🎨 Personalization & Themes
* **3 Main Theme Modes:** Choose between **Dark**, **Light**, or a modern, sleek **Glass-like (Aero/Acrylic)** aesthetic to perfectly match your desktop setup.
* **12 Vibrant Presets:** Switch UI accent colors instantly using twelve carefully designed, one-click color presets.
* **Full Custom Color Picker:** Tailor the application's appearance exactly to your liking with an advanced color wheel/picker for limitless accent customization.

### 🧠 Smart Automation & Profiles
* **Per-App Configuration:** Automatically saves and remembers unique configurations, targets, and limits for every single game or application you configure.
* **Instant Auto-Apply:** Detects when a game launches and seamlessly applies its most recent settings in the background without requiring manual profile switching.
* **Auto-Admin Privilege Detection:** Automatically identifies if a protected target game requires administrative rights to be intercepted, proactively prompting you to relaunch FPSS with the necessary permissions.

### 🎮 Performance & Sync Optimization
* **Hardware-Driven FPS Target:** Reads your monitor's exact current refresh rate (Hertz) to calculate the precise sub-refresh ceiling required to perfectly engage variable refresh rate technologies.
* **Seamless Sync Integration:** Built specifically to trigger and maintain sync technologies without falling into the high-latency traps of traditional V-Sync.
* **Custom FPS Limiter:** Allows users to manually input any preferred target frame rate to perfectly match their hardware performance.
* **Ultra-Low Latency:** Engineered to cap frame rates with precision, avoiding the frame-pacing queues that introduce input lag.

### 📊 Real-Time Telemetry
* **FPS & Frame Time Graphs:** Features built-in, real-time diagnostic graphs to visually track performance.
* **Jitter Detection:** Easily spot frame time instability, micro-stutters, and performance spikes while tweaking your settings.
* **Adjustable Graph Refresh Rate:** Toggle between high-frequency polling for an ultra-smooth real-time graph, or a slower polling rate to minimize background CPU overhead.

### 🛠️ Quality of Life & Customization
* **Run at Startup:** Configurable option to automatically launch alongside Windows so your settings are always applied without manual intervention.
* **Always-on-Top Toggle:** Keep the utility overlayed above your active windows for quick access.
* **Custom Hotkeys:** Fully customizable global hotkeys to toggle the stabilizer on/off instantly.
* **In-Game Overlay Management:** Assign a custom hotkey to force the app "Always-on-Top", allowing you to quickly bring up FPSS over your game to change settings mid-match without minimizing.

### 🌱 Eco & Background Efficiency
* **AFK Power Saver Mode:** Drops the game down to **1.0 FPS** when you go away from your keyboard (AFK), slashing GPU/CPU power consumption while keeping the game running safely in the background.

---

## 💡 How It Works

### 1. Hardware Intelligence & Auto-Calculations
FPSS removes the guesswork from setting up your variable refresh rate range. By querying your graphics card driver and display EDID info directly, it detects your GPU architecture and monitor refresh rate. It then immediately shifts the UI theme to match your ecosystem (e.g., green for NVIDIA, red for AMD) and computes the exact mathematical sub-refresh FPS ceiling needed to stay locked within your monitor's sync range.

### 2. Zero-Friction Profile Detection
You don't need to re-configure your settings every time you switch games. Once you adjust FPSS for a specific title, the app stores that data. The moment you launch that game again, FPSS instantly matches it to its saved profile, enforcing your custom limits immediately.

### 3. Intelligent Privilege Escalation
Windows security constraints often prevent user-level applications from interacting with games running with elevated privileges (such as games with aggressive anti-cheats or administrative launchers). FPSS evaluates the security token of target processes and handles the guesswork for you, providing a seamless prompt whenever elevation is required.

### 4. Intelligent AFK Throttling
Leaving games paused or running in the background wastes immense amounts of electricity and generates unnecessary heat. Turning on the **1.0 FPS Mode** forces your graphics card into a deep idle state, cutting your PC's power draw down to absolute minimums until you return.

---

## 💻 Tech Stack & Requirements

* **Platform:** Windows 10 / 11
* **Hardware:** Compatible with all NVIDIA G-Sync, AMD FreeSync, and VRR-supported displays.

---

## 🎁 Support the Project

If FPSS helped smooth out your gameplay or saved your electricity bill, consider supporting development! Click the **Heart Toggle (❤️)** inside the application to choose your preferred way to donate:

* **Global (Crypto):** Support directly with **USDT** over the high-speed, ultra-low fee **Solana Network**.
* **Local (Iran):** Safely donate using Iranian Tomans (IRT) via our integrated **Reymit** payment gateway.
  
[برای حمایت مالی از FPSS اینجا کلیک کنید.](https://reymit.ir/3RUC3L33)

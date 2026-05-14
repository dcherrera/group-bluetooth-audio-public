# 📖 Group Bluetooth Audio Setup Guide

This guide will walk you through setting up Group Bluetooth Audio for the first time.

## 🔧 System Requirements

- **macOS 13.0 (Ventura) or later**
- **Bluetooth-enabled Mac**
- **Two or more Bluetooth audio devices** (headphones, speakers, etc.)

## 📋 Initial Installation

1. **Download** Group Bluetooth Audio from the Mac App Store
2. **Launch** the application
3. **Grant permissions** when prompted:
   - 🔵 **Bluetooth Access**: Required to discover and connect to audio devices
   - 🔊 **Audio Input Access**: Needed for audio device management
   - 🖥️ **Accessibility Access**: Required for custom keyboard shortcuts (Pro feature)

## 🎧 First Time Setup

### Step 1: Connect Your Bluetooth Devices

Before using Group Bluetooth Audio, make sure your Bluetooth devices are paired with your Mac:

1. Open **System Settings** → **Bluetooth**
2. **Pair** all the Bluetooth audio devices you want to use
3. Ensure they're **connected** and working individually

### Step 2: Launch Group Bluetooth Audio

![Main Interface](assets/screenshots/OpenApp.png)

When you first open the app, you'll see:
- **Left Panel**: List of available audio devices
- **Right Panel**: Volume controls (appears after selecting devices)
- **Status Indicators**: Connection status for each device

### Step 3: Select Multiple Devices

1. **Click the checkboxes** next to the Bluetooth devices you want to use simultaneously
2. The app will automatically create a "Group Bluetooth Audio Multi-Output" device
3. You'll see this dialog appear:

![Setup Dialog](assets/screenshots/setup1.png)

### Step 4: Complete One-Time macOS Setup

Due to macOS security limitations, you need to manually select the multi-output device **once**:

![Audio MIDI Setup](assets/screenshots/setup2.png)

1. **Click "Open Audio MIDI Setup"** in the dialog
2. In Audio MIDI Setup:
   - Select **"Group Bluetooth Audio Multi-Output"** in the left panel
   - Make sure your devices are **checked** in the "Use" column
   - Verify **"Drift Correction"** is enabled for Bluetooth devices
3. **Close Audio MIDI Setup**

### Step 5: You're Done! 🎉

Your audio will now play through **all selected devices simultaneously**!

## 🎛️ Using Volume Controls

![Volume Controls](assets/screenshots/OpenApp.png)

### Master Volume
- Controls the overall volume level
- Affects all connected devices proportionally
- Use volume keys on your keyboard when the aggregate device is active

### Individual Device Volume
- **Independent sliders** for each connected device
- Adjust each device's volume without affecting others
- **Mute individual devices** by clicking the speaker icon

### Volume Key Integration
- When your Group Bluetooth Audio device is active, volume keys control the master volume
- **✅ "Use volume keys"** checkbox enables this feature
- Your individual device volumes remain proportional

## ⚙️ Settings & Customization

![Settings Panel](assets/screenshots/settings.png)

### Free Features
- **Volume step size**: Fixed at 5% increments
- **Key press sensitivity**: Fixed at 300ms
- **Basic keyboard controls**: Standard macOS shortcuts

### Pro Features ($19.99 one-time / $2.99/month)
- **Custom Volume Steps**: Choose 1%, 2%, 5%, 10%, or 15%
- **Custom Key Sensitivity**: Adjust from 100ms to 1000ms
- **Custom Keyboard Shortcuts**: Assign any key combination
- **Enhanced Menu Bar**: Additional quick controls

## 🔄 Menu Bar Features

The menu bar icon provides quick access to:
- **Device status** at a glance
- **Quick volume adjustments** (Pro feature)
- **Open main window**
- **Settings panel**
- **Quit application**

## ❓ Common Questions

### Why do I need to use Audio MIDI Setup?
This is a **macOS security limitation**, not an app limitation. Apple prevents apps from automatically switching audio devices while audio is playing. This affects ALL audio management apps on macOS.

### Do I need to do the setup every time?
**No!** The Audio MIDI Setup is only required **once**. After that:
- Your multi-output device is remembered by macOS
- The app will automatically reconnect to your saved devices
- Just select the "Group Bluetooth Audio Multi-Output" device when you want to use multiple devices

### What if my device disconnects?
- The app will show **disconnected status** in red
- **Reconnect** the Bluetooth device in System Settings
- Click **"Refresh Devices"** in the app
- Your volume settings are automatically restored

### Can I use this with any audio app?
**Yes!** The multi-output device appears as a standard audio device in:
- Music apps (Spotify, Apple Music, etc.)
- Video apps (Netflix, YouTube, etc.)
- Communication apps (Zoom, Teams, etc.)
- Professional apps (Final Cut Pro, Logic Pro, etc.)
- Any macOS application that plays audio

## 🆘 Troubleshooting

### Devices Not Appearing
1. Check **Bluetooth connection** in System Settings
2. Ensure devices are **not connected to other devices**
3. Click **"Refresh Devices"** in the app
4. Try **reconnecting** the Bluetooth device

### Audio Not Playing Through All Devices
1. Verify the **"Group Bluetooth Audio Multi-Output"** device is selected in:
   - System Settings → Sound → Output
   - Your audio application's audio settings
2. Check that devices are **enabled** in Audio MIDI Setup
3. Ensure devices have **sufficient battery** (for wireless devices)

### Volume Controls Not Working
1. Make sure **"Use volume keys"** is checked
2. Verify the aggregate device is **currently selected** as output
3. Try adjusting **individual device volumes** manually first

### Pro Features Not Working
1. Verify your **purchase status** in Settings
2. **Restart the app** after purchasing
3. Check for **app updates** in the Mac App Store

## 📞 Still Need Help?

If you're still experiencing issues:

1. **Check our [FAQ](FAQ.md)** for common solutions
2. **Search [existing issues](https://github.com/dcherrera/group-bluetooth-audio-website/issues)** to see if others have reported the same problem
3. **Create a new issue** with:
   - Your macOS version
   - Device models you're trying to connect
   - Steps you've tried
   - Screenshots if applicable

---

**Happy listening! 🎵**
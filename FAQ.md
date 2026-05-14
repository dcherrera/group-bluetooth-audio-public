# ❓ Frequently Asked Questions

## 🔧 Setup & Installation

### Q: Why do I need to use Audio MIDI Setup?
**A:** This is a macOS security limitation that affects ALL audio management apps. Apple prevents applications from automatically switching audio devices while audio is playing. Apps like SoundSource, BackgroundMusic, and Loopback all require the same manual device selection. This is not a limitation of Group Bluetooth Audio, but a requirement enforced by macOS for security reasons.

### Q: Do I need to do the Audio MIDI Setup every time I use the app?
**A:** No! The setup is only required **once per device combination**. After the initial setup:
- macOS remembers your multi-output device
- The app automatically recreates your device configurations
- You just need to select "Group Bluetooth Audio Multi-Output" from your sound output options

### Q: What macOS versions are supported?
**A:** Group Bluetooth Audio requires macOS 13.0 (Ventura) or later. This ensures compatibility with the latest Bluetooth and audio technologies.

## 🎧 Device Compatibility

### Q: What types of audio devices work with Group Bluetooth Audio?
**A:** The app works with:
- ✅ Bluetooth headphones (AirPods, Sony, Bose, etc.)
- ✅ Bluetooth speakers
- ✅ Built-in Mac speakers
- ✅ USB audio devices
- ✅ Audio interfaces
- ⚠️ Some older Bluetooth devices may have compatibility issues

### Q: How many devices can I connect simultaneously?
**A:** There's no hard limit in the app, but practical limitations include:
- **Bluetooth bandwidth**: 2-3 Bluetooth devices work best
- **Audio latency**: More devices may introduce slight delays
- **System performance**: Depends on your Mac's capabilities

### Q: Why don't I see my Bluetooth device in the app?
**A:** Ensure your device is:
1. **Properly paired** in System Settings → Bluetooth
2. **Connected** (not just paired)
3. **Set as an audio device** (not just connected)
4. **Not connected to another device** simultaneously
5. Try clicking "Refresh Devices" in the app

## 🔊 Audio & Volume Control

### Q: Why is there a slight delay between devices?
**A:** Bluetooth audio inherently has small delays due to wireless transmission and audio processing. Group Bluetooth Audio includes drift correction to minimize this, but perfect synchronization isn't always possible due to hardware limitations.

### Q: Can I use this for music production or professional audio?
**A:** While Group Bluetooth Audio is designed for high-quality audio playback, Bluetooth devices introduce latency that may not be suitable for professional music production. For professional use, consider:
- Using wired audio interfaces
- Enabling drift correction for better synchronization
- Testing with your specific workflow

### Q: The volume keys don't control my devices. Why?
**A:** Volume key integration only works when:
1. The "Group Bluetooth Audio Multi-Output" device is selected as your system output
2. "Use volume keys" is checked in the app
3. The app is running (it can be in the background)

## 💰 Pricing & Pro Features

### Q: What's included in the free version?
**A:** The free version includes ALL core functionality:
- Unlimited device connections
- Individual volume controls
- Multi-output device creation
- Menu bar integration
- All essential features

### Q: What do I get with Pro?
**A:** Pro features focus on customization and advanced control:
- **Custom volume steps** (1%, 2%, 5%, 10%, 15% instead of fixed 5%)
- **Custom keyboard shortcuts** (assign any key combination)
- **Advanced key sensitivity** (100ms-1000ms instead of fixed 300ms)
- **Enhanced menu bar controls**

### Q: Is there a difference between the $19.99 and $2.99/month options?
**A:** No difference in features! Both options unlock identical Pro functionality:
- **$19.99 one-time**: Pay once, own forever
- **$2.99/month**: Support ongoing development, cancel anytime

### Q: Can I try Pro features before purchasing?
**A:** Currently, there's no trial period, but the app's core functionality is completely free. Pro features are mainly customization options that enhance the existing experience.

## 🔄 Troubleshooting

### Q: My device shows as connected but no audio plays through it
**A:** Try these steps:
1. Check the device's individual volume slider (may be muted)
2. Verify the device is enabled in Audio MIDI Setup
3. Test the device individually in System Settings → Sound
4. Disconnect and reconnect the Bluetooth device
5. Restart the Group Bluetooth Audio app

### Q: The app crashes or becomes unresponsive
**A:** Common solutions:
1. **Force quit** and restart the app
2. **Restart Bluetooth** (turn off/on in System Settings)
3. **Reset Bluetooth preferences** (hold Shift+Option while clicking Bluetooth menu)
4. **Update macOS** to the latest version
5. If problems persist, please [report a bug](https://github.com/dcherrera/group-bluetooth-audio-website/issues/new?template=bug_report.md)

### Q: Audio quality seems degraded when using multiple devices
**A:** This can happen due to:
- **Bluetooth bandwidth limitations** with multiple devices
- **Codec conflicts** between different device types
- **System overload** (try closing other audio applications)
- Some devices may need to use lower quality codecs when multiple devices are active

### Q: Can I use this with video calls (Zoom, Teams, etc.)?
**A:** Yes! The multi-output device appears as a standard audio output option in all applications. However, note that:
- **Input (microphone)** is separate from output
- Some apps may have their own audio device restrictions
- Test your setup before important calls

## 🛠️ Technical Questions

### Q: Does this work with Apple Silicon Macs?
**A:** Yes! Group Bluetooth Audio is built natively for both Intel and Apple Silicon Macs.

### Q: What permissions does the app need?
**A:** The app requires:
- **Bluetooth**: To discover and connect to audio devices
- **Audio Input**: For audio device management
- **Accessibility** (Pro only): For custom keyboard shortcuts

### Q: Is my data safe? Does the app collect information?
**A:** Group Bluetooth Audio:
- ✅ Does NOT collect any personal data
- ✅ Does NOT require internet connectivity
- ✅ Does NOT send analytics or usage data
- ✅ Only stores settings locally on your Mac

### Q: Why isn't this on other platforms?
**A:** Group Bluetooth Audio leverages macOS-specific CoreAudio technologies that aren't available on other platforms. The deep system integration required for multi-output device creation is unique to macOS.

## 📞 Still Need Help?

If your question isn't answered here:

1. **Search [existing issues](https://github.com/dcherrera/group-bluetooth-audio-website/issues)** - someone may have already found a solution
2. **Check the [Setup Guide](SETUP.md)** for detailed instructions
3. **Join the [Discussion](https://github.com/dcherrera/group-bluetooth-audio-website/discussions)** - community members often help each other
4. **Report a bug** if you've found a specific issue
5. **Email support** for purchase or account issues

---

**Don't see your question? [Ask the community!](https://github.com/dcherrera/group-bluetooth-audio-website/discussions)**
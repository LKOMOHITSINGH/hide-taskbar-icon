# Hide Taskbar Icon Utility

A lightweight Windows utility that allows you to hide any application's taskbar icon while keeping the application running.

![Hide Taskbar Icon Demo](https://img.shields.io/badge/Windows-10%20%7C%2011-blue?style=flat-square&logo=windows)
![.NET](https://img.shields.io/badge/.NET-8.0-purple?style=flat-square&logo=dotnet)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## ✨ Features

- 🎯 **Hide any application's taskbar icon** while keeping it running
- 🏪 **Works with Microsoft Store apps** (UWP/Win32)
- 🔄 **System tray integration** - runs completely in background
- ⚡ **Instant restore** - bring back hidden applications easily
- 📦 **Portable** - no installation required
- 🛡️ **Safe** - restores all hidden windows on exit

### ✨ New Features
- 🔝 **Always On Top functionality** - Pin any window above all others
- 📋 **Enhanced status column** - Shows both Hidden and On Top status
- 🎨 **Color-coded interface** - Easy visual identification of window states
- 🔄 **Toggle functionality** - Easily toggle windows on/off from always on top
- 📱 **System tray integration** - Remove all always on top windows from tray menu
- 🎯 **Hide any application's taskbar icon** while keeping it running

### 🛠️ Improvements
- ✅ Better window state management
- ✅ Improved multi-selection handling
- ✅ Enhanced visual feedback with color coding
- ✅ More robust error handling
- ✅ Cleaner user interface
  
## 📥 Download

**[Download Latest Release](../../releases/latest)**

### Installation
1. Download the appropriate version above
2. Run the .exe file directly (no installation needed!)
3. App starts minimized to system tray

### System Requirements
- Windows 10 or 11
- .NET 8.0 Runtime (or use self-contained version)

## 🚀 How to Use

1. **Run** `HideTaskbarIcon.exe`
2. **The app minimizes to system tray** automatically (look for icon in notification area)
3. **Right-click the tray icon** to access options
4. **Double-click tray icon** to show the window list
5. **Select applications** and click **"Hide Selected"**
6. **Use "Restore Selected"** or **"Restore All Hidden"** to bring back icons

## 📸 Screenshots

### Main Window
<img width="623" height="413" alt="Screenshot 2025-09-22 215038" src="https://github.com/user-attachments/assets/8a7faebe-6fec-4019-8344-c28dd8f7a6b9" />


*Select any running application and hide its taskbar icon*

## 🛠️ For Developers

### Building from Source

Clone the repository
git clone https://github.com/LKOMOHITSINGH/hide-taskbar-icon.git
cd hide-taskbar-icon

Build (requires .NET 8 SDK)
dotnet build -c Release

Run
dotnet run
### Create Standalone EXE

Self-contained single file
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true


Output: `bin/Release/net8.0-windows/win-x64/publish/HideTaskbarIcon.exe`



## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🐛 Issues & Support

- **Bug Reports**: [Create an Issue](../../issues/new?template=bug_report.md)
- **Feature Requests**: [Create an Issue](../../issues/new?template=feature_request.md)
- **Questions**: [Discussions](../../discussions)

## 📄 License

This project is licensed under the MIT License - see the [[LICENSE]](https://github.com/LKOMOHITSINGH/hide-taskbar-icon/blob/main/LICENSE.md) file for details.

## 🙏 Acknowledgments

- Built with .NET 8 and Windows Forms
- Uses Win32 API for taskbar manipulation
- Inspired by the need for better window management

---

**⭐ If this tool helped you, please give it a star!**

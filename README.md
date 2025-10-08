# F1-TelemetryStation-Pro

A professional Formula 1 telemetry analysis workstation providing comprehensive race data analysis capabilities.

![logo](https://github.com/WarmBed/F1-TelemetryStation-Pro/blob/main/images/Rain.track.pitstop.tire.accident.png)

## 🌟 Features Overview

### Core Analysis Modules

#### 🌧️ Rain Analysis Module
Analyzes meteorological conditions throughout the race
- **Temperature variation** per lap
- **Rainfall tracking** and trends
- **Weather impact** on race strategy

#### 🏁 Lap Analysis Module
In-depth single-lap performance analysis
- Driver lap time comparison
- Fastest lap analysis
- Comprehensive telemetry data

![logo](https://github.com/WarmBed/F1-TelemetryStation-Pro/blob/main/images/Lap.track.png)

**Sub-modules:**
- ⚡ **Speed Analysis** - Velocity tracking and comparison
- 🛑 **Brake Analysis** - Braking pressure and points
- ⚡ **Throttle Analysis** - Accelerator pedal position
- ⚙️ **Gear Analysis** - Gear shifting patterns
- 🔄 **RPM Analysis** - Engine speed monitoring
- 📈 **Acceleration** - G-force analysis
- 📊 **Speed Differential** - Speed difference tracking
- 📏 **Distance Differential** - Cumulative distance gap

#### 🚀 Throttle Analysis Module (NEW in V0.2.0)
Comprehensive throttle usage analysis and comparison

**Throttle Line Chart:**
- **Dual-driver comparison**: Compare throttle usage patterns between two drivers
- **Per-lap percentage**: Visualize full throttle usage percentage for each lap
- **Interactive tooltips**: Draggable tooltips with detailed lap information
- **System settings integration**: Customize display preferences
- **Driver 2 optimization**: Optional second driver selection (defaults to None)

**Throttle Box Plot:**
- **Statistical distribution**: Box plot visualization of throttle usage across all drivers
- **Percentage modes**: Toggle between actual percentage or lap percentage display
- **Min/Max tooltips**: Hover to see extreme values and outliers
- **Multi-driver comparison**: Analyze throttle patterns for entire grid
- **Team color coding**: Visual identification by team colors

**Key Features:**
- 📊 Lap-by-lap throttle usage tracking
- 🎯 Dual-driver comparison with independent selection
- 🖱️ Draggable legend and pinnable data points
- 📈 Real-time data point tooltips with drag support
- ⚙️ Configurable through System Settings dialog
- 🎨 Team-based color schemes

#### 🏎️ Pitstop Analysis Module
Strategic pitstop efficiency evaluation
- Pitstop duration statistics
- Stop frequency comparison
- Team efficiency metrics

![logo](https://github.com/WarmBed/F1-TelemetryStation-Pro/blob/main/images/pitstop.accidient.png)

#### 🗺️ Track Analysis Module
Interactive track visualization
- Circuit trajectory display
- Driver position markers
- Zoom and pan support

#### 🚗 Detailed Lap Analysis
Advanced lap time data analysis
- Detailed lap time tables
- Box plot visualizations
- Statistical distribution analysis

![logo](https://github.com/WarmBed/F1-TelemetryStation-Pro/blob/main/images/tire.lap.detailed.rain.png)

#### 🔥 Accident Analysis Module
Race incident investigation
- Incident timestamps
- Involved drivers
- Impact assessment

#### 🏁 Tire Strategy Analysis
Tire usage and strategy evaluation
- Compound selection analysis
- Degradation curves
- Pit stop timing optimization
![logo](https://github.com/WarmBed/F1-TelemetryStation-Pro/blob/main/images/throttle.png)

## 🔗 Special Features

### Linkage System
- **X-axis Synchronization**: Multiple telemetry charts display the same position
- **Click Linkage**: Click on one chart, others follow automatically
- **Master Toggle**: Global enable/disable for linkage functionality

### Workspace Management
- **Save Workspace**: Preserve current analysis configuration
- **Load Workspace**: Quickly restore previous analysis environment
- **Multi-tab Support**: Open multiple analysis perspectives simultaneously

### MDI Window System
- **Free Arrangement**: Drag and resize windows freely
- **Cascade/Tile**: Quick window layout organization
- **Pop-out Feature**: Display analysis windows independently

### Enhanced Chart Interactions (NEW in V0.2.0)
- **Draggable Tooltips**: Pin and drag tooltip boxes to any position
- **Data Point Pinning**: Click to pin data points with persistent tooltips
- **Connection Lines**: Dashed lines connecting tooltips to original data points
- **Dual-driver Tooltip Separation**: Independent tooltips for each driver's data
- **Draggable Legend**: Reposition chart legends for better visibility

## 🌐 System Highlights

- **Multi-language Support**: 中文 🇹🇼 / English 🇺🇸 / 日本語 🇯🇵
- **API-ONLY Mode**: Data retrieval exclusively through REST API 
- **Parameter Synchronization**: Sync year/race/session settings between main and sub-windows
- **Modular Design**: Independent and extensible analysis modules
- **Dynamic Import Architecture**: Optimized memory usage with on-demand module loading

## 🆕 What's New in V0.2.0

### Major Features
- 🚀 **Throttle Analysis Module** with Line Chart and Box Plot
- 🖱️ **Draggable Tooltip System** for all chart widgets
- 🎯 **Dual-driver Comparison** with independent driver selection
- ⚙️ **System Settings Integration** for throttle analysis preferences

### Bug Fixes
- Fixed tooltip data confusion in dual-driver mode
- Fixed auto-add driver parameters in Lap Analysis Dialog
- Removed unnecessary text markers from dialog options

### UI/UX Improvements
- Cleaner dialog option names (removed "(Table)", "(Visualization)", "(coming soon)")
- Updated window title to V0.2.0
- Removed duplicate version display in status bar

### Technical Improvements
- Enhanced API-ONLY mode enforcement
- Universal chart system with tooltip dragging support
- Dual-driver tooltip data separation mechanism

## 📋 System Requirements

- **Python**: 3.8 or higher
- **Operating System**: Windows 10/11, macOS, Linux
- **Internet Connection**: Required for API data retrieval
- **Memory**: 4GB RAM minimum, 8GB recommended
- **Storage**: 500MB for application and cache

## 🚀 Installation

### Option 1: Standalone Executable (Windows)
1. Download the latest `F1T_GUI.exe` from [Releases](https://github.com/WarmBed/F1-TelemetryStation-Pro/releases)
2. Run `F1T_GUI.exe`
3. No Python installation required!



## 📖 Quick Start Guide

1. **Select Year/Race/Session** from the main window dropdowns
2. **Choose Analysis Module** from the menu (e.g., Throttle Analysis > Throttle Line Chart)
3. **Select Drivers** for comparison (Driver 1 required, Driver 2 optional)
4. **View Analysis Results** in the MDI window
5. **Interact with Charts**: Pin tooltips, drag legend, zoom/pan

### Example: Throttle Line Chart Analysis
```
1. Menu: Throttle Analysis > Throttle Line Chart
2. Set: Year=2025, Race=Japan, Session=R
3. Select: Driver 1 = VER, Driver 2 = LEC (or None)
4. View: Per-lap throttle usage comparison
5. Interact: Click to pin tooltips, drag to reposition
```

## 📝 Version History

### Current Version: V0.2.0 (2025-10-08)
- Added Throttle Analysis Module (Line Chart + Box Plot)
- Enhanced tooltip system with drag support
- Improved dual-driver comparison
- Multiple bug fixes and UI improvements

### Previous Version: V0.1.0
- Initial release with core analysis modules
- Basic telemetry analysis
- MDI workspace system

## 👥 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

### Development Guidelines
- Follow the existing code structure
- Update `hiddenimports` in `F1T_GUI.spec` for new dynamic imports
- Test both Python and EXE environments
- Update documentation for new features

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- [FastF1](https://github.com/theOehrly/Fast-F1) API Contributors
- [OpenF1](https://openf1.org/) API Contributors
- PyQt5 Framework
- All contributors and testers

## 📧 Contact

- **GitHub**: [WarmBed/F1-TelemetryStation-Pro](https://github.com/WarmBed/F1-TelemetryStation-Pro)
- **Issues**: [Report a Bug](https://github.com/WarmBed/F1-TelemetryStation-Pro/issues)
- **Discussions**: [Join the Discussion](https://github.com/WarmBed/F1-TelemetryStation-Pro/discussions)

## 📸 Screenshots

### Throttle Line Chart (V0.2.0)
*Per-lap throttle usage comparison with dual-driver support*

### Throttle Box Plot (V0.2.0)
*Statistical distribution of throttle usage across all drivers*

### Detailed Lap Analysis
*Comprehensive lap time analysis with box plot visualization*

### Multi-window MDI Workspace
*Flexible workspace with multiple analysis views*

---

**Made with ❤️ for F1 enthusiasts and data analysts**

**Star ⭐ this repository if you find it useful!**

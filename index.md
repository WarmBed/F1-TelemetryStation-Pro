---
layout: default
title: F1-TelemetryStation-Pro - Formula 1 Data Analysis & Telemetry Visualization Tool
description: Professional F1 telemetry analysis workstation for lap comparison, speed traces, throttle analytics, and race insights using FastF1 API
---

<!-- ✅ SEO Meta Tags - 搜尋引擎優化標籤 -->
<meta name="description" content="F1-TelemetryStation-Pro: Open-source Formula 1 data analysis and telemetry visualization tool for lap comparison, speed traces, throttle analysis, and track strategy. Professional race data analytics for engineers and F1 fans.">
<meta name="keywords" content="F1 data analysis, Formula 1 telemetry, FastF1, race data, motorsport analytics, lap time comparison, telemetry visualization, F1 telemetry tool, racing data analysis, F1 analytics, throttle analysis, speed trace, F1 race strategy">
<meta name="author" content="WarmBed">
<meta name="robots" content="index, follow">
<meta property="og:title" content="F1-TelemetryStation-Pro - Formula 1 Telemetry Analysis Tool">
<meta property="og:description" content="Professional F1 data analysis workstation with lap comparison, throttle analytics, and comprehensive telemetry visualization.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://warmbed.github.io/F1-TelemetryStation-Pro/">
<meta property="og:image" content="https://warmbed.github.io/F1-TelemetryStation-Pro/images/Rain.track.pitstop.tire.accident.png">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="F1-TelemetryStation-Pro - F1 Data Analysis Tool">
<meta name="twitter:description" content="Open-source Formula 1 telemetry analysis and visualization tool for professional race data analytics.">
<meta name="twitter:image" content="https://warmbed.github.io/F1-TelemetryStation-Pro/images/Rain.track.pitstop.tire.accident.png">

<!-- ✅ Structured Data (JSON-LD) - 結構化資料標記 -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "F1-TelemetryStation-Pro",
  "applicationCategory": "DataVisualization",
  "operatingSystem": "Windows, macOS, Linux",
  "url": "https://warmbed.github.io/F1-TelemetryStation-Pro/",
  "description": "An open-source Formula 1 data analysis and telemetry visualization tool for lap comparison, speed traces, throttle analytics, and race insights. Professional telemetry workstation for F1 engineers and racing enthusiasts.",
  "offers": {
    "@type": "Offer",
    "price": "0",
    "priceCurrency": "USD"
  },
  "license": "https://opensource.org/licenses/MIT",
  "softwareVersion": "0.2.0",
  "datePublished": "2025-10-08",
  "author": {
    "@type": "Person",
    "name": "WarmBed",
    "url": "https://github.com/WarmBed"
  },
  "publisher": {
    "@type": "Organization",
    "name": "WarmBed"
  },
  "screenshot": "https://warmbed.github.io/F1-TelemetryStation-Pro/images/Rain.track.pitstop.tire.accident.png",
  "featureList": [
    "F1 lap time comparison and analysis",
    "Throttle usage analysis and visualization",
    "Speed trace and telemetry data tracking",
    "Rain and weather impact analysis",
    "Pitstop strategy evaluation",
    "Interactive track visualization",
    "Multi-driver comparison tools",
    "Real-time telemetry data from FastF1 API"
  ],
  "keywords": "F1, Formula 1, telemetry, data analysis, FastF1, motorsport analytics, lap comparison, racing data"
}
</script>

<!-- ✅ 以下為專案內容 -->

# F1-TelemetryStation-Pro

**F1 data analysis**

## What is this?

F1-TelemetryStation-Pro is an open-source **F1 data analysis** and telemetry visualization tool.  
It allows race engineers, sim racers, and data fans to analyze lap times, throttle usage, speed traces, and driver comparisons using real Formula 1 telemetry.


A professional Formula 1 telemetry analysis workstation providing comprehensive race data analysis capabilities.

![F1 data analysis telemetry visualization tool](/images/Rain.track.pitstop.tire.accident.png)

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

![F1 data analysis telemetry visualization tool](/images/Lap.track.png)

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

![F1 data analysis telemetry visualization tool](/images/pitstop.accidient.png)

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

![F1 data analysis telemetry visualization tool](/images/tire.lap.detailed.rain.png)

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
![F1 data analysis telemetry visualization tool](/images/throttle.png)

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

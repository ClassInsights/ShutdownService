# ClassInsights WinService

> Windows Service that monitors system information and manages computer shutdown based on WebUntis timetable integration

[![Latest Release](https://img.shields.io/github/v/release/ClassInsights/WinService)](https://github.com/ClassInsights/WinService/releases)

## Overview

The ClassInsights WinService is a Windows background service designed for educational institutions using WebUntis. It intelligently monitors various system metrics and automatically manages computer power states based on class schedules, optimizing energy consumption while ensuring systems are available when needed.

## Features

- **WebUntis Integration** - Automatically retrieves and processes timetable data
- **Smart Power Management** - Schedules computer shutdowns based on class schedules
- **System Monitoring** - Tracks various system metrics and activities
- **Background Service** - Runs silently as a Windows service without user interaction
- **API Connectivity** - Communicates with ClassInsights API for centralized management
- **Automated Updates** - Self-updating capabilities for seamless maintenance

## System Requirements

- **Operating System**: Windows 10/11 or Windows Server 2019+
- **Permissions**: Administrator privileges for service installation
- **Network**: Internet connectivity for API communication and WebUntis access
- **ClassInsights API**: Needs to be up and running before installing any clients

## Installation

Please see [our docs](https://docs.classinsights.at) for our recommended installation process.

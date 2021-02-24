---
layout: post
title:  "FRC Quickstart Guide"
date:   2021-02-23 17:32:11 -0500
categories: frc, guide
keywords: frc, guide
---

This guide contains most (if not all) of the software tools needed to get an FRC robot working.

> This is a block quote

```lua
print("This is some code!")
```

# Overview

 - [Requirements](#requirements)
 - [Installing FRC Game Tools](#installing-frc-game-tools-windows-only)
 - [FRC Java/C++ Programming Suite (All Platforms)](#frc-programming-suite-all-platforms)
 - [Radio Configuration Utility (Windows Only)](#radio-configuration-utility)
 - [References](#references)

## Requirements

- **(For FRC Game Tools only)** A Windows computer. Windows 10 is recommended.
- A correctly wired FRC robot. [See the FRC wiring guide.](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-1/how-to-wire-a-robot.html)
- A working internet connection.

## Installing FRC Game Tools (Windows only)

1. Download the [FRC Game Tools Installer](https://www.ni.com/en-us/support/downloads/drivers/download.frc-game-tools.html#369633).
2. Navigate to your newly-downloaded installer and run it. Accept the license agreement and continue.
3. Follow the installer's instructions and let it run to completion.

The NI Tools Suite will install these programs:
 - FRC Driver station
 - roboRIO Imager

## FRC Programming Suite (All Platforms)

1. [Navigate to the WPILib suite releases page.](https://github.com/wpilibsuite/allwpilib/releases)
2. Scroll down and pick the appropriate file under the Assets tab. For Windows computers, download [`WPILib_WIndows64-2021.2.2.iso`](https://github.com/wpilibsuite/allwpilib/releases/download/v2021.2.2/WPILib_Windows64-2021.2.2.iso)
3. **Windows Only** Once the `WPILib_Windows.x.iso` file has finished downloading, navigate to it in the Downloads folder, right click it, and select `Mount`
4. **Windows Only** Open the new DVD drive in the file explorer. Run `WPILibInstaller.exe` and push `Start`.
5. The installer will ask for which version of VS Code to be installed. VS Code is a Microsoft program that cannot be included with WPILib for licensing reasons. For most users, select `Download VS Code for Single Install`, even if VS Code is already installed. This will install the WPILib tools into its own container of VS Code.
6. Once WPILib indicates that VS Code is done downloading, continue the installation.
7. WPILib will ask for items to install. Leave every item checked. This will install both Java and C++ FRC libraries. Proceed with installation.
8. Once WPILib finishes installing the new programs will be on the desktop. Press `2021 WPILib VS Code` to open the WPILib bundled VS Code editor. The WPILib software comes preconfigured for FRC programming.

WPILib will save a local copy of everything you need to get going, including:
 - VS Code with plugins preinstalled
 - Coding documentation
 - Software tools such as Pathweaver, Shuffleboard, SmartDashboard, RobotBuilder, and OutlineViewer. (Documentation for these tools can be found in the included WPILib documentation)

## Radio Configuration Utility

The FRC Radio Configuration Software is used to configure your robot's radio. For a full guide, visit [Programming Your Radio (docs.wpilib.org)](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-3/radio-programming.html)

1. [Download FRC Radio Configuration Software 20.0.0 (.zip)](https://firstfrc.blob.core.windows.net/frc2020/Radio/FRC_Radio_Configuration_20_0_0.zip)
2. Navigate to the downloaded `.zip` file and extract it.
3. Run the installer included in the `.zip` file. This will include the configuration tool itself and a program called `nmap` which is responsible for scanning network configurations.
4. Navigate to your computer's desktop and run `FRC Radio Configuration Utility`. 

If you already have Java installed, the radio configuration utility should work. If not, continue following these instructions:

5. If you do not have Java Runtime Environment installed, the installer will take you to the JRE download page. Ensure you are on [https://java.com/en/downloads](https://java.com/en/downloads). On the Java website, press `Agree and Start Download` for your version of Java Runtime Environment.
6. Download the installer and select `Install` to complete the installation of Java Runtime Environment.
7. Once the Java installation finishes, try running the `FRC Radio Configuration Utility` again.

If the installation went well, the radio configuration utility's graphical interface should pop up and ask for a network interface. The Radio Configuration Utility is an extremely handy tool to have available on team laptops during and after build season. For a guide on and explanation about the radio configuration software, click **here** (no guide yet).

## References

[See docs.wpilib.org](https://docs.wpilib.org/en/stable/) for full detailed documentation on every step.

- [Installing Software (docs.wpilib.org)](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/index.html) 
- [Offline Installation Preparation (docs.wpilib.org](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/offline-installation-preparations.html)
- [FRC Game Tools Installation (docs.wpilib.org)](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/frc-game-tools.html)
- [WPI FRC Wiring Guide (docs.wpilib.org)](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-1/how-to-wire-a-robot.html)




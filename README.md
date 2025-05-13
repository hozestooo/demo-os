# demoOS

![demoOS Boot Display](./assets/boot_display.png)

## About

demoOS is an open-source operating system using the Cosmos OS framework. It serves as a learning platform demonstrating fundamental operating system concepts.

## Features

* Basic command-line interface
* File system operations (List, Add, View, Remove .txt files)
* System information display (Time, Date, RAM, CPU, Storage)
* Network information display (IP Address)
* Customizable settings (Time/Date Format, Language)

## Getting Started

### Prerequisites

Make sure you have the following installed:
* Visual Studio (e.g., 2019) with the ".NET Core cross-platform development" workload
* .NET Framework 4.6.2 Developer Pack
* VMware Player or Workstation
* Latest Cosmos User Kit (installed via executable, *after* Visual Studio)

### Installation

**Option 1: Clone the Repository**
```bash
git clone [https://github.com/honestovicente/demoOS.git](https://github.com/honestovicente/demoOS.git)
cd demoOS
```

Then open the demoOS.sln file in Visual Studio.

**Option 2: Download ZIP**

* Download the source code ZIP file from the GitHub repository page.
* Extract the contents.
* Open the demoOS.sln file in Visual Studio.

Running
* Ensure all prerequisites, especially the Cosmos User Kit, are correctly installed.
* Open the project solution (demoOS.sln) in Visual Studio.
* Build the solution.
* Run the project (usually by pressing F5 or the start button). Cosmos integration should typically launch the OS in your 
 installed VMware instance.

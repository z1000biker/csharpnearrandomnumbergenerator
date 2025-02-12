# Near Random Number Generator

## Overview

This project aims to generate near-random numbers by leveraging inherent variability in system metrics such as CPU load, disk I/O, and network traffic. While these numbers are not truly random, they provide a degree of unpredictability suitable for non-cryptographic purposes.

## Features

- **CPU Load**: Uses the current CPU load as a source of entropy.
- **Disk I/O**: Generates entropy from disk read/write operations.
- **Network Traffic**: Leverages network activity to introduce variability.
- **Combined Entropy**: Combines multiple sources for better randomness.

## Getting Started

### Prerequisites

- .NET Framework or .NET Core installed on your system.
- Visual Studio 2022 or any compatible IDE.

### Installation

Open the solution file in Visual Studio 2022.
### Build the Project:
Open the solution in Visual Studio.
Build the project to ensure all dependencies are resolved.
Run the Application:
Press F5 to run the application.
The application will generate a near-random number based on the combined entropy from CPU load, disk I/O, and network traffic.

### Limitations
- **Non-Cryptographic**: This generator is not suitable for cryptographic purposes due to its reliance on system metrics, which can be influenced by various factors.
- **System Load** : The quality of randomness can vary based on system load and network activity.

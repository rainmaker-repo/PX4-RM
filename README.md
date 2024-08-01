# PX4 Autopilot - Rainmaker Fork

This repository contains a fork of the PX4 Autopilot project with specific modifications for Rainmaker.

## Getting Started

Follow these steps to set up and build the project:

1. Clone the repository:
   ```
   git clone --recursive https://github.com/rainmaker-repo/PX4-RM.git
   cd PX4-RM
   ```

   Note: The `--recursive` flag will automatically initialize and update all submodules.

2. Install PX4 Toolchain:

   For Ubuntu/Debian:
   ```
   bash ./Tools/setup/ubuntu.sh
   ```

   For macOS:
   ```
   bash ./Tools/setup/macos.sh
   ```

   For Windows:
   ```
   bash ./Tools/setup/windows.sh
   ```

   These scripts will install all necessary dependencies and set up the PX4 development environment.

3. Build the project:
   ```
   make px4_sitl
   ```

   This will build the SITL (Software In The Loop) version. For other build targets, refer to the official PX4 documentation.

## Additional Information

For more detailed information about PX4 Autopilot, including supported hardware, contribution guidelines, and documentation, please refer to the [official PX4 repository](https://github.com/PX4/PX4-Autopilot).

## License

This project is licensed under the BSD 3-clause license - see the [LICENSE](LICENSE) file for details.

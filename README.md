# PX4 Autopilot - Rainmaker Fork

This repository contains a fork of the PX4 Autopilot project with specific modifications for Rainmaker.

## Getting Started

Follow these steps to set up and build the project:

1. Clone the repository:
   ```
   git clone https://github.com/rainmaker-repo/PX4-RM.git
   cd PX4-RM
   ```

2. Update submodules:
   ```
   git submodule update --init --recursive
   ```

3. Fetch all tags:
   ```
   git fetch --tags
   ```

4. Build the project:
   ```
   make px4_sitl
   ```

   This will build the SITL (Software In The Loop) version. For other build targets, refer to the official PX4 documentation.

## Additional Information

For more detailed information about PX4 Autopilot, including supported hardware, contribution guidelines, and documentation, please refer to the [official PX4 repository](https://github.com/PX4/PX4-Autopilot).

## License

This project is licensed under the BSD 3-clause license - see the [LICENSE](LICENSE) file for details.

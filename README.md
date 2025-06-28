# Aseprite RPM Build Script

This repository contains a simple script to build an RPM package for Aseprite from the official GitHub source.

## Files
- `build-aseprite-rpm.sh`: Bash script to automate the build process.
- `aseprite.spec`: RPM spec file for Aseprite.

## Usage
1. Make the script executable:
   ```bash
   chmod +x build-aseprite-rpm.sh
   ```
2. Run the script:
   ```bash
   ./build-aseprite-rpm.sh
   ```

The script will install required dependencies, download sources, and build the RPM. All sources and build files are downloaded and created in a single directory.

---

**Tested only on Fedora 42.**
**And Aseprite v1.3.14**

All rights to Aseprite belong to the original authors.

- Support Aseprite: https://www.aseprite.org/
- Original repository: https://github.com/aseprite/aseprite

This script was created because Aseprite does not offer an official RPM package.


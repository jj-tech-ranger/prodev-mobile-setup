# Mobile Development Setup

## Objective
To set up a robust mobile development environment using the Expo Framework, Node.js, and Expo Go for real-time device testing.

## Environment Details
- **Node.js**: Installed (LTS version)
- **IDE**: WebStorm
- **Operating System**: Windows
- **Testing Device**: Physical device with Expo Go installed

## Installation Steps
1. Installed Node.js LTS from the official website.
2. Installed the Expo Go app on my physical mobile device via the App Store/Google Play Store.
3. Created an Expo account and logged in on both the development machine and the mobile device.
4. Verified that both the computer and the mobile device are on the same Wi-Fi network.

## Challenges and Troubleshooting
- **Network Discovery**: Initially, the mobile device could not find the local development server. This was resolved by ensuring both devices were on the same network and allowing Node.js through the Windows Firewall.
- **EPERM Errors**: Encountered permission issues during folder renaming on Windows. Resolved by closing the IDE and stopping any active Node processes before attempting file system changes.

## Conclusion
The environment is fully configured. The Expo CLI is responsive, and the physical device is ready to render React Native components via Expo Go.
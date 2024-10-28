# Haveno App

<img src="https://i.ibb.co/J7J9qV4/Screenshot-20240817-203316.jpg" width=150 /> <img src="https://i.ibb.co/Btt17Vg/Screenshot-20240817-203341.jpg" width=150 /> <img src="https://i.ibb.co/1L09NT6/Screenshot-20240817-203431.jpg" width=150 /> <img src="https://i.ibb.co/QDPyJp9/Screenshot-20240817-203535.jpg" width=150 /> <img src="https://i.ibb.co/L011YGW/Screenshot-20240817-203150.jpg" width=150 /> <img src="https://i.ibb.co/64YQR1S/Screenshot-20240817-204709.jpg" width=150 />

## Table of Contents
1. [Prerequisites](#prerequisites)
4. [Project Status](#project-status)
   - [Network Endorsements](#network-endorsements)
6. [Project Activity](#project-activity)
7. [Roadmap](#roadmap)
8. [Contributing](#contributing)

---

## Prerequisites (For Testing)

Before you begin, you'll need to set up a testing environment:

- **Android Device or Emulator:** You can test on a physical Android phone or use an Android simulator via [Android Studio](https://studio.android.com) for advanced users. [BlueStacks](https://www.bluestacks.com/download.html) is another option with a gentler learning curve.
- **Latest Pre-release Builds:** Obtain the latest pre-release builds from the [Releases](https://github.com/KewbitXMR/haveno-app/releases) page. These are typically updated weekly.

**Important:** Follow the instructions in this guide carefully for Haveno Plus to function correctly.

## Setup Your Mobile Device

### Install Tor VPN Relay

To ensure all traffic is securely routed through Tor, you must install and activate a Tor VPN relay on your mobile device. The recommended apps are:

- **[Orbot](https://play.google.com/store/apps/details?id=org.torproject.android):** Officially supported by The Tor Project.
  - [Sourcecode & Releases](https://github.com/guardianproject/orbot/releases/tag/17.3.2-RC-1-tor-0.4.8.12)
- **[InviZible](https://play.google.com/store/apps/details?id=pan.alexander.tordnscrypt.gp):** A popular community alternative.
  - [Sourcecode & Releases](https://github.com/Gedsh/InviZible/releases/tag/v2.3.0-beta)

**Steps:**
1. Download [Orbot on Google Play](https://play.google.com/store/apps/details?id=org.torproject.android) or [InviZible on Google Play](https://play.google.com/store/apps/details?id=pan.alexander.tordnscrypt.gp).
   - Alternatively, download [InviZible on F-Droid](https://f-droid.org/packages/pan.alexander.tordnscrypt.stable/).
2. Open the app of your choice and follow the on-screen instructions to activate it. Ensure that Tor is enabled and the VPN is activated.
3. Configure the VPN relay to route your Haveno Plus app traffic through Tor. The app will not load if a VPN relay is not configured first, by design, for your security.

### Haveno Install Guide

The Haveno Plus app is available as alpha pre-release builds for Android and Windows. Download the app from the [Releases](https://github.com/KewbitXMR/haveno-app/releases) page. The desktop clients are designed to be user-friendly, with custom installers for quick setup.

**Note:** Haveno Plus is currently configured to use the stagenet (a test network) for at least the next 2 months. It is not intended for real-life trading.

## Setup Your Desktop or Server

- **Windows:** (Coming soon)
- **MacOS:** (Coming soon)
- **Android** (Coming soon)
- **iOS** (Coming soon)
- **Linux:** (Coming soon)
- **Docker:** (Coming soon)


### Step-by-Step Guides
1. [How to Install Haveno on Desktop](https://haveno.com/documentation/installing-haveno-on-desktop/)
2. [How to Install Haveno on Mobile](https://haveno.com/documentation/install-haveno-on-a-mobile-device/)
3. [How to Install Haveno on Server with Docker](https://haveno.com/documentation/installing-the-haveno-daemon-with-docker-securely/)
4. [How to Setup your own Haveno Network](https://haveno.com/documentation/setup-a-custom-haveno-network-seednode-with-docker/)


## Project Status

The project is currently on **Milestone 2** which is creating and releasing the **App UI**.

### Network Endorsements

Haveno does not endorse or denounce any particular network. The choice of network will be available upon official release.

## Project Activity

The project is actively developed full-time for at least the next 2 months. Continued support may require sponsorships or feature bounties. The goal is to provide significant value to the XMR community.

## Roadmap

- Dart SDK API ✅
- Complete and release UI - Currently milestone 
- Windows desktop Support 
- MacOS desktop support 
- Android mobile Support 
- Complete full arbitration scope.
- Add client authentication for onion-hosted daemons.
- iOS support. 
- Linux desktop support.
- Easy whitelisting and fund transfers to Cake Wallet or similar.
- Biometric security for mobile devices, with PIN or password protection for those without biometric options.
- Standalone version not requiring desktop or server (considerable work; community support may be needed).
- Support for Monero Atomic Swaps

## Contributing

Testing on old phones or laptops and providing high-quality feedback is the best way to contribute. A discussion section will be set up for initial feedback and contributions.

## Additional Resources
Kewbit the maintainers blog is at [Kewbit.org](https://kewbit.org/) official source and binaries for this are located at [https://haveno.com](Haveno.com) only, there are now also lots of guides located at [haveno documentation](https://haveno.com/documentation/) secion of the site, which are atuned towards the new app.

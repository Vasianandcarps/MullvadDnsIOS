# MullvadDnsIOS

A configuration profile (`.mobileconfig`) for setting up custom DNS on iOS via Mullvad DNS-over-HTTPS (the "base" filter: blocks ads, trackers, and malware).

## Installation

1. Open the `mullvad-dns.mobileconfig` link in Safari on your iPhone/iPad
2. Wait for the "Profile Downloaded" banner
3. Go to Settings → General → VPN & Device Management
4. Select the profile → Install → confirm with Face ID/passcode

## Direct install link (via jsDelivr)

https://cdn.jsdelivr.net/gh/Vasianandcarps/MullvadDnsIOS@main/mullvad-dns.mobileconfig

## Shortcut with installation

Works properly if Safari is your default browser. If you use Brave or another browser, check which folder your downloads are saved to and update the folder parameter in the "Get File" action accordingly.

<img height="500" alt="signal-2026-07-26-23-08-15-046" src="https://github.com/user-attachments/assets/3b443da5-08ff-45e5-aba6-ebba0ec7d3c6" />

## Removal

Settings → General → VPN & Device Management → select the profile → Remove Profile

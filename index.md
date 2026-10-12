# OCOS Privacy Policy

Effective date: October 12, 2026

Developer: Mishchenko Sergei, contact: msi.mail@yandex.ru

## Summary

OCOS is a VPN client for iPhone that connects to ocserv servers (OpenConnect / AnyConnect protocol). The app does not
collect user data, does not send it to the developer, and does not share it with third parties. While the VPN is on,
traffic goes only to the server the user specified.

## Data the app handles

**Connection profiles** — name, server address, user name, authentication group and settings (including "TCP only" and
"Connect automatically"). They are stored on the device in the app's data and may be included in device backups under
standard iOS rules.

**Password** — stored on the device in the iOS Keychain, not in profile files. The password leaves the device only when it
is sent to the user's own VPN server during sign-in.

**Sign-in credentials** are sent only to the VPN server the user specified, over a secure connection (TLS). The developer has
no access to that server or to these credentials.

**Client information.** As part of the AnyConnect protocol, the VPN server receives standard client details: platform (iOS),
client version and generic device information. This is required by the protocol and goes only to the user's own server.

**Network traffic** is encrypted while the VPN is on and sent to the user's server. The app does not inspect, record or modify
the content of the traffic. Tunnel parameters (address, DNS, MTU, traffic counters, last error reason) are shown in the app
and never leave the device.

**System logs.** Diagnostic messages from the VPN extension are written to the device's system log and are not sent to the
developer.

## What the app does not do

- contains no analytics, advertising or crash-reporting services;
- does not send data to the developer or to third parties;
- does not sell, use or disclose any data to third parties for any purpose;
- does not track the user or use advertising identifiers;
- does not use traffic for advertising or monetization;
- does not request access to contacts, location, camera, microphone or photos.

## Open-source components

The app uses OpenConnect (LGPL 2.1), OpenSSL (Apache 2.0) and KCP (MIT). Versions, source links and full license texts are
available in the app: Settings → Legal information and licenses.

## Security

"Allow invalid certificate" turns off server certificate verification and weakens the connection's protection. Enable it
only for your own server and only if you understand the risk.

## Deleting data

A profile and its password can be deleted in the app (Configurations → profile → Delete configuration). All data is also
removed when the app is deleted from the device.

## Children

The app is not directed to children under 13 and does not collect their data.

## Changes

Changes are published on this page with a new effective date.

## Contact

msi.mail@yandex.ru

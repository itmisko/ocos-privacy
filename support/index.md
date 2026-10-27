# OCOS Support

OCOS is an independent VPN client for iPhone that connects to ocserv servers (OpenConnect protocol, compatible with
AnyConnect-compatible servers). OCOS does not provide VPN servers, accounts or subscriptions: you need a server that you run
yourself or that your administrator gives you access to. For the server address, user name and password, please contact
your server administrator.

Contact: msi.mail@yandex.ru — please include the app version (Settings → About), your iOS version and a short description
of the problem.

## Getting started

1. Open OCOS and tap "+".
2. Enter the server address (for example, `vpn.example.com` or `vpn.example.com:4443`), your user name and password.
3. Tap "Add", then tap the large power button on the main screen.
4. When iOS asks to add a VPN configuration, allow it.

The password is stored in the iOS Keychain on your device and is sent only to your VPN server.

## Common problems

**"The VPN server rejected the sign-in details."** Check the user name and password in the profile. After several wrong
passwords in a row, the server may temporarily block your IP address — wait a few minutes before trying again.

**Certificate error.** OCOS checks the server's TLS certificate. If your server uses a self-signed certificate, ask your
administrator for a certificate from a public certificate authority. "Allow invalid certificate" turns off certificate
checks and weakens protection — use it only for your own server and only if you understand the risk.

**The server cannot be found or does not respond.** Check the server address and port in the profile and your internet
connection. If the server does not answer within 30 seconds, OCOS stops the attempt and shows an error.

**"Session rejected".** The server accepted your user name and password but refused a new connection, usually because a
previous connection of the same account is still active on the server (connection limit). Wait a few minutes and connect
again, or ask your administrator to allow more simultaneous connections.

**The connection drops on networks that block UDP.** Turn on "TCP only (no DTLS/UDP)" in the profile.

## Sending a diagnostic report

If a problem keeps happening, a diagnostic report helps to find the cause.

1. Open Settings → Support → Diagnostics and tap "Diagnose next connection".
2. Return to the main screen, connect and reproduce the problem.
3. Right after the error, tap "Send report" under the error message (or "Send diagnostic report" in Diagnostics).
4. Check the preview (files, size, period), then send the report to msi.mail@yandex.ru from your mail app or another
   app of your choice. Please add what you did, the time on your phone and the network type (Wi-Fi or cellular).

The report contains technical logs only. Passwords, cookies, user names, server addresses, profile names and IP addresses
are removed before anything is written, and nothing leaves your device unless you send it yourself. You can delete the
logs at any time in Settings → Diagnostics → Clear logs.

## Open-source components

OCOS statically links OpenConnect (GNU LGPL 2.1) and uses OpenSSL (Apache License 2.0). Versions, source links and full
license texts are available in the app: Settings → Legal information and licenses.

On request through the contact above, the applied changes, object files and instructions needed to relink OCOS with a
modified OpenConnect are provided free of charge for at least three years after the distribution of each version.

OCOS is not affiliated with the OpenConnect project, the ocserv project or Cisco. "AnyConnect" is a trademark of Cisco
Systems, Inc., used here only to describe protocol compatibility.

## Privacy

OCOS contains no ads or analytics and collects no data. Privacy policy: https://itmisko.github.io/ocos-privacy/

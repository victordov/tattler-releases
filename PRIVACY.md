# Tattler privacy policy

*Last updated: October 8, 2026. Applies to Tattler for macOS, from the Mac App Store and from this repository.*

Tattler is a firewall and network monitor that runs entirely on your Mac. It has no accounts, no
analytics and no telemetry, and it collects no information about you.

## What stays on your Mac

Everything Tattler records stays on your Mac and is never sent to us or anyone else: the
connections apps make, your rules, profiles and lockdowns, traffic statistics, and (in the version
from this repository) packet captures, TLS keys and intercepted traffic. You can delete any of it
from the app, and uninstalling Tattler removes it.

## The only connections Tattler makes

- **Blocklists and rule groups** you add, downloaded from the addresses you give and refreshed.
- **db-ip.com**, to download the country database (and the city database, if you turn it on) for
  the map, about once a month. Addresses are looked up locally and never sent.
- **The encrypted DNS provider** you choose, if you turn encrypted DNS on, which then answers your
  Mac's DNS lookups under its own privacy policy.
- **GitHub**, to check for updates (version from this repository only, if you allow it). The check
  names the app and its version, like any download.

## Location

If you allow it, Tattler uses Location Services only to read the name of the Wi-Fi network you're
on, so rules can change with the network. Your location is never stored or sent anywhere.

## Children

Tattler collects no information from anyone, including children.

## Changes and contact

Changes to this policy are published here, with the date above. Questions: open an issue at
https://github.com/victordov/tattler-releases/issues.

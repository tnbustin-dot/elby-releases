# Elby for Mac

Public installer downloads and signed update feeds for [Elby](https://helloelby.com).
This repository contains release files only. App source, account data, and credentials
are not published here. Using Elby still requires an allowed sign-in account.

Download the ZIP from the [latest release](https://github.com/tnbustin-dot/elby-releases/releases/latest),
quit an older Elby, and move **Elby.app** into Applications. Version 0.6.0 and later
include **Elby > Check for Updates…**. Automatic checks can be toggled in the same
menu; you choose when to install. Signed updates retain your existing sign-in and
pending captures.

Requires macOS 14 or later; installers support Apple Silicon and Intel.
These builds are currently ad-hoc code signed, not Apple-notarized. macOS may
require you to approve the initial app in Privacy & Security. In-app updates and
their feed are independently verified using Elby's Ed25519 update-signing key.

Release files are immutable. Each release includes its ZIP, signed `appcast.xml`,
release notes, and `SHA256SUMS`. The update feed is the latest release's
`appcast.xml` download.

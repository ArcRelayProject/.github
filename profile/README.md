# ArcRelay

> Local-first software for devices and networks you trust.

ArcRelay is developed and maintained by Shenzhen Changning Technology Co., Ltd.
We build focused tools for the everyday work that happens between your own
devices: moving input and content, capturing what is on screen, and connecting
directly across private networks.

We start with the device and network you control. Identity, permissions, data
paths, platform differences, and release status should remain visible instead
of being hidden behind a convenient interface.

## Products

| Product | What it does | Current stage |
| --- | --- | --- |
| **[ArcRelay](https://github.com/ArcRelayProject/arcrelay)** | Cross-device keyboard and mouse, clipboard, file transfer, and inspectable local automation | [Desktop source](https://github.com/ArcRelayProject/arcrelay) and [downloads](https://github.com/ArcRelayProject/arcrelay/releases) are public |
| **[Sniptra](https://github.com/ArcRelayProject/sniptra)** | Screenshot capture, editable annotation, local OCR, and pinned images | Included with ArcRelay and [available as a standalone download](https://github.com/ArcRelayProject/sniptra/releases/latest) for Windows, macOS, and Linux |
| **[SubnetDesk](https://github.com/zibo-chen/SubnetDesk)** | Direct remote desktop across LANs, routed private networks, and VPNs | Released from the maintainer repository; moving here later |

Products share a set of principles, but not necessarily the same release cycle,
license, or platform coverage. The README and release notes in each product
repository are the source of truth for current support.

## How we build

- **Local first.** Prefer local devices, LANs, and reachable private networks
  when a task does not need a cloud round trip.
- **Visible trust.** Make device identity, permission scope, data destination,
  and revocation understandable.
- **One clear job.** Shared foundations should not force someone to install a
  full suite for a focused task.
- **Honest boundaries.** Distinguish implemented capabilities, validation work,
  and released products without promising unverified dates or platforms.
- **Open where it helps.** Publish source, protocols, and engineering context
  where they make the software easier to inspect and improve.

## Open development

The ArcRelay desktop app and the shared components required to build it are
available in this organization. Sniptra documentation and standalone binaries
are public, while its source code remains proprietary. Mobile applications,
release-signing material, private QA and design records, and proprietary
integrations are maintained in private repositories. SubnetDesk currently
remains in the maintainer's personal repository; its source and downloads remain
available from the links above.

For a repository-specific bug or proposal, use that repository's issue tracker.
For an organization-profile correction, [open an issue here](https://github.com/ArcRelayProject/.github/issues/new).

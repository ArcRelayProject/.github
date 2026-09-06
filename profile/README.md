# ArcRelay

> Local-first software for devices and networks you trust.  
> 面向可信设备与私有网络的本地优先软件。

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
| **ArcRelay Suite** | Cross-device keyboard and mouse, clipboard, file transfer, and inspectable local automation | Desktop source and shared components are public |
| **Sniptra** | Screenshot capture, editable annotation, local OCR, and pinned images | Available in selected official builds; standalone release planned |
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
available in this organization. Mobile applications, release-signing material,
private QA and design records, and proprietary integrations are maintained in
private repositories. SubnetDesk currently remains in the maintainer's personal
repository; its source and downloads remain available from the links above.

For a repository-specific bug or proposal, use that repository's issue tracker.
For an organization-profile correction, [open an issue here](https://github.com/ArcRelayProject/.github/issues/new).

---

## 中文

ArcRelay 由深圳市长柠科技有限公司（Shenzhen Changning Technology Co., Ltd.）
开发和维护，专注于自己的设备之间那些本应简单的任务：传递键鼠与内容、截取和
整理屏幕信息，以及在局域网、专线和 VPN 中直接连接设备。

| 产品 | 主要用途 | 当前阶段 |
| --- | --- | --- |
| **ArcRelay Suite** | 跨设备键鼠、剪贴板、文件传输与可检查的本地自动化 | 桌面端及其必要共享组件已公开 |
| **Sniptra** | 截图、可编辑标注、本地 OCR 与贴图 | 在部分官方构建中提供；独立版规划中 |
| **[SubnetDesk](https://github.com/zibo-chen/SubnetDesk)** | 局域网、路由私网与 VPN 内的直接远程桌面 | 已在个人仓库发布；后续迁入本组织 |

我们优先使用用户可控的设备与网络，明确展示身份、权限和数据去向，让每个
产品解决一个清晰的问题，并如实区分已经发布、正在验证和长期探索的能力。

ArcRelay 桌面端及其构建所需的共享组件已在本组织公开。移动应用、发布签名材料、
内部 QA 与设计记录以及专有集成继续保存在私有仓库。SubnetDesk 目前仍位于维护者
的个人仓库。具体功能、平台支持与许可信息，以各仓库 README 和正式发行说明为准。

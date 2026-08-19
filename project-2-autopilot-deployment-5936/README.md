# Windows Deployment with Autopilot

**Certification:** MD-102: Endpoint Administrator  ·  **Completed:** 2026-08-19

**Eric Kulee** · [@ericskulee](https://github.com/ericskulee)

Deploy Windows using modern provisioning. Configure Windows Autopilot deployment profiles across the deployment modes (user-driven, self-deploying, pre-provisioning), register a device with Autopilot using its hardware hash, create a device group for Autopilot, and configure provisioning packages as an alternative. Commit your Autopilot profile configuration, device registration, and deployment mode settings.

## What I built

- **Autopilot Deployment Profile** — `md102-autopilot-profile` — User-driven with Microsoft Entra join; OOBE customized
- **Dynamic Device Group** — `md102-autopilot-devices` — Rule: device.devicePhysicalIds -any _ -contains "[ZTDId]"
- **Provisioning Package** — `md102-provisioning.ppkg` — Offline alternative to Autopilot via Windows Configuration Designer

## Steps completed

1. Create a Windows Autopilot Deployment Profile
2. Register a Device and Create a Dynamic Autopilot Group
3. Configure Pre-Provisioning and Compare Deployment Modes
4. Create a Provisioning Package Alternative

## What this covered

- Manage and maintain devices — 25-30% of exam

## Evidence

| # | Task | Screenshot |
|---|------|------------|
| 1 | Create a Windows Autopilot Deployment Profile | [01-autopilot-deployment-profile.png](./screenshots/01-autopilot-deployment-profile.png) |
| 1.2 | Create a Windows Autopilot Deployment Profile | [01-autopilot-deployment-profile-2.png](./screenshots/01-autopilot-deployment-profile-2.png) |
| 2 | Register a Device and Create a Dynamic Autopilot Group | [02-autopilot-device-dynamic-group.png](./screenshots/02-autopilot-device-dynamic-group.png) |
| 2.2 | Register a Device and Create a Dynamic Autopilot Group | [02-autopilot-device-dynamic-group-2.png](./screenshots/02-autopilot-device-dynamic-group-2.png) |
| 2.3 | Register a Device and Create a Dynamic Autopilot Group | [02-autopilot-device-dynamic-group-3.png](./screenshots/02-autopilot-device-dynamic-group-3.png) |
| 3 | Configure Pre-Provisioning and Compare Deployment Modes | [03-preprovisioning-mode-comparison.png](./screenshots/03-preprovisioning-mode-comparison.png) |
| 3.2 | Configure Pre-Provisioning and Compare Deployment Modes | [03-preprovisioning-mode-comparison-2.png](./screenshots/03-preprovisioning-mode-comparison-2.png) |
| 4 | Create a Provisioning Package Alternative | [04-provisioning-package.png](./screenshots/04-provisioning-package.png) |
| 4.2 | Create a Provisioning Package Alternative | [04-provisioning-package-2.png](./screenshots/04-provisioning-package-2.png) |
| 4.3 | Create a Provisioning Package Alternative | [04-provisioning-package-3.png](./screenshots/04-provisioning-package-3.png) |

## Skills demonstrated

- Windows Autopilot
- Deployment Profiles
- Deployment Modes
- ZTDId Dynamic Groups
- Provisioning Packages

---
_Powered by [HandsOnCert](https://handsoncert.com) — hands-on MD-102: Endpoint Administrator labs, auto-committed to this portfolio._

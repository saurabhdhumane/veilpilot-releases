# VeilPilot

**VeilPilot v1.0.1** is a desktop copilot for technical interview practice, live coding, and system-design study. It combines a desktop overlay, audio transcription, and screen vision to provide contextual explanations and coding guidance.

> **Responsible use:** VeilPilot is intended for mock interviews, practice, study, and other settings where AI assistance is permitted. Always follow the rules and code of conduct of your interviewer, school, employer, or assessment provider. Do not use it to misrepresent your abilities in an evaluation where assistance is prohibited.

- **Website:** [veilpilot.vercel.app](https://veilpilot.vercel.app/)
- **Downloads and release notes:** [GitHub Releases](https://github.com/saurabhdhumane/veilpilot-releases/releases)
- **Current version:** `1.0.1`

## Features

- **Desktop copilot overlay** with visibility, click-through, and always-on-top controls.
- **Screen vision and OCR** for coding prompts, diagrams, and test cases.
- **Audio assistance** with on-device speech transcription and headphone audio loopback capture.
- **Interview-focused responses** for algorithms, system design, programming-language topics, and behavioral questions.
- **Bring your own API key (BYOK):** configure a supported Google Gemini or OpenAI key in the application.
- **Local credential storage:** the website describes Windows DPAPI and macOS Keychain support.
- **Keyboard shortcuts** for common overlay, audio, screen-capture, and settings actions.

## Installation

Download the appropriate package from [Releases](https://github.com/saurabhdhumane/veilpilot-releases/releases) and follow the instructions included with that release. The website currently describes the following Windows package:

- **Windows 10/11, 64-bit:** `VeilPilot-Setup-1.0.1.exe` (84.2 MB)
- Minimum requirements: Intel Core i3 / AMD Ryzen 3 or equivalent, 4 GB RAM, and 350 MB of free storage. 8 GB RAM is recommended.
- A headphone or headset is recommended for audio loopback use.

After installation, activate the license, then open settings and add your own supported AI provider API key. See the [website](https://veilpilot.vercel.app/) for the latest platform and setup information. Native screen-protection support is described for Windows 10/11 and macOS; check the release notes for actual package availability and compatibility.

## Keyboard shortcuts

The shortcut labels below follow the website's macOS (⌘) and Windows/Linux (Ctrl) reference. Available shortcuts can vary by platform and configuration.

| Action | Shortcut |
| --- | --- |
| Capture screen for vision/OCR | `⌘ Shift S` |
| Toggle overlay visibility | `⌘ Shift V` |
| Toggle click-through | `⌘ Shift I` / `⌥ A` |
| Dismiss response HUD | `Esc` |
| Momentarily hide overlay | `⌘ Shift H` / `⌥ H` |
| Toggle speech recognition | `⌥ R` |
| Toggle audio capture mute | `⌥ M` |
| Toggle code word wrap | `⌥ W` / `⌘ Shift W` |
| Expand or collapse code area | `⌥ E` / `⌘ Shift E` |
| Open settings | `⌘ ,` |
| Clear session memory | `⌘ Shift \\` |
| Open manual chat prompt | `⌘ Shift C` |
| Force always on top | `⌘ Shift T` |
| Emergency quit | `⌘ Shift Q` |

## Privacy and security

According to the product description, audio transcription runs locally using an embedded faster-whisper worker, while the application uses the user's own AI API key for model requests. API keys are described as being stored locally using Windows DPAPI or macOS Keychain. Review the [privacy policy](https://veilpilot.vercel.app/) and your provider's terms before use; third-party AI requests may be subject to that provider's data practices.

The product also describes native screen-capture protection and process-disguise features. Support and behavior can vary by operating system and screen-sharing application. Verify the behavior on your own system and do not rely on it to conceal activity where disclosure is required.

## License and pricing

The website advertises a single-device lifetime license for **₹59** (promotional price; the listed original price is ₹129), with a 14-day performance guarantee and lifetime software updates. Check the [website](https://veilpilot.vercel.app/) for current pricing, terms, and purchase details.

## Support

For release-specific questions or to report a problem, [open an issue](https://github.com/saurabhdhumane/veilpilot-releases/issues) and include your operating system, VeilPilot version, and steps to reproduce the issue. Do not include API keys, license keys, or other secrets in an issue.

---

© 2026 VeilPilot Technologies Inc. Product details in this README are based on the website and may change; refer to the current release notes and product site for the latest information.

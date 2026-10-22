# Anti-Paws

**Published under the Diakrisian-Byte banner.**

> Because not every keystroke comes from fingers.

Anti-Paws is a small Windows system-tray utility intended to recognize suspicious keyboard input patterns that may arise when cats walk, sit, or sprawl across keyboards.

When activity triggers the guard, Anti-Paws asks:

**Was that Feline or Fingers?** — **YES / NO / MAYBE**

- **YES:** Attempts to remove a verified suspicious text suffix in supported classic Windows single-line text controls.
- **NO:** Leaves the input unchanged.
- **MAYBE:** Displays “Feline phantasms most likely... Watch your half full cups for spills.”
- Includes a tray menu, manual pause, optional startup, and a launch notification: “Anti-Paws is running purrrrfectly”.

## Download

Visit [GitHub Releases](https://github.com/diakrisian-byte/Anti-Paws/releases) and download the file named **Anti-Paws_v0.1.2_Windows-x64.zip**.

Extract it and launch `Anti-Paws.exe`. No conventional installation is required. Windows 10 or 11 (x64) and a compatible .NET Framework 4.x runtime are required.

This repository is the **official portable binary release channel** of Diakrisian-Byte. GitHub’s automatically generated *Source code (zip)* archive is not the Anti-Paws application.

## Safety and privacy

This utility observes keyboard event patterns while active; it does not record a persistent typing log or include built-in network telemetry. If YES is selected, a limited recovery routine can read certain standard Windows text controls to verify the proposed removal.

**It is not an operating-system lock or a security product.** It may fail to intercept a keystroke before an application receives it. Text recovery is limited and must not be relied upon for web editors, password fields, or other unsupported controls.

Read the [privacy notice](PRIVACY.md) and the README/PRIVACY text included in the ZIP.

The first distributed build is marked **pre-release** pending broader clean-machine testing. The EXE is currently unsigned; do not disable operating-system security protections merely to run it.

## Support

Use this repository’s [Issues](https://github.com/diakrisian-byte/Anti-Paws/issues) to report functional defects or false-positive detection. Do **not** post passwords, typed sensitive data, or personal logs.

## Rights and licensing

**No open-source license has been granted.** The portable executable is distributed for end-user use through the official release channel. Publishing a binary on GitHub does not authorize redistribution, modification, or republication of the software or artwork without permission.

Publisher / project banner: **Diakrisian-Byte**.

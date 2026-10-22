# Anti-Paws — Privacy Notice

**Diakrisian-Byte · Portable Windows edition v0.1.2**  
**Published:** October 21, 2026

Anti-Paws is a Windows utility designed to detect unusual keyboard event patterns associated with accidental input. Its normal operation is local to the user's computer.

## Keyboard input examined

While active, Anti-Paws installs a keyboard hook and temporarily observes key-event timing, pressed-key overlap, and a short sequence of recent keystrokes. This observation can occur while other applications have focus.

Only when a user clicks **YES** does the app attempt limited text correction. For certain supported standard Win32 single-line EDIT controls, it may read the field's text and caret position to verify a specific matching suffix before selecting and removing that suffix. Unsupported or ambiguous fields are left unchanged.

## Storage and network

The v0.1.2 compiled application contains no built-in network communication, advertising, cloud analytics, account login, or persistent keystroke logging. Keyboard-event state is held in process memory and discarded on exit.

Other software on the computer, Windows itself, or GitHub may process their own telemetry separately. Anti-Paws cannot control those systems.

## User controls

Use the tray icon to pause protection or exit. **Start with Windows is optional and off by default**, with its per-user setting stored locally in the Windows Run registry location if enabled. The app is portable and can be removed by exiting it, disabling startup first, and deleting the downloaded files.

## Important limitations

Anti-Paws is not a secure input barrier. It cannot guarantee blocking all accidental typing or recovering any particular input, and it can report false positives. It is not intended for covert monitoring or for installation on a computer without authorization from its users.

## Questions or reports

Use the [official GitHub Issues page](https://github.com/diakrisian-byte/Anti-Paws/issues). Do not send sensitive typing history, passwords, or private material in issue reports.

# Privacy policy for Abyss Mod Manager

Publisher: Sylvie Abyss. Version 1.0, 24 October 2026. Applies to the Windows beta described by the accompanying build notes.

## Local information

AMM reads the game/mod locations you select and relevant local metadata, configuration, save descriptors, logs and process information to perform requested management and diagnosis. File fingerprint checks read selected mod payloads. Game-running checks inspect relevant process names, executable paths and command lines. Launch monitoring records related process identifiers, timing and exit information. It does not inspect unrelated document contents for analytics.

AMM stores settings, folder paths, drafts, profiles, notes, metadata, file fingerprints, downloaded caches, action history, backups and diagnostic logs locally. The default application-data folder on Windows is `%APPDATA%\Abyss Mod Manager`; an explicitly configured data directory can replace it. Game/mod files and backups can also be in the locations shown by their workflows. Native crash dumps are stored under the application's logs/crashes directory. Backups may contain complete mod payloads and copies of relevant configuration.

Application logs can contain local usernames through paths, mod identifiers, source URLs, timestamps, process identifiers and error details. Redaction attempts remove common credentials and URL query values; it is not a guarantee that every sensitive value is removed. Normal application logs rotate at roughly 4 MiB per file with up to four retained rotations; crash dumps, backups, caches and exports have separate lifetimes. Do not rely on rotation to remove all local records.

AMM does not require an AMM account. The inspected build does not implement publisher analytics, advertising identifiers or automatic crash uploads. Crash reporting is configured with uploads disabled. This does not prevent Windows, Steam, your browser, antivirus or other third-party software from communicating under its own settings.

## Network and external services

Online features contact the source involved when you request or enable that feature. These can include Steam/Steam Workshop public APIs and the installed Steam client, author update/download URLs, GitHub-hosted community rules, and Factorio's public mod portal. Source addresses can come from mod metadata or a URL you supply. A remote service receives ordinary connection information such as your IP address, requested URL, headers and request parameters. Published Workshop queries include the item IDs and/or search terms needed for that action. Opening a browser or Steam link passes that link to the chosen external application.

Steam subscription/download actions use your locally signed-in Steam session through the installed game's Steam API. Private local action history can retain a derived account-binding token to prevent verifying an action under a different account. AMM does not ask you for a Steam password. Steam controls its own account data, network traffic and content distribution.

Local scanning, sorting and file inspection are distinct from remote checks. Optional live Steam refresh can repeat requests while enabled. Requested downloads and an external game/mod's own network behavior are governed by their sources. No promise is made that launching third-party software is offline.

## Sharing and support

Diagnostic export creates a local file at the location you choose; it is not automatically submitted to the publisher. Review exported files before sharing. If you upload a report, screenshot, log, profile or save to GitHub, its recipients and GitHub process that material under their own policies. Public GitHub issues and attachments may be visible to everyone. Do not post secrets, account-binding records, full saves or unreviewed logs publicly. AMM has no publisher-side support-data retention schedule until you actually submit information through a support channel; that channel's published handling applies.

## Your choices and deletion

Use the relevant settings to disable optional automation/live refresh. Use the application's cache, backup and history controls where available. Keep independent backups before removing local data. Uninstalling AMM intentionally preserves application data; uninstall alone does not delete profiles, logs, snapshots, caches, exported files or game files. With AMM and games closed, you may delete the application-data directory if you no longer need its contents. Separately delete any exports and files stored outside it. Local deletion does not delete information already submitted to a third-party service.

## Contact and changes

Contact Sylvie Abyss through the official profile at https://github.com/sylvieabyss and the AMM support links published there. Request a private contact channel without posting sensitive information in public. This policy does not replace rights available under applicable privacy law. Material changes should be documented with a new policy date and release notes; this policy does not authorize new collection merely because a future feature is possible.

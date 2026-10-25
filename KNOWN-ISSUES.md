# Known beta limitations

- Windows x64 beta; installer unsigned. Physical installer wizard and default-data migration have not been qualified.
- Native RimWorld/Starsector acceptance receipts are version-specific. The last native-game-qualified build is0.99.0;0.100.0 passed packaged desktop/install-upgrade checks. Do not apply an older receipt to a newer binary.
- A controlled native campaign/colony does not prove compatibility with arbitrary saves, mods or combat.
- Live Steam subscribe/unsubscribe passed for one installed item, with verified backups and restored subscription/file state. New transferred-byte/matching download-completion acceptance is still separate. Do not automatically resend an uncertain request.
- Profile version metadata is different from byte fingerprints. Fingerprints detect changes; snapshots preserve recoverable files.
- Optional optimization currently has specific supported reversible operations; no general FPS improvement is promised.
- Expansion-game workspaces are incomplete; Antimatter is deferred.

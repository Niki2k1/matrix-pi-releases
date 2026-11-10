# matrix-pi update channel

Signed release binaries for matrix-pi LED panels. Devices fetch `latest.json`,
verify `latest.json.sig` (ed25519) against the key compiled into the firmware,
and then check the binary's SHA-256 from the manifest. Only the latest
release is kept; this branch is force-pushed on every release.

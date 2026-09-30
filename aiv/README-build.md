# AIV 0.6.20 public unsigned build lane

This branch is isolated for one purpose: compile the AIV 0.6.20 baseline into an aligned **unsigned** APK on a public GitHub-hosted runner.

- Source ZIP: `aiv/AIV-0.6.20-sources-completes.zip`
- Package: `fr.erick.journallocal`
- versionCode: `26`
- versionName: `0.6.20`

No signing key, password, certificate file, or signing secret is stored in this public repository.

The workflow uploads:
- `AIV-0.6.20-unsigned.apk`
- SHA-256
- `apksigner.jar`
- package/version verification output

Signing is intentionally performed outside GitHub after the unsigned artifact is downloaded.

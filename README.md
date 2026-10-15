# AdventHub Android releases

Signed APK downloads and update manifests only. Application source, signing keys, database data and logs are not stored in this repository.

- AdventHub Events: Levels 1–7, package `org.adventhub.events`.
- AdventHub Admin: Level 0 only, package `org.adventhub.admin`; live access requires a provisioned Level 0 account and authenticator MFA.
- Open Settings → App updates to check for a newer signed release.
- Releases are preview builds until the shared Supabase database is configured. Sample records are not a live membership database.

Download APKs from [Releases](https://github.com/jerdonlee/adventhub-releases/releases). Verify against SHA256SUMS.txt. Android requires permission to install app updates and user confirmation.

Future releases must increase the Android version code and use the original app signing key. Upload APKs/checksums, then update the respective manifest with the published asset URL and exact SHA-256. Keep Events and Admin manifests separate.

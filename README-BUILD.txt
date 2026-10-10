POCKET DEX CLOUD BUILD (PHONE-ONLY)

1. Create a new GitHub repository in your browser. Keep it private if you prefer.
2. Upload BOTH files from this package, preserving the workflow path:
   - pocketdex-source.zip (repo root)
   - .github/workflows/build.yml (this must be under .github/workflows/)
3. Open the repository's Actions tab. Select "Build Pocket Dex APK" and tap "Run workflow".
4. Wait for the workflow to finish. Open the successful run and download the "PocketDex-debug-APK" artifact.
5. Extract the downloaded artifact ZIP to obtain app-debug.apk, then install it on your phone if Android permits.

Important: this is an experimental build route. The source project has not been tested/verified, and the workflow may fail if the Gradle project needs fixes. Never upload passwords, signing keys, or personal secrets to the repository. A debug APK is for personal testing, not Play Store release.

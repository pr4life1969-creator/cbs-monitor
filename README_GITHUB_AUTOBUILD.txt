
How to auto-build the APK using GitHub (plain English)

1. Create a GitHub account at https://github.com (if you don't have one).
2. Create a new repository named: cbs-monitor
3. Upload the contents of this ZIP into the repository web UI (Add file -> Upload files).
   - Upload everything at the top level (bundle/, app/, .github/, build.gradle ...)
   - Commit the changes to the 'main' branch.
4. Go to the Actions tab on your repo. The workflow 'Build Android APK' will start automatically.
5. Wait ~5-10 minutes for the workflow to finish. Click the latest run, then download the 'cbs-apk' artifact.
6. Transfer the APK to your phone and install (allow unknown sources for the installer once).

If the build fails, send me a screenshot of the Actions log and I will interpret and fix it for you.

GEMI-GPT PIXEL AI — cloud APK build starter

This is a starter app, not a prebuilt APK. The current app has local photo selection, filters, brightness/contrast/saturation controls, and PNG export. Advanced generative AI tools are not implemented yet and require additional AI services.

Build the APK without installing Android Studio on your phone:
1. Download and extract this ZIP.
2. Sign in to GitHub and create a NEW repository named gemi-gpt-pixel-ai. Keep it private if preferred.
3. Upload the contents of this folder to the repository root. Include the .github/workflows/build-apk.yml file. If uploading the workflow folder is difficult on mobile, use GitHub's Add file > Create new file and create the path .github/workflows/build-apk.yml, then paste the workflow content from this ZIP.
4. Open the repository's Actions tab. Select "Build GEMI-GPT Pixel AI APK" and tap Run workflow (or push files to main to trigger it).
5. Wait for the workflow to finish successfully. Open the completed run and download the artifact named GEMI-GPT-PIXEL-AI-debug-apk.
6. Extract the artifact ZIP and install app-debug.apk. Android may ask permission to install apps from that browser/file manager.

Notes:
- GitHub account required. GitHub Actions availability/usage limits may apply.
- This creates a debug APK for testing, not a Play Store release APK.
- Never share your GitHub password or verification codes.

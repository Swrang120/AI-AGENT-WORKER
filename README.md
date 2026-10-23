# AI Agent Worker

A web landing page starter for the AI Agent Worker project.

## Current status
- `web-deploy` contains a responsive static website preview.
- This is **not yet** the full AI Content Factory application.
- The ZIP supplied in ChatGPT is an Android/Jetpack Compose project, not a website source bundle. The Android source still needs to be imported into this repository separately.
- AI generation, video rendering, YouTube/Drive OAuth, publishing, live streaming, multi-user authentication, and database features require backend implementation and provider credentials.

## Deploy the website with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `web-deploy` and folder `/ (root)`, then click **Save**.
4. Wait for GitHub Pages to publish. The final website URL will appear in the Pages settings.

## Next engineering steps
1. Import the Android project from the supplied ZIP into this repository (for example, into `android-app/`) or keep it in a separate repository.
2. Decide whether to build a separate web dashboard as well as the Android app.
3. Implement backend APIs and authentication before enabling real integrations.
4. Keep API keys and OAuth secrets in host environment variables; never commit them to Git.

# Study planner — public app, local private data

This folder contains only the empty app. It includes no personal timetable, trips, deadlines, account identifiers, or private resource links.

## Publish on GitHub Pages

1. Create a repository named `study-planner-app`. For the free Pages option, choose **Public**; only this empty app belongs in it. If your GitHub plan supports Pages from private repositories, you may keep the repository private while the empty Pages website remains public.
2. Upload **the contents of this folder**, including `index.html`. Do not upload the ZIP itself. Do not upload any personal JSON file or a previous personalized HTML file.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**. Save.
5. Wait for GitHub to show the deployed website address. Open that address.
6. Click **Import plan / backup**, choose **Replace plan and progress**, then **Choose JSON file** and select your private plan file from your device.
7. In your dashboard, click **+ Bookmark**, name it **Study planner**, paste the deployed website address, and save.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Importing and keeping progress

- The first visit is empty for everyone.
- The supplied private JSON contains the prepared schedule and resource links. It cannot include progress saved only in a browser that created it.
- If you already logged progress in an earlier planner, export that planner's newest JSON backup and import it instead. Then import the supplied private plan again using **Resource links only** to add the file links without replacing your progress.
- On the same browser/profile/device and website address, changes are saved automatically in local storage. A fresh private/incognito session, clearing browser data, or using another browser/device will not carry that data over.
- Use **Back up progress** periodically. Keep the JSON in a private location. It is not encrypted.
- The import is local: there is no upload, analytics, login service, cloud synchronization, or server-side database in this app.
- Resource files open only when you click their links. Links to your ChatGPT files require your signed-in account.
- Public app updates do not intentionally erase saved data. Keep a backup before updating.

## Publish future updates safely

Replace `index.html` with the next empty public-app version at the same Pages address. Never publish a personalized HTML version or private JSON backup.

The `.gitignore` helps avoid accidentally committing JSON from a local checkout. GitHub's browser uploader does not enforce it: choose your uploads carefully.

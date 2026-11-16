# TheDaily

A simple calorie tracker that runs as a website and installs to your iPhone home screen. Food data comes from the USDA FoodData Central API.

## Files

- `index.html` — the whole app (layout, styles, code, and the cheer character's artwork)
- `manifest.json` — lets the site behave like an app when added to the home screen
- `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` — home-screen icons

## Put it on GitHub Pages

1. Create a new public repository on GitHub, for example `thedaily`.
2. Upload all the files in this folder to the root of the repository.
3. In the repository, open **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two your app will be live at `https://YOUR-USERNAME.github.io/thedaily/`.

## Install it on your iPhone

1. Open the link in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**.
3. Open TheDaily from the home screen icon. It runs full screen, like an app.

Use it from the home screen icon rather than a Safari tab: Safari can clear data for websites you haven't visited in a while, but home-screen apps keep their data.

## Get a USDA API key

The app works right away with a shared demo key, but that key only allows a handful of searches per hour.

1. Sign up for a free key at https://fdc.nal.usda.gov/api-key-signup (it's emailed to you instantly).
2. In TheDaily, tap the gear icon, paste the key, and save.

The key is stored only on your phone. It is never written into the website files, so it stays out of your public GitHub repository.

## Your data

Everything you log is stored on your phone, in the browser's local storage. Nothing is sent anywhere except your search words, which go to the USDA. Use **Settings → Export backup** now and then to save a copy, and **Import backup** to restore it (or to move it to a new phone).

## Cheer character

She sits next to your calories-left number and reacts as you log: a cheer for your first entry of the day and when you reach about 90% of your goal, a giggle for other entries, and a gentle worried look if you go over. Tap her for encouragement. You can turn her off in Settings. Your daily goal isn't shown on the main screen; she uses it to know when to celebrate.

## Calendar

Scroll to the bottom to see the month. Days you logged show their calorie total; tap any day to see what you ate.

## Checking you have the latest version

Open Settings and look for the version number at the bottom. If it's not the newest one, close TheDaily completely (swipe it away in the app switcher) and open it again.

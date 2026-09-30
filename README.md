# app-pages

Support and privacy policy pages for my iOS apps, served by GitHub Pages at **https://app-pages-one.vercel.app/**.

App Store Connect requires a support URL and a privacy policy URL for every app. This repo is where those URLs point. Each app gets a folder with two static HTML files: no build step, no JavaScript, no tracking.

## Pages

| App | Support | Privacy |
|---|---|---|
| Baseline Ledger | [support](https://app-pages-one.vercel.app/baseline-ledger/) | [privacy](https://app-pages-one.vercel.app/baseline-ledger/privacy.html) |
| Chain | [support](https://app-pages-one.vercel.app/chain/) | [privacy](https://app-pages-one.vercel.app/chain/privacy.html) |
| Chores | [support](https://app-pages-one.vercel.app/chores/) | [privacy](https://app-pages-one.vercel.app/chores/privacy.html) |
| Clockout | [support](https://app-pages-one.vercel.app/clockout/) | [privacy](https://app-pages-one.vercel.app/clockout/privacy.html) |
| Curve | [support](https://app-pages-one.vercel.app/curve/) | [privacy](https://app-pages-one.vercel.app/curve/privacy.html) |
| Fairway Ledger | [support](https://app-pages-one.vercel.app/fairway-ledger/) | [privacy](https://app-pages-one.vercel.app/fairway-ledger/privacy.html) |
| Ironbook | [support](https://app-pages-one.vercel.app/ironbook/) | [privacy](https://app-pages-one.vercel.app/ironbook/privacy.html) |
| Minder | [support](https://app-pages-one.vercel.app/minder/) | [privacy](https://app-pages-one.vercel.app/minder/privacy.html) |
| Odometer | [support](https://app-pages-one.vercel.app/odometer/) | [privacy](https://app-pages-one.vercel.app/odometer/privacy.html) |
| Pawprint | [support](https://app-pages-one.vercel.app/pawprint/) | [privacy](https://app-pages-one.vercel.app/pawprint/privacy.html) |
| Pricebook | [support](https://app-pages-one.vercel.app/pricebook/) | [privacy](https://app-pages-one.vercel.app/pricebook/privacy.html) |
| Quiver | [support](https://app-pages-one.vercel.app/quiver/) | [privacy](https://app-pages-one.vercel.app/quiver/privacy.html) |
| Race Fuel | [support](https://app-pages-one.vercel.app/race-fuel/) | [privacy](https://app-pages-one.vercel.app/race-fuel/privacy.html) |
| Rooms | [support](https://app-pages-one.vercel.app/rooms/) | [privacy](https://app-pages-one.vercel.app/rooms/privacy.html) |

## Layout

```
index.html              list of apps
<app>/index.html        support page (what the app is, how to reach the developer)
<app>/privacy.html      privacy policy
```

## Adding an app

1. Copy an existing folder to `<app-slug>/` and edit the name, one-line description, accent color and the privacy text.
2. Add a link to `index.html`.
3. Push to `main`. GitHub Pages redeploys in a minute or two.
4. In App Store Connect, set the support URL to `https://app-pages-one.vercel.app/<app-slug>/` and the privacy policy URL to `https://app-pages-one.vercel.app/<app-slug>/privacy.html`.

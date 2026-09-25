# app-pages

Support and privacy policy pages for my iOS apps, served by GitHub Pages at **https://mattbusel.github.io/app-pages/**.

App Store Connect requires a support URL and a privacy policy URL for every app. This repo is where those URLs point. Each app gets a folder with two static HTML files: no build step, no JavaScript, no tracking.

## Pages

| App | Support | Privacy |
|---|---|---|
| Baseline Ledger | [support](https://mattbusel.github.io/app-pages/baseline-ledger/) | [privacy](https://mattbusel.github.io/app-pages/baseline-ledger/privacy.html) |
| Chain | [support](https://mattbusel.github.io/app-pages/chain/) | [privacy](https://mattbusel.github.io/app-pages/chain/privacy.html) |
| Chores | [support](https://mattbusel.github.io/app-pages/chores/) | [privacy](https://mattbusel.github.io/app-pages/chores/privacy.html) |
| Clockout | [support](https://mattbusel.github.io/app-pages/clockout/) | [privacy](https://mattbusel.github.io/app-pages/clockout/privacy.html) |
| Curve | [support](https://mattbusel.github.io/app-pages/curve/) | [privacy](https://mattbusel.github.io/app-pages/curve/privacy.html) |
| Fairway Ledger | [support](https://mattbusel.github.io/app-pages/fairway-ledger/) | [privacy](https://mattbusel.github.io/app-pages/fairway-ledger/privacy.html) |
| Ironbook | [support](https://mattbusel.github.io/app-pages/ironbook/) | [privacy](https://mattbusel.github.io/app-pages/ironbook/privacy.html) |
| Minder | [support](https://mattbusel.github.io/app-pages/minder/) | [privacy](https://mattbusel.github.io/app-pages/minder/privacy.html) |
| Odometer | [support](https://mattbusel.github.io/app-pages/odometer/) | [privacy](https://mattbusel.github.io/app-pages/odometer/privacy.html) |
| Pawprint | [support](https://mattbusel.github.io/app-pages/pawprint/) | [privacy](https://mattbusel.github.io/app-pages/pawprint/privacy.html) |
| Pricebook | [support](https://mattbusel.github.io/app-pages/pricebook/) | [privacy](https://mattbusel.github.io/app-pages/pricebook/privacy.html) |
| Quiver | [support](https://mattbusel.github.io/app-pages/quiver/) | [privacy](https://mattbusel.github.io/app-pages/quiver/privacy.html) |
| Race Fuel | [support](https://mattbusel.github.io/app-pages/race-fuel/) | [privacy](https://mattbusel.github.io/app-pages/race-fuel/privacy.html) |
| Rooms | [support](https://mattbusel.github.io/app-pages/rooms/) | [privacy](https://mattbusel.github.io/app-pages/rooms/privacy.html) |

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
4. In App Store Connect, set the support URL to `https://mattbusel.github.io/app-pages/<app-slug>/` and the privacy policy URL to `https://mattbusel.github.io/app-pages/<app-slug>/privacy.html`.

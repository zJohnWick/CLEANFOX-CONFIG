![GitHub Maintained](https://img.shields.io/badge/open%20source-yes-orange)
![GitHub Maintained](https://img.shields.io/badge/maintained-yes-yellow)

# Cleanfox
user.js for clean, fast, private Firefox.

## Getting started
*If you don't have firefox already: [Get Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)*

1) Download the user.js file [here](https://github.com/zJohnWick/Cleanfox-Config/raw/main/user.js) (Right click > `Save Link As…`).
2) Open Firefox. In the URL bar, type `about:profiles` and press **Enter**.
3) For the profile you want to use (or use default), click **Open Folder** in the **Root Directory** section.
4) Move the `user.js` file into the folder.
5) Done.

## Difference with the Betterfox Config.
* Changed/Added a few things in Betterfox.

| Fox Type | Line # | Description | Status |
| :---: | :---: | :---: | :---: |
| `Peskyfox.js` | 274 | Pinned Shortcuts on New Tab | On |
| `Peskyfox.js` | 330, 336 | Always ask where to download | Off |
| `Securefox.js` | 181 | Battery status tracking | Off |

* Additional things added according to personal preference.

| Code | Description |
| :---: | --- |
| `browser.urlbar.speculativeConnect.enabled` | Disable URL bar, making speculative connections |
| `ui.key.menuAccessKeyFocuses` | Disable menu popping up when press ALT key |

## Note
> [!IMPORTANT]
> There are a few extra things available at the bottom of the user.js file. Enable them if you need.

## Recommended Addons
1) [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) - Adblocker | [Recommended filters](https://github.com/yokoffing/filterlists#guidelines)
2) [Enhancer for YouTube™](https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube/) - Additional features for YouTube
3) [Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/) - Automatically learns to block invisible trackers
4) [Sessionic](https://addons.mozilla.org/en-US/firefox/addon/sessionic/) - Save, manage and restore sessions

## Additional Readings
* [Firefox Hardening Guide](https://brainfucksec.github.io/firefox-hardening-guide)

## Credit
* Many thanks to the [Betterfox](https://github.com/yokoffing/Betterfox) team for the base config.

<div align='center'>
  <a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=48832&s=3' border='0' alt='Free Website Counter'></a><br/>
since 05 Feb 2024</div>

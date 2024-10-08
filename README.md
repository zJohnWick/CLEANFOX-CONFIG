# CLEANFOX Firefox Config
user.js for clean, fast, private Firefox.
- Tested this user.js on Firefox, Firefox Nightly, Firefox ESR.

## Getting started
*If you don't have firefox already: [Get Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)*

1) Download the user.js file [here](https://github.com/zJohnWick/Cleanfox-Config/raw/main/user.js) (Or download source > [Click Here](https://github.com/zJohnWick/CLEANFOX-CONFIG/archive/refs/heads/main.zip))
2) Open Firefox. In the URL bar, type `about:profiles` and press **Enter**.
3) For the profile you want to use (or use default), click **Open Folder** in the **Root Directory** section.
4) Move the `user.js` file into the folder.
5) Done.

## Difference with Betterfox Config.
* Changed a few things in Betterfox.

| Fox Type | Line # | Description | Status |
| :---: | :---: | :---: | :---: |
| `Peskyfox.js` | 274 | Pinned Shortcuts on New Tab | On |
| `Securefox.js` | 192 | Battery status tracking | Off |

* Following things added based on personal preference.

| Code | Description |
| :---: | --- |
| `browser.urlbar.speculativeConnect.enabled` | Disable URL bar, making speculative connections |
| `ui.key.menuAccessKeyFocuses` | Disable menu popping up when press ALT key |
| `browser.tabs.warnOnClose` | Ask confirmation when closing a window with multiple tabs |
| `browser.urlbar.openViewOnFocus` | Disable address bar popping out |

## Note
> [!IMPORTANT]
> There are a few extra things available at the bottom of the user.js file. Enable them if you need.

## Recommended Addons
1) [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) - Adblocker | [Recommended filters](https://t.me/jCloud1/470)
2) [Enhancer for YouTube™](https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube/) - Additional features for YouTube
3) [Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/) - Automatically learns to block invisible trackers
4) [Sessionic](https://addons.mozilla.org/en-US/firefox/addon/sessionic/) - Save, manage and restore sessions
4) [Duplicate Tab Shortcut](https://addons.mozilla.org/en-US/firefox/addon/duplicate-tab-shortcut/) - Press Alt+Shift+D to duplicate the current tab

## Additional Readings
* [Check what information your device exposes to the web](https://personaldata.info/#about)
* [Firefox Hardening Guide](https://brainfucksec.github.io/firefox-hardening-guide)
* [archlinux article about Firefox configuration](https://wiki.archlinux.org/title/Firefox/Privacy#Configuration)

## Credit
* Many thanks to the [Betterfox](https://github.com/yokoffing/Betterfox) team for the base config.

<div align='center'>
  <a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=48832&s=3' border='0' alt='Free Website Counter'></a><br/>
since 05 Feb 2024</div>

# youtube-plus
A YouTube theme

# NOTICE
This theme is in its early stages. Expect lots of bugs, inconsistencies, frequent updates and the like. It's not compatible with the light theme yet, and I can't guarantee it'll work on anything but Chrome.

Because of this, the theme's main installation method uses @import to always be up-to-date with this repository.

# Installation
The steps are the same for all browsers, as long as you're using Stylish.
## Stylish for Chrome and Chromium-based Browsers
[Stylish on the Google Chrome Web Store](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe).
## Stylish for Firefox
[Stylish on Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/stylish/)
## Stylish for Opera
[Stylish on Opera Add-ons](https://addons.opera.com/en/extensions/details/stylish/)
## (Unofficial) Stylish for Safari
[Stylish at Safari Extensions](https://safari-extensions.apple.com/details/?id=com.sobolev.stylish-5555L95H45)

# Installation steps:
- Click the Stylish icon in your browser's navigation bar
- Click the three dots in the popup
- Click "Create New Style"
- Paste this:
```
@import url(https://rawgit.com/PlusInsta/youtube-plus/master/styles.css);
```
- If you have Ghostery or another tracking blocker, add this to avoid blank spaces:
```
#ad-iframe { display: none };
#player-ads { display: none }
```
_Note: This doesn't actually block ads. It only prevents empty spaces from appearing if you're using tracking blockers._
- Click "Specify" at the bottom of the page
- Select "URLs on the domain"
- Enter `youtube.com`
- Give the theme a name
- Save

The theme should load immediately after saving.

# Screenshots
Homepage

![Homepage Screenshot](https://dl.dropboxusercontent.com/s/rhbc8ywonxpmk2x/HomepageSS.png)

Videos

![Video Example Screenshot](https://dl.dropboxusercontent.com/s/lignkzrftward20/VideoSS.png)

Channels

![Channel Example Screenshot](https://dl.dropboxusercontent.com/s/ivxm12o6gqkbhp6/ChannelSS.png)
_Note: I picked PewDiePie simply because his channel makes use of all the YouTube features. I do not support his content._

# Firefox Nova - Connected Tabs Fix

A lightweight `userChrome.css` customization for Firefox Nova that visually connects the floating tab strip to the browser toolbar while preserving rounded tab styling.


## Preview

| Before | After |
|--------|-------|
| ![Before](images/before.png) | ![After](images/after.png) |


## Features

* **Design Preservation:** Maintains Nova's signature rounded tab aesthetic.
* **UI Polish:** Fixes clipping issues around the first tab.
* **Zero Dependencies:** Requires no extensions, addons, or external build tools.


## Compatibility
* Requires a Firefox version with the Nova interface and CSS nesting support.
* `userChrome.css` customization support enabled.
* **Tested on:** Firefox 158.0.1 (64-bit), Linux Mint


## Installation

1. Open **`about:support`** in your Firefox address bar.
2. Locate the **Profile Folder** row and click **Open Directory** (or **Show in Finder**).
3. Create a folder named `chrome` inside your profile directory if it does not already exist.
4. Back up your existing `userChrome.css` file if present.
5. Download this repository's `userChrome.css` file into your newly created `chrome` folder. 
   > *Note:* If you already use custom CSS rules, merge the relevant rules rather than overwriting your entire file.
6. Navigate to **`about:config`** in Firefox, accept the warning, and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
7. Restart Firefox to apply the changes.


## License

Copyright (C) 2026 Abhishek B.
Distributed under the [GNU General Public License v3.0 or later](LICENSE).

# Oneline Proton

_An oneline userChrome.css theme for Firefox, which aims to keep the Proton experience._

![Oneline Proton screenshot](screenshot.png)


## Features

- **Minimal**: Oneline Proton has been made trying to keep all the Proton experience, but with a cleaner interface.
- **Practical**: The oneline interface allows you to keep a higher visible space and focus on what matters.
- **Clean**: back/forward buttons keep hidden when disabled, and some url icons are hidden until you hover them.
- **Flexible**: Support for compact, normal, and touch densities.
- **Themeable**: You can still using custom themes with full compatibility.
- **Customizable**: You are able to change settings like navbar's width, animation speed, and hidden elements at the top of the userChrome.css file.


## Installation

1. In the searchbar, type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`** and change it to **True**.
3. Go to your Firefox profile:
   - In the searchbar, type `about:support` and press `Enter`.
   - Search for **`Profile Directory`** and click on **`Open Directory`** button.
4. Create a folder and name it **`chrome`** (with lowercase).
5. Paste userChrome.css file into the folder.
6. Restart Firefox
7. Enjoy your new Firefox!


## Customization

- You can change some settings inside the userChrome.css file.
- Use `--navbarWidth` variable to change the width of the navbar (you can use px units for a fixed width, or vw units for a percentage one).
- Use `--animationSpeed` variable to change (or disable) animations.
- Hide or show the elements you want by commenting or uncommenting them:
```css
/* This element is hidden */
/* "Shield" icon */
#tracking-protection-icon-container {display: none !important}

/* This element is visible */
/* This is the "Search with" indicator on the urlbar */
/* #urlbar-search-mode-indicator {display: none !important} */
```


# Eric's Zen UI Tweak Box

Several optional UI changes for the Zen Browser. Completely changes the appearance of the browser with all tweaks enabled.

**Exit Button Right Padding theme users** - You don´t need that theme when using this one.

## Available Tweaks

### `!macos:uc.erics-zen-ui-tweak-box.exit-button-padding-right.enabled`

**Description:** Adds some spacing to the right of the exit button. This is particularly useful when using certain Gnome extensions This setting does the exact same thing as the `Exit Button Right Padding` theme.

### `uc.erics-zen-ui-tweak-box.fun-colors.enabled`

**Description:** Enables a cool gradient as the background.

### `uc.erics-zen-ui-tweak-box.tab-bar-top-padding.enabled`

**Description:** Removes the top padding from the tabs side panel so it's aligned with the page canvas.

### `uc.erics-zen-ui-tweak-box.page-canvas-shadows.enabled`

**Description:** Adds shadows to the edges of the page canvas.

### `uc.erics-zen-ui-tweak-box.remove-url-bar-border.enabled`

**Description:** Removes the border around the URL Bar.

### `uc.erics-zen-ui-tweak-box.url-bar-tweaks.enabled`

**Description:** Introduces various visual enhancements to the URL bar, including hover effects and background color changes.

### `uc.erics-zen-ui-tweak-box.floating-url-bar-tweaks.enabled`

**TO BE USED ONLY WITH THE FLOATING URL BAR EXTENSION**

**Description:** Floating URL Bar appearance tweaks with different background color and shadows.

### `uc.erics-zen-ui-tweak-box.new-tab-button-text.enabled`

**Description:** Adds a "New Tab" text next to the new tab button when the sidebar is expanded.

### `uc.erics-zen-ui-tweak-box.new-tab-separator-when-no-unpinned-tabs.enabled`

**Description:** Adds a separator before the new tab button if there are no unpinned tabs separating it from the pinned tabs. (Close all unpinned tabs to see it).

### `uc.erics-zen-ui-tweak-box.pinned-tabs-layout.enabled`

**Description:** Tweaks the layout of the pinned tabs with background, hover effects and new selected tab style.

### `uc.erics-zen-ui-tweak-box.workspace-button-tweaks.enabled`

**Description:** Tweaks the appearance of the workspace button.

### `uc.erics-zen-ui-tweak-box.tab-button-tweaks.enabled`

**Description:** Tweaks the appearance of the tab buttons with background, hover effects and new selected tab style.

### `uc.erics-zen-ui-tweak-box.toolbar-button-tweaks.enabled`

**Description:** Tweaks the appearance of the toolbar buttons.

## Tweaking the background gradient

If you wish to change the colors of the gradient you can set the following variables in your `userChrome.css` in the `chrome` folder inside of you profile folder:

- `--ezuitb-background-gradient-start: {YOUR_COLOR} !important;` - the start color of the gradient.
- `--ezuitb-background-gradient-end: {YOUR_COLOR} !important;` - the end color of the gradient.
- `--ezuitb-background-gradient-angle: 140deg !important;` - rotates the gradient.

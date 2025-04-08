# 🌹🦊

This is a collection of CSS files to customize the [Midnight Discord theme](https://github.com/refact0r/midnight-discord) to my taste + some QuickCSS tweaks for hiding UI elements I find to be clutter and a waste of space.

## How to use:

Requirements:

- Have Vencord or Vesktop installed -> [download link](https://vencord.dev/download/)

### Theme

Instructions:

Go to `Settings -> Themes -> Online Themes` and paste the following link:

```
https://raw.githubusercontent.com/sophiiss/midnight-rosefox/main/midnight-rosefox-refresh.theme.css
```

### QuickCSS

Instructions:

Go to `Settings -> Themes -> Edit QuickCSS` and paste the following line:

```css
@import url('https://raw.githubusercontent.com/sophiiss/midnight-rosefox/main/quick.css');
```

There are some variables I added to make the QuickCSS more customizable.<br>You can insert them in your QuickCSS below the `@import` line, then replace `true` with `false` wherever you see fit.

```css
body {
  --hide-context-menu-items: true; /* for right-click menu on any user */
  --hide-nitro-shop-recentapps: true; /* tabs above dms */
  --hide-gift-button: true; /* gift button on message box */
  --hide-apps-button: true; /* apps button on message box */
  --hide-toolbar-items-dm: true; /* buttons above chat, 'Start Video Call', 'Create Group DM', etc. */
  --hide-toolbar-items-server: true; /* buttons above chat on server, like 'Threads' */
  /* note: when hiding server toolbar, you can use Ctrl+U to open/close the members list */
}
```

All done!

## Screenshots

#### Context menu before/after

![07_111445_Discord](https://github.com/user-attachments/assets/9ba0d0d9-d292-4464-b825-7144a6be52de)

#### General UI

![image](https://github.com/user-attachments/assets/cbb3e910-16ec-4987-82e9-5cd82fe3c18d)

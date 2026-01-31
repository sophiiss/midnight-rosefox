# 🌹🦊

This is a collection of CSS files to customize the [Midnight Discord theme](https://github.com/refact0r/midnight-discord) to my taste + some QuickCSS tweaks for hiding UI elements I find to be clutter and a waste of space.

## How to use:

Requirements:

- Have Vencord or Vesktop installed -> [download link](https://vencord.dev/download/)

### Theme

Instructions:

Go to `Settings -> Themes -> Online Themes` and paste the following link:

```
https://sophiiss.github.io/midnight-rosefox/midnight-rosefox-refresh.theme.css
```

### QuickCSS

Instructions:

Go to `Settings -> Themes -> Edit QuickCSS` and paste the following lines:

```css
@import url('https://sophiiss.github.io/midnight-rosefox/quick.css');

body {
   /* items on the right-click menu on users */
  --hide-context-menu-items: true;

  /* tabs above dms */
  --hide-nitro-shop-recentapps: true;

  /* gift button on message box */
  --hide-gift-button: true;

  /* apps button on message box */
  --hide-apps-button: true;

  /* close, minimize, maximize buttons */
  /* can be also set to 'toolbox', in case you have the Vencord Toolbox plugin */
  --hide-window-controls: false;

  /* buttons above chat, 'Start Video Call', 'Create Group DM', etc. */
  --hide-toolbar-items-dm: true;

  /* buttons above chat on server, like 'Threads' */
  /* note: when hiding server toolbar, you can use Ctrl+U to open/close the members list */
  --hide-toolbar-items-server: true;
}
```

There are some variables included to make the CSS more customizable.<br>You can set them to `true` or `false`, or also `toolbox` in the case of window controls.

All done!

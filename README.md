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
There are two QuickCSS files. The first one hides elements I find useless through the UI, and the second one which hides items from the user context menu (right-click on DM).
Both work together.

#### Standard hiding
Go to `Settings -> Themes -> Edit QuickCSS` and paste the following line:
```css
@import url('https://raw.githubusercontent.com/sophiiss/midnight-rosefox/main/quick.css');
```

#### Context menu hiding
Do the same and add this line below the first one:
```css
@import url('https://raw.githubusercontent.com/sophiiss/midnight-rosefox/main/quick-context-menu.css');
```

All done!

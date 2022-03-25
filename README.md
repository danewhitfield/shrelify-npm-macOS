# shrelify

## This package will turn your console and output text colours to green!

### you'll also have awesome green accent colours almost everywhere!

### Shrel is love <3

To install this beautiful package, simply type into your project terminal:

```
npm i shrelify
```

Once you have the Shrelify package installed you can require it in:

```
const shrelify = require('shrelify')
```

To run the shrelify script you just need to invoke the function:

```
shrelify()
```

Make sure to run:

```
node yourFileName.js
```

# How do I go back to my previous settings?

If for some bizarre reason you would like to revert back, here's how...

### Navigate to File > Preferences > Settings > Workbench > Appearance

Underneath 'Color Customizations' select 'Edit in settings.json'

Once in the JSON file you can remove this section:

```
"workbench.colorCustomizations": {
      "terminal.foreground": "#00fd61",
      "errorForeground": "#fd0000",
      "scrollbarSlider.background": "#00fd61",
      "sideBar.foreground": "#00fd61",
      "sideBarTitle.foreground": "#00fd61",
      "sideBarSectionHeader.foreground": "#00fd61",
      "panelTitle.activeForeground": "#00fd61",
      "panelTitle.inactiveForeground": "#009b05",
      "statusBar.foreground": "#00fd61",
      "statusBar.border": "#00fd61",
      "notificationCenterHeader.foreground": "#00fd61",
      "notifications.foreground": "#00fd61",
      "notificationLink.foreground": "#00fd61",
}
```

Make sure to save the settings.json file and it will instantly go back to how it was :)

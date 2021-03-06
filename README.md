## ONE light UI theme

A light UI theme that adjusts to most Syntax themes.

![one-light-ui](https://cloud.githubusercontent.com/assets/378023/6241878/95c31112-b768-11e4-9ac0-46a626f4963d.png)

There is a matching [Syntax theme](https://atom.io/themes/one-light-syntax), but most other Syntax themes work fine as well.

![one-light-grid](https://cloud.githubusercontent.com/assets/378023/6241877/95bee43e-b768-11e4-96e8-bb80ae4015ae.png)

### Install

This theme is installed by default with Atom and can be activated by going to the __Settings > Themes__ section and selecting "One Light" from the __UI Themes__ drop-down menu.

### Customize

You can scale the whole UI up or down by adding this to your `styles.less`:

```css
.theme-one-light-ui { font-size: 14px; }
```

It's also possible to only change certain areas (Use the DevTools to find the right selectors):

```css
.theme-one-light-ui {
  .tab-bar { font-size: 18px; }
  .tree-view { font-size: 14px; }
  .status-bar { font-size: 12px; }
}
```

### FAQ

__Why do the colors change when I switch Syntax themes.__
This UI theme uses the same background color as the choosen Syntax theme. In case that Syntax theme has a dark background color, it only uses its hue, but otherwise stays light. This lets you use light-dark combos.

# Monitor window switcher 2

GNOME shell extension to improve the window or application switcher on dual (or more) monitor setups. It has the following options:

![Screenshot](screenshot.png)

- Shows the window or application switcher on the current monitor (instead on primary monitor).
- Filter windows or applications by the monitor they are open on (instead of windows or applications opened in all monitors).
- Filter applications by the workspace they are open on (instead of applications opened in all workspaces).

To install the extension run the following commands:

```
git clone https://github.com/lepa22/window-app-switcher-on-active-monitor.git
mkdir -p ~/.local/share/gnome-shell/extensions/window-app-switcher-on-active-monitor@NiKnights.com
cp -r window-app-switcher-on-active-monitor/* ~/.local/share/gnome-shell/extensions/window-app-switcher-on-active-monitor@NiKnights.com
```

Then restart GNOME Shell by pressing <kbd>Alt</kbd>+<kbd>F2</kbd>, entering `r`, and pressing <kbd>Enter</kbd>.

**Note:** This extension is a fork of https://github.com/gedzeppelin/monitor-window-switcher. I made this fork because the original extension wasn't getting updated for recent GNOME versions. I know almost nothing about JavaScript and GNOME Shell extensions, so I will probably be not able to do much if GNOME does any changes to its extensions API. I also may not be able to fix any bugs if reported. Feel free to do pull requests though!

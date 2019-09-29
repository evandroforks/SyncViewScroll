# syncViewScroll Package For sublimeText

--------

## About

Sync View Scroll is a simple [Sublime Text 3](http://www.sublimetext.com/3 ) plug-in which allows sync scroll among views.

*note: st2 should work, if you find any bug, please open an issue at github.*


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `SyncViewScroll` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## Usage

1. In one View, goto `View`, check the `Sync Scroll` checkbox. (OR using command palette with 'syncscroll')
2. Repeat step 1 on all other view you want to sync view
3. Scroll on one of these views, the others sync scrolls.
4. You can set `{ "keys": [your_keys_here], "command": "toggle_sync_scroll" }` in user's keymap to trigger sync scroll(thanks to [@KaduAmaral](https://github.com/KaduAmaral))

## Author
zzjin tczzjin#gmail.com

## Thanks
 [@FichteFoll](https://github.com/FichteFoll) to suggest add command palette support
 [@pribilinskiy](https://github.com/pribilinskiy) to report windows menu toggle bug
 [@spywhere](https://github.com/spywhere) to report is_check error in some case views are not inited
 [@Kl0tl](https://github.com/Kl0tl) to add support for horizontal scroll and implement the configureable staus bar text, Thanks!
 [@getify](https://github.com/getify) and [@CSester](https://github.com/CSester) to report st2 activate bug

## TODO

* add context menu support.
* improve sync scroll delay.

### Please use github to submit Bugs and Feature Requests.

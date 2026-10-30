# Tab Numbers Synced

Jump straight to any of your first eight tabs with Ctrl+1 through Ctrl+8 (Cmd on macOS). Ctrl+9 jumps to the last tab. This mod shows a number on each tab, and that number is the key that takes you there.

## Why this fork exists

This is a fork of [Tab Numbers](https://github.com/philmard/tab-numbers) by philmard. All the styling and options come from that mod.

The store version of Tab Numbers numbers every tab in the space, including tabs hidden inside a collapsed folder. Zen's shortcuts skip hidden tabs, so the numbers and the shortcuts disagree once a folder is collapsed ([issue #32](https://github.com/philmard/tab-numbers/issues/32)).

For example: tabs 4, 5 and 6 sit in a folder, and you collapse it. The tab below the folder still shows 7, but Zen now treats it as tab 4. Pressing Ctrl+7 takes you to a different tab.

This fork numbers tabs the same way Zen's shortcuts count them. These tabs don't get a number:

- tabs inside a collapsed folder
- pinned tabs while the space's pinned section is collapsed

The selected tab and any tab Zen keeps showing in a collapsed folder still get a number, because Zen counts them too.

## Setup

1. If you have the original Tab Numbers mod installed, disable it. Both mods style the same numbers and share settings, so running both can conflict.
2. Install this mod.
3. On Linux, Zen's default shortcut is Alt+1 through Alt+8. To use Ctrl instead, open Settings > Keyboard Shortcuts and change "Select tab #1" through "Select tab #8" and "Select last tab". Windows already uses Ctrl and macOS uses Cmd.

## Options

Same as the original: number size, bold, background shape and color, and which side of the tab the number sits on, separately for expanded and compact tabs.

<img width="227" alt="Blue rectangular numbers" src="https://github.com/user-attachments/assets/e0c3d48c-12c1-4db8-a519-260cb6687ad1">
<img width="230" alt="Orange round numbers" src="https://github.com/user-attachments/assets/df859dd3-7caa-4cdb-abec-0d017ff1e48a">
<img width="230" alt="Grey numbers on the left" src="https://github.com/user-attachments/assets/731b1593-bf16-43a9-8907-b11ec9567b10">

## Credit

Original mod by [philmard](https://github.com/philmard). Like every mod in the Zen store, this one is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

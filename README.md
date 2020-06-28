# ANSI remaps for UK PC keyboard layout in Windows 10

I used the Microsoft Keyboard Layout Creator to create a custom keyboard layout for the UK English locale.

Installing this package and switching your keyboard layout to `United Kingdom - Custom ANSI` will swap the keymap for `Shift + 2` and `Shift + '`.

Everything else remains intact for a UK ISO PC layout.

## Installation Steps

1. Download the release zip
2. Unzip and run the installer on your Windows 10 PC
3. Open Settings -> Time & Language -> Language (alternatively type `Language Settings` into Windows Search)
4. Click on Keyboard
5. Select `United Kingdom - Custom ANSI` as your default layout

You could also make the change from the language preferences in the taskbar. After it is installed you should see `ENG UK` in the taskbar next to the calendar. Click that and select `United Kingdom - Custom ANSI` as your new keyboard layout.

## Why did I create this?

ANSI (aka "US") PC keyboard layouts are slightly different to the UK ISO PC layout. To add to the fun, the UK MacBook Pro keyboards find themselves in a weird in-between state.

Some notable differences between UK and US layouts.

| Key       | UK  | US  | Mac UK |
| --------- | --- | --- | ------ |
| Shift + ' | @   | "   | "      |
| Shift + 2 | "   | @   | @      |
| Shift + 3 | £   | #   | £      |

The UK ISO keyboard has a special key with # that shifts to ~. There are also a few other differences between the three different keyboard layouts.

I used ANSI layout when growing up in South Africa and have used a UK MacBook Pro for most of my time in the UK.

However, recently I have found myself regularly using both a UK MacBook Pro and a UK PC laptop.

The muscle memory for hitting `Shift + 2` to get @ or shifting the single quote into a double quote was proving frustrating on the UK PC keyboard.

And so I created this to always use ANSI keymaps for @ and ".

## Bonus tips

If you too regularly switch between Windows 10 and MacOS, I strongly encourage you to install Windows 10 Powertoys.

This will allow you to create a few custom key remaps.

I recommend the following

| Keymap Source | Keymap Target |
| ------------- | ------------- |
| Win + Q       | Alt + F4      |
| Win + W       | Ctrl + W      |
| Win + T       | Ctrl + T      |

Now you won't battle muscle memory and can use some MacOS shortcuts in Windows.

`Cmd/Win + Q` feels way more comfortable a finger stretch to close down an app imho.

Thanks to `Cmd/Win + W` and `Cmd/Win + T` it is the same to quickly open a new tab in the browser.

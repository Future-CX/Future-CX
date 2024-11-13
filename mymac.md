## My Mac Setup

This document contains info on all the apps / tools / settings I use on my Mac.

## What Macbook do I have?

I recently moved from an Intel Macbook Pro (2019) to a shiny new Macbook Pro M4 Max.

#### Specs
- M4 Max (16 CPU, 40 GPU)
- 48 GB memory
- 1TB SSD
- Standard Display

See my configuration on [apple.com](https://www.apple.com/go/dt/sharelist?sfid=10078&slid=AAAjAAIBiOgAFSema1IopUQ5drvl1iqfZZv9aEp8KBT4R7KEZvTZM8h9E1B6G4HqBEpuyXmiAAIB0u0tV6wuXcKd-3As0CnpILmFpaNkXxfTSkRo4OI1lgY)

## MacOS settings

### Desktop & Dock settings
- I am reducing the size of the dock and autohiding it
- I keep the position of the Dock to the bottom
- I like the minimize windows into the application icon to keep the Dock clean
- I uncheck the option to show suggested and recent apps in Dock
- I like to keep a clean desktop so uncheck the option 'Show Items'
- I dont use Stagemanager currently
- I set the Widget style to Monochrome
- **The new feature in Sequoia for resize and arrange windows is awesome!**


### Finder settings
Tip: When in a Finder window, press CMD+, to open Finder settings. This shortcut works in most applications.
- I unchecked all items to show on the desktop to keep the desktop clean at all times
- For new Finder windows I set it to the Home folder
- I like to use tabs in Finder. Use CMD+T to open a new Finder tab
- I prefer to use Finder in List view
- I disabled all the tags in Finder settings, as I don't really use the feature
- In the Sidebar the only items I have checked are Applications, Downloads, Home, Macbook Pro, External Disks, Drives, Cloud Storage and Connected Servers
- I uncheck the Show warning when changing an extension in Advanced Settings
- I changed the Search setting to Current Folder
- I enabled the Show Path Bar and Show Status Bar in Finder View Settings

## Apps I use

### Replace Spotlight with Raycast

I found Raycast more intelligent and learning my behaviour when launching apps. It has a build in calculator. And it can be set to search in Google by just typing 's' and then my search query. And there are many more options, extensions and cool features.

1. Download Raycast from [Raycast.com](https://www.raycast.com/) and install it.
2. Launch the app
3. Setup the app using the Wizard
   - Since MacOs Sequoia has a new feature for Window Management, I dont need Raycast for it
4. To replace Spotlight with Raycast we need to change the keyboard shortcuts
  - First Uncheck the keyboard shortcut to launch Spotlight in System Settings > Keyboard > Keyboard shortcuts > Spotlight
  - Next Record and set the keyboard short to launch Raycast to CMD-Space in Raycast settings

### Homebrew Package Manager

[Homebrew](https://brew.sh/) allows us to install tools and apps from the command line.

To install it, open up the built in `Terminal` app and run this command:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

This will also install the xcode build tools which is needed by many other developer tools.

After Homebrew is done installing, we will use it (via RayCast) to install everything else we need.


#### RayCast Homebrew Plugin

Install the [RayCast Homebrew Plugin](https://www.raycast.com/nhojb/brew) so we can easily install formulae (CLI tools) and casks (Apps) directly from RayCast.

### Hidden Bar

If you have several apps running that have menu bar icons, [Hidden Bar](https://github.com/dwarvesf/hidden) will let you choose which ones should be hidden after a timeout. This cleans things up if you have a ton of background apps running.

Search for `hiddenbar` in RayCast `brew search` or:

```sh
brew install hiddenbar
```

### Arc Web Browser

After many years of using Chrome I recently moved to Arc as my primary web brower.

Download and install Arc Web Browser from [Arc.net](https://arc.net/)

### VS Code

VS Code is my main IDE

Check my dedicated page on [VS Code](https://github.com/Future-CX/Future-CX/blob/main/vscode.md)

### Warp Terminal

I am using Warp as my primary terminal


## Other apps I use regurlarly

- Apple Notes and Freeform
- 

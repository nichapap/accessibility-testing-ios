# Accessibility Testing on iOS

## Prerequisite

- ~~BNC Nexus access~~
- ~~BNC Github access~~
- Xcode

## Setup Xcode

1. Open `Xcode`, go to `Xcode > Preferences`
2. Go to `Components` tab
3. Install `iOS 14.0`
4. Go to `Xcode > Open Developer Tool > Simulator`
5. On `Simulator`, go to `File > New Simulator`.
   - Set the `Deveice Type` to your choice of iPhone. _Recommened: iPhone 8 for now_
   - Set the `OS Versionn` to `iOS 14.0`
   - Click `Create`
6. Go to `File > Open Simulator > Simulator > iOS 14.0` then select the device of your choice. _Recommened: iPhone 8 for now_

## How to use Accessibility Inspector

![Accessibility Inspector](/img/AccessibilityInspector.png 'Accessibility Inspector')

1. Open `Xcode`, go to `Xcode > Open Developer Tool > Accessibility Inspector`
2. Click the button after `Inspected Emement`
3. Move your cursor to iPhone screen then click.
4. Green hover indicated the position of target. Or look for the symbol: ⌖
5. `Navigation` can be use to navigate the target back or forth and toggle on/off the speech.
   - 💬: toggle on/off the VoiceOver
   - ＜: navigate the target back
   - ▶️: Auto navigating with VoiceOver
   - ＞: navigate the target forth
6. `Hierarchy` is the list of elements on the selected target.

## Setup environment in Terminal

1. Install `Homebrew` with this command:
   <br/>`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` <br /> _Please check homebrew export path at the end of the installation_
2. Install node nvm and yarn via hombrew: `brew install node nvm yarn`
<br /> _Please check usage of each package at the end of the installation_
<!-- 3. Installing **lts/dubnium** using nvm: `nvm install lts/dubnium` -->

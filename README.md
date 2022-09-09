# HA-AppleTV-Remote-Card

A very simple `picture-elements` YAML config with custom images to match the built in IOS remote

## Features

-   Power on and Power off with the same power button
-   Play/Pause with one button
-   Styled directly on the latest IOS remote UI
-   Back button to redirect home if you use this in a stand a lone dashboard
-   Hold the Home button and release to open the control centre just oike on the physical remote
-   Options for both "plus-minus" and VOL up down volume rockers
-   Optional back button

![Both types of Volume](https://github.com/HenrySeed/HA-AppleTV-Remote-Card/blob/main/eithor_or.png?raw=true)

## Installation

1. Copy the contents of `remote-card.yaml` into a `picture-elements` lovelace card.
2. Change `remote.living_apple_tv` and `media_player.living_apple_tv` to your Apple TV remote and media entities
3. Make a script called `apple_tv_power` (or something else and update the yaml to fit). Copy the contents of `apple_tv_power.yaml` into it
4. Update the `navigation_path: home` to point to the dashboard you send this to.
5. Choose a different image from `Images/` to remove the back button or change the volume rocker.

### Optionally

-   Save the images to your `/config/resources` folder (making that folder if necessary)
-   Change the image you point to, there are options for rounded corners and VOL vs +- Volume rockers

Credit to [douglampe](https://github.com/douglampe) for the idea [his repo](https://github.com/douglampe/ha-appletv-remote-card)

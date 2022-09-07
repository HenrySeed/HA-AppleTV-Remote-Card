# HA-AppleTV-Remote-Card

A very simple `picture-elements` YAML config with custom images to match the built in IOS remote

Credit to [douglampe](https://github.com/douglampe) for the original YAML setup and idea [his solution](https://github.com/douglampe/ha-appletv-remote-card)

![Both types of Volume](https://github.com/HenrySeed/HA-AppleTV-Remote-Card/blob/main/eithor_or.png?raw=true)

## Installation

1. Copy the contents of `remote-card.yaml` into a `picture-elements` lovelace card.
2. Change `remote.living_apple_tv` and `media_player.living_apple_tv` to your Apple TV remote and media entities
3. Make a script called `apple_tv_power` (or something else and update the yaml to fit). Copy the contents of `apple_tv_power.yaml` into it

### Optionally

-   Save the images to your `/config/resources` folder (making that folder if necessary)
-   Change the image you point to, there are options for rounded corners and VOL vs +- Volume rockers

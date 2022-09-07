# HA-AppleTV-Remote-Card
A very simple `picture-elements` YAML config with custom images to match the built in IOS remote

Credit to [douglampe](https://github.com/douglampe) for the original YAML setup and idea [his solution](https://github.com/douglampe/ha-appletv-remote-card)

## Installation

1. Copy the contents of `remote-card.yaml` into a `picture-elements` lovelace card.
2. Change `remote.living_apple_tv` and  `media_player.living_apple_tv` to your Apple TV remote and media entities
3. Save the images to your `/config/resources` folder (making that folder if necessary)
4. Update the YAML to point to the version of the image you want to use. Alternatly point the `image` referrence to ``
4. Make a script called `apple_tv_power` (or something else and update the yaml to fit). Copy the contents of apple_tv_power.yaml into it

Patched for custom hostname (avoid mdns reflection conflicts). Also listen on my netwrok interfaces

# homeassistant addon cups airprint
CUPS addon with working Avahi in reflector mode 

Tested with Home Assistant version **2025.2.3**

CUPS administrator login: **print**, password: **print** (can be changed in the Dockerfile)

Configuration data is stored in **/addon_configs/<slug>_cups** folder

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fzajac-grzegorz%2Fhomeassistant-addon-cups-airprint)

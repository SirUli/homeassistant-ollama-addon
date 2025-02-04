# Ollama Addon for Home Assistant

Please note that this addon runs with CPU acceleration or experimental Nvidia GPU Support (please report if it works for you!). For ROCm the support is still pending.

## Model Directory

All downloaded models are stored `/share/ollama` by default. For historic reasons you can also configure it for `/config/ollama`. Please make sure that you have sufficient space available.

## Ollama Integration

To download any models either use the API of Ollama or integrate with the Home Assistant Integration [Ollama](https://www.home-assistant.io/integrations/ollama/):

[![Add Ollama Integration](https://my.home-assistant.io/badges/brand.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=ollama)

Use the following data:

- URL: `http://76e18fb5-ollama:11434`

If you want to change the model, delete the integration (not the addon!) and restart the process for the configuration of the integration.

## Note on the UI Link

The UI Link is only there to check if the API of ollama is available. There is no chat functionality included in the official image of ollama.

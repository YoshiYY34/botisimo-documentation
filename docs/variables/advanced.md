# Advanced Example
This example shows you how to combine the `$(fetch)`, `$(urlencode)`, and `$(query)` response variables to make a !ascii command that translates the user's input into formatted ASCII text for Discord

## Example
    ```$(fetch http://artii.herokuapp.com/make?text=$(urlencode $(query))&font=colossal)```

`!ascii Hello World` ->

```text
888    888          888 888              888       888                  888      888
888    888          888 888              888   o   888                  888      888
888    888          888 888              888  d8b  888                  888      888
8888888888  .d88b.  888 888  .d88b.      888 d888b 888  .d88b.  888d888 888  .d88888
888    888 d8P  Y8b 888 888 d88""88b     888d88888b888 d88""88b 888P"   888 d88" 888
888    888 88888888 888 888 888  888     88888P Y88888 888  888 888     888 888  888
888    888 Y8b.     888 888 Y88..88P     8888P   Y8888 Y88..88P 888     888 Y88b 888
888    888  "Y8888  888 888  "Y88P"      888P     Y888  "Y88P"  888     888  "Y88888
```
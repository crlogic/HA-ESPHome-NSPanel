# HA-ESPHome-NSPanel
My work on the Sonoff NSPanel, based off much community effort.

![](https://github.com/crlogic/HA-ESPHome-NSPanel/blob/main/Grid.png)

# Random Notes to self..
- local Nextion objects lose state on page change, global do not
- ESPHome lambda `set_component_value` changes Nextion object.val where `send_command_printf("page0.bco=%i"` will change any applicable attribute

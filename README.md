# TP Pinboard

## Development Exports

```lua

-- @param location : requires the pinboard location that is located on the configuration file `Config.Locations`.
exports.tp_pinboard:openPinboardByName(location)
```

## Development Events

```lua

-- @param location : requires the pinboard location that is located on the configuration file `Config.Locations`.

TriggerEvent("tp_pinboard:openPinboardByName", location) -- client to client
TriggerClientEvent("tp_pinboard:openPinboardByName", source, location) -- server to client
```

# Client side
```lua
exports['nftyNotify']:showNotify("Title", "Message", Time, 'type')
```

# Server side
```lua
TriggerClientEvent('nftyNotify:showNotify', source, "Title", "Message", Time, 'type')
```

# Types:
```lua
success
error
info
warning
normal
police
ambulance
```

# Examples

```lua
exports['nftyNotify']:showNotify("Engine Status", "The engine has been start", 5000, 'succes')

exports['nftyNotify']:showNotify("Engine Status", "The engine has been stopped", 5000, 'error')
```

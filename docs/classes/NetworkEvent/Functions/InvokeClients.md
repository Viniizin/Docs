# InvokeClients

### Description

Sends a NetMessage from the server to all players. Can only be called from server.

Function of [NetworkEvent](/classes/NetworkEvent/)

#### Parameters

message `NetMessage`

#### Returns

`void`

### Example

```lua
local message = NetMessage.New()
message.AddString("key", "value")
netEvent.InvokeClients(message)
```

---
ns: CFX
apiset: shared
---
## SET_RESOURCE_KVP

```c
void SET_RESOURCE_KVP(char* key, char* value);
```

A setter for [GET_RESOURCE_KVP_STRING](#_0x5240DA5A), which fetches the string value for the set **key**.

## Parameters
* **key**: The key to set
* **value**: The value to write

Writes the **value** parameter under the **key** identifier.

## Examples
```lua
SetResourceKvp('mollis', 'vesuvius citrate')
```

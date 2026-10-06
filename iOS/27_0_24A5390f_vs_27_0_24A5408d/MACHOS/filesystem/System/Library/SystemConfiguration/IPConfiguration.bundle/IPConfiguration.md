## IPConfiguration

> `/System/Library/SystemConfiguration/IPConfiguration.bundle/IPConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ca48` | `0x5cd9c` | **`+0x354`** |
| `__TEXT.__oslogstring` | `0x61dc` | `0x623e` | **`+0x62`** |
| `__TEXT.__cstring` | `0x424b` | `0x425e` | **`+0x13`** |
| `__TEXT.__const` | `0x300` | `0x308` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-555.0.0.0.0
+557.0.0.0.0

-  CStrings:  1740
+  CStrings:  1744
CStrings:
+ "%s: %s present in new list"
+ "%s: can't find %s, building new list"
+ "add_or_set_service"
+ "frame_length %zu > sendbuf_len %u"
```

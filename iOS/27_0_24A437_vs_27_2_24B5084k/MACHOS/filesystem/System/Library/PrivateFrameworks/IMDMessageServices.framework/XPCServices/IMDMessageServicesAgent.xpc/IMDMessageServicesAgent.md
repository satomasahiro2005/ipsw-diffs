## IMDMessageServicesAgent

> `/System/Library/PrivateFrameworks/IMDMessageServices.framework/XPCServices/IMDMessageServicesAgent.xpc/IMDMessageServicesAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x774c` | `0x7814` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x1303` | `0x135b` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x85c` | `0x868` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  CStrings:  345
+  CStrings:  346
Functions:
~ sub_100006a2c : 1452 -> 1652
CStrings:
+ "Watchdog: message %@ on service '%@' is not retry-eligible, failing instead of retrying"
```

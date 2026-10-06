## com.apple.driver.AppleUSBDeviceNCM

> `com.apple.driver.AppleUSBDeviceNCM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x9460` | `0x9048` | **`-0x418`** |
| `__TEXT.__cstring` | `0x1027` | `0xff5` | **`-0x32`** |
| `__DATA_CONST.__const` | `0x25c8` | `0x25a8` | **`-0x20`** |
| `__TEXT_EXEC.__auth_stubs` | `0x650` | `0x630` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x328` | `0x318` | **`-0x10`** |
| `__TEXT.__const` | `0x88` | `0x80` | **`-0x8`** |

### Other Changes

```diff

-397.0.0.0.0
-  Functions: 226
+404.0.0.0.0
+  Functions: 222

-  CStrings:  133
+  CStrings:  130
CStrings:
- "disable-transport-rm"
- "ncm-no-trm"
- "submitPacketGated"
```

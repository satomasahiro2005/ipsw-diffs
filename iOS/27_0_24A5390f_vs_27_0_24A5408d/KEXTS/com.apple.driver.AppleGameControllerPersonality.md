## com.apple.driver.AppleGameControllerPersonality

> `com.apple.driver.AppleGameControllerPersonality`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1de0` | `0x26a4` | **`+0x8c4`** |
| `__DATA_CONST.__const` | `0x1388` | `0x1b20` | **`+0x798`** |
| `__TEXT.__os_log` | `0xc0` | `0x17e` | **`+0xbe`** |
| `__TEXT.__cstring` | `0x24b` | `0x2dc` | **`+0x91`** |
| `__DATA_CONST.__kalloc_type` | `0xc0` | `0x100` | **`+0x40`** |
| `__DATA.__common` | `0x88` | `0xb0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT_EXEC.__auth_stubs` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA.__bss` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xa0` | `0xa8` | **`+0x8`** |
| `__DATA_CONST.__mod_init_func` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__mod_term_func` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-14.0.21.0.0
-  Functions: 57
+14.0.24.0.0
+  Functions: 77

-  CStrings:  29
+  CStrings:  38
CStrings:
+ "121111121222121211111112112"
+ "GCIOMatchVirtual"
+ "RegisterService"
+ "SteamControllerUserEventDriver"
+ "SteamControllerUserEventDriver connected; registering service"
+ "SteamControllerUserEventDriver disconnected; terminating"
+ "SteamControllerUserEventDriver::handleStart(<IOHIDInterface %#010llx>)"
+ "bInterfaceNumber"
+ "site.SteamControllerUserEventDriver"
```

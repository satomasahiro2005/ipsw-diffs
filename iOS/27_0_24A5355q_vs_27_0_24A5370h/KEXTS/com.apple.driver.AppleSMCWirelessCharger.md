## com.apple.driver.AppleSMCWirelessCharger

> `com.apple.driver.AppleSMCWirelessCharger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x5e0` | **`+0x5e0`** |
| `__TEXT_EXEC.__text` | `0x10bf8` | `0x11028` | **`+0x430`** |
| `__TEXT.__cstring` | `0x36fa` | `0x377d` | **`+0x83`** |
| `__TEXT.__os_log` | `0x5b1` | `0x5f0` | **`+0x3f`** |
| `__DATA_CONST.__auth_got` | `0x2d0` | `0x2f0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1040` | `0x1048` | **`+0x8`** |

### Other Changes

```diff

-147.0.0.0.1
-  Functions: 210
+153.0.0.0.0
+  Functions: 211

-  CStrings:  457
+  CStrings:  461
CStrings:
+ "%s: FFB comms enabled\n"
+ "%s: resetComms blocked — streams active, puck likely not ready for GetString yet\n"
+ "%s: resetting stream %d sequence state (rxSeq=%d, txSeq=%llu)\n"
+ "12111112122212121221221112221221111121212111222221111111111111111111111111111122222222222222222222222222112211111211121111111111111111121"
+ "dataStreamsEnableGated"
- "1211111212221212122122111222122111112121211122222111111111111111111111111111112222222222222222222222222112211111211121111111111111111121"
```

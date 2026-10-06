## com.apple.driver.AppleSMCWirelessCharger

> `com.apple.driver.AppleSMCWirelessCharger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x10fdc` | `0x110e4` | **`+0x108`** |
| `__TEXT.__cstring` | `0x377d` | `0x37ce` | **`+0x51`** |

### Other Changes

```diff

-155.0.0.502.1
-  Functions: 211
+155.0.5.0.0
+  Functions: 212

-  CStrings:  461
+  CStrings:  464
CStrings:
+ "121111121222121212212211122212211111212121112222211111111111111111111111111111222222222222222222222222222112211111211121111111111111111121"
+ "Camera bitmask: 0x%x -> 0x%x\n"
+ "RCAM active: %d -> %d\n"
+ "[b:%s, b-sw:%s, b-tele:%s, b-str:%s, fo-str:%s, fi-str:%s]"
+ "_cameraState:%s\n"
+ "chg-nfc-power-pause-disable"
- "12111112122212121221221112221221111121212111222221111111111111111111111111111122222222222222222222222222112211111211121111111111111111121"
- "RCAM active: %d -> %d; _cameraState:%s\n"
- "[b:%s, sw:%s, tele:%s, streaming:%s]"
```

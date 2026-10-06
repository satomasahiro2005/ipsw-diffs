## com.apple.driver.usb.AppleUSBCommon

> `com.apple.driver.usb.AppleUSBCommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x3a0` | **`+0x3a0`** |
| `__TEXT_EXEC.__text` | `0x592c` | `0x5b40` | **`+0x214`** |
| `__TEXT.__cstring` | `0x309` | `0x365` | **`+0x5c`** |
| `__TEXT.__os_log` | `0xc6` | `0xef` | **`+0x29`** |
| `__DATA_CONST.__got` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-1616.0.0.0.0
-  Functions: 217
+1617.0.1.0.0
+  Functions: 218

-  CStrings:  44
+  CStrings:  47
CStrings:
+ "%s: %s::%s: memory descriptor still set\n"
+ "121121121112"
+ "AppleUSBRequest.cpp"
+ "returnDMACommand_block_invoke"
- "12112112111"
```

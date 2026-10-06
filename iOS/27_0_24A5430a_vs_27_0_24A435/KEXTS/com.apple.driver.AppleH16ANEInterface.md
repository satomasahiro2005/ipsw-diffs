## com.apple.driver.AppleH16ANEInterface

> `com.apple.driver.AppleH16ANEInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x14e9a4` | `0x151df0` | **`+0x344c`** |
| `__DATA.__data` | `0x482c` | `0x54f4` | **`+0xcc8`** |
| `__TEXT.__const` | `0x1000` | `0x12a0` | **`+0x2a0`** |
| `__DATA_CONST.__kalloc_type` | `0x6dc0` | `0x6e40` | **`+0x80`** |
| `__TEXT.__os_log` | `0x3b5dc` | `0x3b649` | **`+0x6d`** |
| `__TEXT.__cstring` | `0x11982` | `0x119ae` | **`+0x2c`** |

### Other Changes

```diff

-  Functions: 4958
+  Functions: 4959

-  CStrings:  5263
+  CStrings:  5270
CStrings:
+ "%s: %s: ANE0 harvested. Enable IPC/Exclave on ANE1\n"
+ "AppleCamera"
+ "[ERROR] %s: %s: Couldn't create MTRCluster instance %d.\n"
+ "ane1-exclave-proxy"
+ "h18g"
+ "h19"
+ "m12"
```

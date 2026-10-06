## com.apple.driver.AppleDisplayCrossbar

> `com.apple.driver.AppleDisplayCrossbar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3d3bc` | `0x3d704` | **`+0x348`** |
| `__TEXT.__cstring` | `0x4cc7` | `0x4de0` | **`+0x119`** |
| `__DATA_CONST.__const` | `0x10bb8` | `0x10bc8` | **`+0x10`** |

### Other Changes

```diff

-417.0.3.0.0
-  Functions: 2159
+417.0.4.0.0
+  Functions: 2160

-  CStrings:  814
+  CStrings:  821
CStrings:
+ "auto connect must be disabled for seamless update\n"
+ "disconnect ufp(%d,%d) from dfp(%d,%d)\n"
+ "disconnect ufp(%d,%d) from ufp(%d,%d) seamlessly\n"
+ "no available peer pipe for rearrangement\n"
+ "no available ufp peer found seamlessly\n"
+ "rearrange only support single pipe\n"
+ "testOnly with success\n"
```

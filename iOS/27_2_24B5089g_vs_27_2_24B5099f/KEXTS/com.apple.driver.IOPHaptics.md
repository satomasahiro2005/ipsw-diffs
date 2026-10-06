## com.apple.driver.IOPHaptics

> `com.apple.driver.IOPHaptics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x26a8` | `0x2820` | **`+0x178`** |
| `__TEXT.__os_log` | `0x1f9` | `0x23f` | **`+0x46`** |
| `__TEXT.__cstring` | `0x4b3` | `0x4d7` | **`+0x24`** |

### Other Changes

```diff

-1000.45.0.0.0
+1010.2.0.0.0

-  CStrings:  38
+  CStrings:  40
Functions:
~ sub_fffffff008bb3018 -> sub_fffffff008b36ba8 : 312 -> 500
~ sub_fffffff008bb3f7c -> sub_fffffff008b37bc8 : 144 -> 332
CStrings:
+ "%s::%s(%d) hall_ctrl failed [0x%x]"
+ "%s::%s(%d) hall_ctrl failed [0x%x]\n"
```

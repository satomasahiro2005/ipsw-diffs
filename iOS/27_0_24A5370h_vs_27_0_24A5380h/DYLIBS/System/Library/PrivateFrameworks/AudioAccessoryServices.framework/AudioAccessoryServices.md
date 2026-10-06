## AudioAccessoryServices

> `/System/Library/PrivateFrameworks/AudioAccessoryServices.framework/AudioAccessoryServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0xf68` | `0xda8` | **`-0x1c0`** |
| `__DATA_DIRTY.__data` | `0x310` | `0x4d0` | **`+0x1c0`** |
| `__TEXT.__text` | `0x506a8` | `0x50704` | **`+0x5c`** |
| `__TEXT.__cstring` | `0xf3c2` | `0xf3d5` | **`+0x13`** |
| `__DATA.__bss` | `0x68` | `0x58` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x30` | `0x40` | **`+0x10`** |

### Other Changes

```diff

-40.31.1.0.0
+40.33.1.0.0

-  CStrings:  2013
+  CStrings:  2015
Functions:
~ -[AudioAccessoryDevice descriptionWithLevel:] : 8688 -> 8780
CStrings:
+ "SR&P: "
+ "routed %u, "
```

## ClockKit

> `/System/Library/Frameworks/ClockKit.framework/ClockKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c17c` | `0x6c1cc` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x730` | `0x738` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x36b0` | `0x36b8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x97ec` | `0x97f4` | **`+0x8`** |

### Other Changes

```diff

-2483.544.0.0.0
+2483.556.1.0.0

-  Functions: 3856
-  Symbols:   6849
+  Functions: 3857
+  Symbols:   6851
Symbols:
+ +[CLKTimeFormatter invalidateCachedTimeFormatters]
+ _dispatch_assert_queue$V2
Functions:
~ -[CLKSensitiveUIMonitor considersUISensitivitySensitive:] : 28 -> 24
+ +[CLKTimeFormatter invalidateCachedTimeFormatters]
```

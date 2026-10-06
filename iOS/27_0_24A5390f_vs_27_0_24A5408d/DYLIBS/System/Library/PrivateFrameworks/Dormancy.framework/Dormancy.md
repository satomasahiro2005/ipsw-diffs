## Dormancy

> `/System/Library/PrivateFrameworks/Dormancy.framework/Dormancy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bc4` | `0x70a8` | **`+0x4e4`** |
| `__TEXT.__oslogstring` | `0x5c` | `0xba` | **`+0x5e`** |
| `__AUTH_CONST.__auth_got` | `0x470` | `0x4a8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x288` | `0x298` | **`+0x10`** |

### Other Changes

```diff

-27.0.57.0.0
+27.0.60.0.0

-  Functions: 226
-  Symbols:   193
-  CStrings:  6
+  Functions: 231
+  Symbols:   196
+  CStrings:  8
Symbols:
+ _objc_release_x20
+ _objc_release_x27
+ _swift_arrayDestroy
CStrings:
+ "Donating event %s for %s from defaultBiomeEventDispatcher"
+ "User engaged with %s for %s"
```

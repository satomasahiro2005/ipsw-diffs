## Ambient

> `/System/Library/PrivateFrameworks/Ambient.framework/Ambient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x230` | `—` | **`-0x230`** |
| `__DATA_DIRTY.__objc_data` | `0x280` | `0x4b0` | **`+0x230`** |
| `__TEXT.__text` | `0x5d2c` | `0x5da4` | **`+0x78`** |
| `__TEXT.__cstring` | `0x72a` | `0x771` | **`+0x47`** |
| `__AUTH_CONST.__objc_const` | `0x1b18` | `0x1b48` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x760` | `0x780` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x9cc` | `0x9e4` | **`+0x18`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x800` | `0x810` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd0` | `0xd4` | **`+0x4`** |

### Other Changes

```diff

-107.0.0.0.0
+108.0.0.0.0

-  Functions: 213
-  Symbols:   525
-  CStrings:  110
+  Functions: 215
+  Symbols:   528
+  CStrings:  112
Symbols:
+ -[AMAmbientDefaults motionDetectionWatchdogTimeoutSeconds]
+ -[AMAmbientDefaults setMotionDetectionWatchdogTimeoutSeconds:]
+ _OBJC_IVAR_$_AMAmbientDefaults._motionDetectionWatchdogTimeoutSeconds
CStrings:
+ "AMMotionDetectionWatchdogSeconds"
+ "motionDetectionWatchdogTimeoutSeconds"
```

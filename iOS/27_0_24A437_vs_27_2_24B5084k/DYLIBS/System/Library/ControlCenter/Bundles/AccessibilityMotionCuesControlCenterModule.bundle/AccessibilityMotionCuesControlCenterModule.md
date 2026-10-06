## AccessibilityMotionCuesControlCenterModule

> `/System/Library/ControlCenter/Bundles/AccessibilityMotionCuesControlCenterModule.bundle/AccessibilityMotionCuesControlCenterModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd4` | `0xf6c` | **`+0x198`** |
| `__TEXT.__gcc_except_tab` | `0x9c` | `0xc8` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x68` | `0x90` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x250` | `0x278` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x418` | `0x438` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xc0` | `0xd8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2d4` | `0x2dc` | **`+0x8`** |
| `__TEXT.__cstring` | `0xb9` | `0xbf` | **`+0x6`** |
| `__DATA.__objc_ivar` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x9b` | `0x98` | **`-0x3`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 26
-  Symbols:   60
-  CStrings:  15
+  Functions: 28
+  Symbols:   63
+  CStrings:  16
Symbols:
+ _OBJC_CLASS_$_AXDispatchTimer
+ __dispatch_main_q
+ _objc_retain_x22
CStrings:
+ "CC update selected: active=%{bool}d, enabled=%{bool}d, mode=%d"
+ "v8@?0"
- "CC setting did change: active=%{bool}d, enabled=%{bool}d, mode=%d"
```

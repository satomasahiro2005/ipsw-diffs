## ReplayKit

> `/System/Library/Frameworks/ReplayKit.framework/ReplayKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36c8c` | `0x36cdc` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x3680` | `0x3670` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x66f0` | `0x66e8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x4e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x21a0` | `0x2198` | **`-0x8`** |
| `__TEXT.__cstring` | `0x81db` | `0x81d5` | **`-0x6`** |

### Other Changes

```diff

-740.63.1.2.0
+765.9.1.0.0

-  Functions: 1418
-  Symbols:   2239
+  Functions: 1419
+  Symbols:   2241
Symbols:
+ -[RPControlCenterAngelProxy showRemoteAlertOfType:application:bundleID:]
+ _AVControlCenterVideoEffectReactions
+ _showTip
- -[RPControlCenterAngelProxy showReactionsTipForApplication:bundleID:]
CStrings:
+ "-[RPControlCenterAngelProxy showRemoteAlertOfType:application:bundleID:]"
+ "showTip"
- "-[RPControlCenterAngelProxy showReactionsTipForApplication:bundleID:]"
- "showReactionsTip"
```

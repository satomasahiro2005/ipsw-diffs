## BaseBoard

> `/System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1860` | `0xa17a0` | **`-0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xd4c0` | `0xd530` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x7074` | `0x70b4` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x10f64` | `0x10f88` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x8ca0` | `0x8cc0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5260` | `0x5280` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x31f0` | `0x3200` | **`+0x10`** |
| `__TEXT.__cstring` | `0x8f4d` | `0x8f53` | **`+0x6`** |
| `__DATA.__objc_ivar` | `0x860` | `0x864` | **`+0x4`** |

### Other Changes

```diff

-821.0.0.0.0
+825.0.0.0.0

-  Functions: 3025
-  Symbols:   5932
-  CStrings:  1590
+  Functions: 3030
+  Symbols:   5938
+  CStrings:  1591
Symbols:
+ -[BSAnimationSettings _initWithStoredDuration:storedDurationIsDirty:delay:frameInterval:frameRange:highFrameRateReason:timingFunction:speed:beginTime:interactionTrackingReason:mass:stiffness:damping:epsilon:initialVelocity:isSpring:]
+ -[BSAnimationSettings _setInteractionTrackingReason:]
+ -[BSAnimationSettings interactionTrackingReason]
+ -[BSMutableAnimationSettings setInteractionTrackingReason:]
+ -[BSMutableSpringAnimationSettings setInteractionTrackingReason:]
+ _OBJC_IVAR_$_BSAnimationSettings._lock_interactionTrackingReason
+ __bs_set_crash_log_backtrace
- -[BSAnimationSettings _initWithStoredDuration:storedDurationIsDirty:delay:frameInterval:frameRange:highFrameRateReason:timingFunction:speed:beginTime:mass:stiffness:damping:epsilon:initialVelocity:isSpring:]
CStrings:
+ "tr"
```

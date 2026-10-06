## NearbyInteraction

> `/System/Library/Frameworks/NearbyInteraction.framework/NearbyInteraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37068` | `0x371f0` | **`+0x188`** |
| `__AUTH_CONST.__cfstring` | `0x5ae0` | `0x5b20` | **`+0x40`** |
| `__TEXT.__cstring` | `0x51c0` | `0x51fa` | **`+0x3a`** |
| `__AUTH_CONST.__objc_const` | `0x7fc8` | `0x7ff8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x5a28` | `0x5a54` | **`+0x2c`** |
| `__TEXT.__objc_methlist` | `0x44a8` | `0x44c0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2040` | `0x2050` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x518` | `0x51c` | **`+0x4`** |

### Other Changes

```diff

-569.0.0.0.0
+575.0.5.0.0

-  Functions: 1585
-  Symbols:   3000
-  CStrings:  946
+  Functions: 1588
+  Symbols:   3003
+  CStrings:  948
Symbols:
+ -[NINearbyObject setSuggestedNearbyThreshold:]
+ -[NINearbyObject suggestedNearbyThreshold]
+ _OBJC_IVAR_$_NINearbyObject._suggestedNearbyThreshold
CStrings:
+ ", Suggested Nearby Threshold: %@"
+ "suggestedNearbyThreshold"
```

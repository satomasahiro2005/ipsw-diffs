## ARKitUI

> `/System/Library/SubFrameworks/ARKitUI.framework/ARKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b478` | `0x2b9b4` | **`+0x53c`** |
| `__TEXT.__oslogstring` | `0x1830` | `0x192e` | **`+0xfe`** |
| `__AUTH_CONST.__objc_const` | `0x75c8` | `0x7648` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0xc20` | `0xc60` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2288` | `0x22c0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x2950` | `0x2988` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x3a0` | `0x3c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xdb4` | `0xdcf` | **`+0x1b`** |
| `__DATA.__bss` | `0x240` | `0x250` | **`+0x10`** |
| `__TEXT.__const` | `0x938` | `0x948` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x588` | `0x594` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0xc18` | `0xc20` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 979
-  Symbols:   2143
-  CStrings:  230
+  Functions: 987
+  Symbols:   2153
+  CStrings:  235
Symbols:
+ -[ARCoachingAnimationView updateGlyphForDisplayRegionIfNeeded:]
+ -[ARCoachingOverlayView displayRegionOverrideEnabled]
+ -[ARCoachingOverlayView displayRegionOverride]
+ -[ARCoachingOverlayView setDisplayRegionOverride:]
+ -[ARCoachingOverlayView setDisplayRegionOverrideEnabled:]
+ _ARCoachingDeviceGlyphNameForDisplayRegion
+ _ARDeviceIsV68
+ _OBJC_IVAR_$_ARCoachingAnimationView._currentGlyphName
+ _OBJC_IVAR_$_ARCoachingOverlayView._displayRegionOverride
+ _OBJC_IVAR_$_ARCoachingOverlayView._displayRegionOverrideEnabled
CStrings:
+ "%{public}@ <%p>: Coaching display region glyph changed (%@ -> %@), rebuilding renderer"
+ "%{public}@ <%p>: Overriding ARFrame display region to be %ld"
+ "Call ARCoachingDeviceGlyphNameForDisplayRegion on %@ instead. Falling back to unspecified display region."
+ "DeviceF-V68"
+ "DeviceG-V68"
+ "\xf0r"
- "\xf0b"
```

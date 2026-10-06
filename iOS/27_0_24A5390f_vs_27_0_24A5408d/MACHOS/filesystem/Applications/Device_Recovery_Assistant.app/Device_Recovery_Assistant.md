## Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e4c0` | `0x1e77c` | **`+0x2bc`** |
| `__TEXT.__objc_methname` | `0x8928` | `0x8b1c` | **`+0x1f4`** |
| `__TEXT.__objc_stubs` | `0x6180` | `0x6220` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x64f8` | `0x6558` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x2d38` | `0x2d90` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x35a0` | `0x35e9` | **`+0x49`** |
| `__DATA.__objc_selrefs` | `0x2280` | `0x22c0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x2551` | `0x257a` | **`+0x29`** |
| `__TEXT.__unwind_info` | `0x6e0` | `0x6f8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xa18` | `0xa08` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x830` | `0x840` | **`+0x10`** |
| `__TEXT.__cstring` | `0x35aa` | `0x35b5` | **`+0xb`** |
| `__DATA.__objc_ivar` | `0x204` | `0x20c` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x428` | `0x430` | **`+0x8`** |
| `__DATA.__data` | `0xcdc` | `0xce0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-149.0.0.0.0
+150.0.2.0.0

-  Functions: 785
-  Symbols:   306
-  CStrings:  2339
+  Functions: 793
+  Symbols:   307
+  CStrings:  2355
Symbols:
+ _BKHIDServicesGetNonFlatDeviceOrientation
CStrings:
+ "$"
+ "%{public}s: DREOrientationManager: Boot orientation from BKS = %ld"
+ "%{public}s: DREOrientationManager: Orientation %ld -> %ld (animated=%d)"
+ "-[DREOrientationManager _applyDeviceOrientation:animated:]"
+ "@\"FBSDisplayConfiguration\""
+ "T@\"FBSDisplayConfiguration\",&,N,V_activeDisplayConfiguration"
+ "Tq,N,V_dr_activeInterfaceOrientation"
+ "_activeDisplayConfiguration"
+ "_applyDeviceOrientation:animated:"
+ "_bindScene:"
+ "_dr_activeInterfaceOrientation"
+ "_unbindScene:"
+ "activeDisplayConfiguration"
+ "activeInterfaceOrientation"
+ "dr_activeInterfaceOrientation"
+ "noteActiveInterfaceOrientationDidChangeToOrientation:willAnimateWithSettings:fromOrientation:screen:"
+ "noteActiveInterfaceOrientationWillChangeToOrientation:screen:"
+ "setActiveDisplayConfiguration:"
+ "setDr_activeInterfaceOrientation:"
+ "v28@0:8q16B24"
+ "windowRotationDuration"
- "%{public}s: DREOrientationManager: Orientation changed %ld -> %ld"
- "-[DREOrientationManager _applyDeviceOrientation:]"
- "_referenceBounds"
- "traitCollection"
- "userInterfaceStyle"
```

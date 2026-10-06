## backboardd

> `/usr/libexec/backboardd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58a64` | `0x5a140` | **`+0x16dc`** |
| `__DATA.__objc_const` | `0xaf20` | `0xb0f8` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0x7144` | `0x72cb` | **`+0x187`** |
| `__TEXT.__objc_stubs` | `0x9e80` | `0x9fc0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x4a0c` | `0x4b24` | **`+0x118`** |
| `__DATA_CONST.__cfstring` | `0x5000` | `0x5080` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0xdbe8` | `0xdc67` | **`+0x7f`** |
| `__DATA.__data` | `0x1b88` | `0x1be8` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2030` | `0x2080` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x15e0` | `0x1628` | **`+0x48`** |
| `__TEXT.__cstring` | `0x4cd3` | `0x4d19` | **`+0x46`** |
| `__TEXT.__objc_classname` | `0x13c1` | `0x13fd` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x30e8` | `0x3118` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3318` | `0x3348` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x1550` | `0x1570` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xab8` | `0xac8` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x2ed7` | `0x2ee4` | **`+0xd`** |
| `__DATA_CONST.__objc_classlist` | `0x338` | `0x340` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x240` | `0x248` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x7fc` | `0x800` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-877.0.0.0.0
+877.2.1.0.0

-  Functions: 1904
-  Symbols:   618
-  CStrings:  4091
+  Functions: 1929
+  Symbols:   620
+  CStrings:  4111
Symbols:
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
CStrings:
+ "@\"<BKDisplayRenderOverlayPresentable>\""
+ "BKDisplayRenderOverlayPresentable"
+ "BKDisplayRenderOverlaySet"
+ "Current bootUI for display %{public}@ is an Apple Logo, level %g"
+ "Current bootUI for display %{public}@ is the spinny because the Apple Logo can only be laid out for the legacy main display, level %g"
+ "Current bootUI for display %{public}@ is the spinny, level %g"
+ "T@\"NSArray\",R,N"
+ "TB,R,N,GisEmpty"
+ "Using %{public}@ for %{public}@"
+ "Using default display for %{public}@"
+ "_displaysForBootUI"
+ "_members"
+ "_overlayForDisplays:level:"
+ "_queue_appendDescriptionToStream:"
+ "addOverlay(%d-%{public}@): Adding the overlay: %{public}@"
+ "addOverlay(%d-%{public}@): no displays to add the overlay to"
+ "addUnderlay: Adding the underlay: %{public}@"
+ "addUnderlay: no displays to add the underlay to"
+ "appendCollection:withName:itemBlock:"
+ "arrayWithCapacity:"
+ "dismissWhenUnsustained"
+ "initWithOverlays:"
+ "isEmpty"
+ "overlaySustained"
+ "overlays"
+ "screenOwner"
+ "screenOwnerPID"
+ "setInterstitial:"
+ "setWithOverlays:"
- "@\"BKDisplayRenderOverlay\""
- "Current bootUI is an Apple Logo"
- "Current bootUI is the spinny, level %@"
- "T@\"BKDisplayRenderOverlay\",&,N,V_overlay"
- "T@\"BKDisplayRenderOverlay\",&,N,V_underlay"
- "addOverlay(%d-%{public}@): Adding the overlay"
- "addUnderlay:  Adding the underlay"
- "setOverlay:"
- "setUnderlay:"
```

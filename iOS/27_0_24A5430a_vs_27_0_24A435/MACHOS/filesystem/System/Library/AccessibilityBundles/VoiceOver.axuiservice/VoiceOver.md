## VoiceOver

> `/System/Library/AccessibilityBundles/VoiceOver.axuiservice/VoiceOver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25048` | `0x255d8` | **`+0x590`** |
| `__TEXT.__objc_methname` | `0x6e76` | `0x6f76` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x4b40` | `0x4c40` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x251` | `0x2e7` | **`+0x96`** |
| `__DATA.__data` | `0x1648` | `0x16a8` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x1a20` | `0x1a68` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x1dfc` | `0x1e44` | **`+0x48`** |
| `__DATA.__objc_const` | `0x3898` | `0x38c0` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x626` | `0x640` | **`+0x1a`** |
| `__TEXT.__auth_stubs` | `0x13d0` | `0x13e0` | **`+0x10`** |
| `__TEXT.__const` | `0xc90` | `0xca0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x9d8` | `0x9e8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x137a` | `0x1389` | **`+0xf`** |
| `__TEXT.__gcc_except_tab` | `0x250` | `0x25c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x9f8` | `0xa00` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xa0` | `0xa8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 833
-  Symbols:   414
-  CStrings:  1496
+  Functions: 837
+  Symbols:   415
+  CStrings:  1510
Symbols:
+ _AXDeviceIsViridian
CStrings:
+ "AXUIActiveDisplayObserver"
+ "Hiding"
+ "Showing"
+ "[ActiveDisplay] %{public}s VoiceOver UI on displayID=%@."
+ "[ActiveDisplay] Active display changed to displayID=%u; reconciling VoiceOver UI visibility."
+ "_activeDisplaySceneIsForegroundActive"
+ "_reconcileDisplayVisibility"
+ "_setVoiceOverUIHidden:forScene:"
+ "activationState"
+ "activeDisplayDidChangeToDisplayID:"
+ "activeDisplayID"
+ "addActiveDisplayObserver:"
+ "removeActiveDisplayObserver:"
+ "shouldPresentUIForWindowScene:"
```

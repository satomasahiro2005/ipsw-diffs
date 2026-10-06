## assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x163ba4` | `0x1642b8` | **`+0x714`** |
| `__TEXT.__oslogstring` | `0x6c21` | `0x6d83` | **`+0x162`** |
| `__TEXT.__objc_stubs` | `0x2bd60` | `0x2be20` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x380f0` | `0x38180` | **`+0x90`** |
| `__DATA.__data` | `0x4290` | `0x42f0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1571c` | `0x1575c` | **`+0x40`** |
| `__DATA.__objc_const` | `0x1c6b0` | `0x1c6d8` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0xc498` | `0xc4c0` | **`+0x28`** |
| `__TEXT.__cstring` | `0xded7` | `0xdefd` | **`+0x26`** |
| `__DATA_CONST.__cfstring` | `0x9e20` | `0x9e40` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x2ab4` | `0x2ace` | **`+0x1a`** |
| `__TEXT.__gcc_except_tab` | `0x2a10` | `0x2a28` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x4160` | `0x4170` | **`+0x10`** |
| `__TEXT.__const` | `0x4af0` | `0x4b00` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x20c0` | `0x20c8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1bf8` | `0x1c00` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x428` | `0x430` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x65b8` | `0x65c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 9325
-  Symbols:   2326
-  CStrings:  11965
+  Functions: 9329
+  Symbols:   2328
+  CStrings:  11978
Symbols:
+ _AXAssistiveTouchIconTypeMultitasking
+ _AXDeviceIsViridian
CStrings:
+ "AXUIActiveDisplayObserver"
+ "Hiding"
+ "Showing"
+ "[ActiveDisplay] %{public}s AssistiveTouch UI on displayID=%u."
+ "[ActiveDisplay] Active display changed to displayID=%u (displayManager=%p)."
+ "[ActiveDisplay] Applying active displayID=%u on scene connect (observer callback found no manager)."
+ "_activateActiveDisplayIfNotYetApplied"
+ "_reconcileDisplayVisuals"
+ "activeDisplayDidChange"
+ "activeDisplayDidChangeToDisplayID:"
+ "addActiveDisplayObserver:"
+ "sceneDidBecomeActive: scene active (hardwareIdentifier=%{public}@); active-display handling runs from the observer."
+ "shouldPresentUIForWindowScene:"
```

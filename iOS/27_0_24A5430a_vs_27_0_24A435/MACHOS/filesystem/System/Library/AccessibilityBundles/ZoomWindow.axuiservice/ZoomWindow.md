## ZoomWindow

> `/System/Library/AccessibilityBundles/ZoomWindow.axuiservice/ZoomWindow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ba38` | `0x6bcdc` | **`+0x2a4`** |
| `__TEXT.__objc_methname` | `0x113eb` | `0x1149b` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0xbc80` | `0xbd20` | **`+0xa0`** |
| `__DATA.__data` | `0x1ab0` | `0x1b10` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x920` | `0x975` | **`+0x55`** |
| `__DATA.__objc_selrefs` | `0x3860` | `0x3890` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4d60` | `0x4d90` | **`+0x30`** |
| `__DATA.__objc_const` | `0x79b8` | `0x79e0` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x920` | `0x93a` | **`+0x1a`** |
| `__DATA_CONST.__objc_protolist` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a78` | `0x1a80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 2546
-  Symbols:   4995
-  CStrings:  3282
+  Functions: 2548
+  Symbols:   5007
+  CStrings:  3290
Symbols:
+ -[ZWUIServer _activeDisplaySceneIsForegroundActive]
+ -[ZWUIServer activeDisplayDidChangeToDisplayID:]
+ GCC_except_table1127
+ GCC_except_table1145
+ GCC_except_table1192
+ GCC_except_table1236
+ GCC_except_table1265
+ GCC_except_table1361
+ GCC_except_table1531
+ GCC_except_table1542
+ GCC_except_table772
+ GCC_except_table808
+ _AXDeviceIsViridian
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AXUIActiveDisplayObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AXUIActiveDisplayObserver
+ __OBJC_$_PROTOCOL_REFS_AXUIActiveDisplayObserver
+ __OBJC_LABEL_PROTOCOL_$_AXUIActiveDisplayObserver
+ __OBJC_PROTOCOL_$_AXUIActiveDisplayObserver
+ _objc_msgSend$_activeDisplaySceneIsForegroundActive
+ _objc_msgSend$activeDisplayID
+ _objc_msgSend$addActiveDisplayObserver:
+ _objc_msgSend$removeActiveDisplayObserver:
+ _objc_msgSend$shouldPresentUIForWindowScene:
- GCC_except_table1125
- GCC_except_table1143
- GCC_except_table1190
- GCC_except_table1234
- GCC_except_table1255
- GCC_except_table1359
- GCC_except_table1529
- GCC_except_table1540
- GCC_except_table770
- GCC_except_table806
- _objc_retain_x28
CStrings:
+ "AXUIActiveDisplayObserver"
+ "[ActiveDisplay] Active display changed to displayID=%u; reconciling zoom visibility."
+ "_activeDisplaySceneIsForegroundActive"
+ "activeDisplayDidChangeToDisplayID:"
+ "activeDisplayID"
+ "addActiveDisplayObserver:"
+ "removeActiveDisplayObserver:"
+ "shouldPresentUIForWindowScene:"
```

## MessagesDrawingBoard

> `/System/Library/ExtensionKit/Extensions/MessagesDrawingBoard.appex/MessagesDrawingBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa7f4` | `0xafc0` | **`+0x7cc`** |
| `__TEXT.__objc_methtype` | `0x153` | `0x1db` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0xabe` | `0xb42` | **`+0x84`** |
| `__TEXT.__objc_stubs` | `0x920` | `0x9a0` | **`+0x80`** |
| `__DATA.__objc_data` | `0x310` | `0x340` | **`+0x30`** |
| `__TEXT.__const` | `0x6b4` | `0x684` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x3a0` | `0x3c8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x530` | `0x558` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x310` | `0x338` | **`+0x28`** |
| `__DATA.__objc_const` | `0x390` | `0x3b0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x17a` | `0x19a` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x360` | `0x378` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xd10` | `0xd20` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x22c` | `0x23c` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x108` | `0x118` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x174` | `0x180` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x690` | `0x698` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-376.0.0.0.0
+379.0.0.0.0

-  Functions: 212
-  Symbols:   166
-  CStrings:  179
+  Functions: 222
+  Symbols:   167
+  CStrings:  187
Symbols:
+ _OBJC_CLASS_$_UINavigationController
+ _OBJC_CLASS_$_UIViewController
+ __UIEnhancedLandscapeEnabled
+ _objc_release_x9
+ _objc_retain_x24
+ _objc_retain_x25
- _OBJC_CLASS_$_UINavigationBar
- _OBJC_CLASS_$_UINavigationItem
- _objc_retain_x26
- _objc_retain_x28
- _swift_release_x24
CStrings:
+ "animateAlongsideTransition:completion:"
+ "cancelButton"
+ "canvasHostViewController"
+ "effectiveGeometry"
+ "initWithRootViewController:"
+ "interfaceOrientation"
+ "navigationItem"
+ "setWidth:"
+ "userInterfaceIdiom"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
+ "v40@0:8{CGSize=dd}16@32"
+ "viewWillTransitionToSize:withTransitionCoordinator:"
- "bringSubviewToFront:"
- "constraintEqualToAnchor:constant:"
- "safeAreaLayoutGuide"
- "setItems:animated:"
```

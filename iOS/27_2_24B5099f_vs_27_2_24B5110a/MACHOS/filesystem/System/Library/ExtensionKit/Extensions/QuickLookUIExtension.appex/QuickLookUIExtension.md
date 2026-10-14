## QuickLookUIExtension

> `/System/Library/ExtensionKit/Extensions/QuickLookUIExtension.appex/QuickLookUIExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11c68` | `0x11fc4` | **`+0x35c`** |
| `__TEXT.__objc_methname` | `0x5112` | `0x51da` | **`+0xc8`** |
| `__TEXT.__objc_stubs` | `0x3fc0` | `0x4080` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0xdc0` | `0xd60` | **`-0x60`** |
| `__DATA.__objc_selrefs` | `0x1560` | `0x1598` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x13fc` | `0x1434` | **`+0x38`** |
| `__TEXT.__cstring` | `0x126f` | `0x124d` | **`-0x22`** |
| `__DATA.__objc_const` | `0x1ac0` | `0x1ae0` | **`+0x20`** |
| `__DATA.__data` | `0x4e8` | `0x4f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3a8` | `0x3b8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x124` | `0x128` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1034.1.4.0.0
+1034.1.5.100.0

-  Functions: 470
+  Functions: 477

-  CStrings:  1165
+  CStrings:  1170
CStrings:
+ "_dismissCalendarChooserIfNeededAnimated:"
+ "_icsViewBottomConstraint"
+ "_updateICSViewBottomInset"
+ "opaqueBottomBarHeight"
+ "parentViewController"
+ "presentedViewController"
+ "setConstant:"
+ "viewSafeAreaInsetsDidChange"
- "H:|[icsView]|"
- "V:|[icsView]|"
- "icsView"
```

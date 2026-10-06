## VoiceOver

> `/System/Library/AccessibilityBundles/VoiceOver.axuiservice/VoiceOver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25958` | `0x25c58` | **`+0x300`** |
| `__DATA_CONST.__cfstring` | `0xcc0` | `0xde0` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x4d20` | `0x4dc0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x138a` | `0x1428` | **`+0x9e`** |
| `__TEXT.__objc_methname` | `0x70c0` | `0x7140` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x2040` | `0x2068` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1aa0` | `0x1ac0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x13e0` | `0x1400` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xa00` | `0xa10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x9f0` | `0x9f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
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

-2482.13.1.0.0
+2482.13.3.0.0

-  Functions: 842
-  Symbols:   416
-  CStrings:  1520
+  Functions: 844
+  Symbols:   420
+  CStrings:  1534
Symbols:
+ _AXUILocalizedStringForKey
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ __AXUISettingsAccessibilityBundle
CStrings:
+ "CANCEL"
+ "CONFIRM_SOUND_CURTAIN_MESSAGE"
+ "CONFIRM_TOUCH_CURTAIN_MESSAGE"
+ "OK"
+ "SOUND_CURTAIN"
+ "TOUCH_CURTAIN"
+ "VoiceOverSettings"
+ "actionWithTitle:style:handler:"
+ "addAction:"
+ "alertControllerWithTitle:message:preferredStyle:"
+ "curtainType"
+ "rootViewController"
+ "sound"
+ "v16@?0@\"UIAlertAction\"8"
```

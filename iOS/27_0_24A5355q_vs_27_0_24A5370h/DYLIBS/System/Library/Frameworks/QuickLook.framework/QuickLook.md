## QuickLook

> `/System/Library/Frameworks/QuickLook.framework/QuickLook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdcb4c` | `0xdd16c` | **`+0x620`** |
| `__TEXT.__cstring` | `0x5324` | `0x54a4` | **`+0x180`** |
| `__DATA.__bss` | `0x3428` | `0x3528` | **`+0x100`** |
| `__TEXT.__const` | `0x3a64` | `0x3ad4` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x11950` | `0x11988` | **`+0x38`** |
| `__DATA.__data` | `0x33f0` | `0x3420` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xb71c` | `0xb744` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1cce` | `0x1cf4` | **`+0x26`** |
| `__AUTH_CONST.__auth_got` | `0x14c8` | `0x14e0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x7418` | `0x7430` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x46d8` | `0x46f0` | **`+0x18`** |
| `__AUTH.__data` | `0x1638` | `0x1648` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x49fc` | `0x4a0c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1748` | `0x1758` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x907` | `0x917` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb00` | `0xb0c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xfa0` | `0xfa8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x194` | `0x19c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc08` | `0xc0c` | **`+0x4`** |

### Other Changes

```diff

-1027.1.0.0.0
+1029.0.0.0.0

-  Functions: 5695
-  Symbols:   7505
-  CStrings:  901
+  Functions: 5702
+  Symbols:   7513
+  CStrings:  913
Symbols:
+ -[QLPreviewCollection isFormFilling]
+ -[QLPreviewCollection previewItemViewController:didEnableFormFillingMode:]
+ -[QLPreviewCollection setIsFormFilling:]
+ GCC_except_table178
+ GCC_except_table179
+ _OBJC_IVAR_$_QLPreviewCollection._isFormFilling
+ _associated conformance 9QuickLook16QLDocumentEntityV10AppIntents015SystemFrameworkD0AaD0eD0
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents13_IntentTargetV
+ _symbolic _____y_____SgG 10AppIntents14EntityPropertyC 10Foundation3URLV
- GCC_except_table176
CStrings:
+ "com.apple.MobileCBP"
+ "com.apple.MobileSMS"
+ "com.apple.Passbook"
+ "com.apple.TapToRadar"
+ "com.apple.freeform"
+ "com.apple.mobilemail"
+ "com.apple.mobilenotes"
+ "com.apple.mobilesafari"
+ "com.apple.mobileslideshow"
+ "com.apple.preview"
+ "com.apple.reminders"
+ "com.apple.shortcuts"
```

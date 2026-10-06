## HomeSettings

> `/System/Library/PreferenceBundles/HomeSettings.bundle/HomeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b94` | `0x5a00` | **`-0x194`** |
| `__TEXT.__cstring` | `0x1225` | `0x128c` | **`+0x67`** |
| `__TEXT.__objc_methname` | `0x2bc0` | `0x2c25` | **`+0x65`** |
| `__TEXT.__objc_stubs` | `0x18c0` | `0x1920` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x298` | `0x2d8` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x370` | `0x3b0` | **`+0x40`** |
| `__DATA.__bss` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1c8` | `0x1e8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x1480` | `0x14a0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xc40` | `0xc58` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x460` | `0x470` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1b0` | `0x1c0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-1265.0.0.1.1
+1269.2.3.0.1

-  Functions: 102
-  Symbols:   219
-  CStrings:  684
+  Functions: 109
+  Symbols:   228
+  CStrings:  688
Symbols:
+ _HFPreferencesCameraClipsDebugMenuKey
+ _HOSLocalizedStringForKey
+ _HOSLocalizedStringWithFormat
+ _NSLog
+ _OBJC_CLASS_$_NSLocale
+ ___NSArray0__struct
+ _dispatch_once
+ _objc_release_x1
+ _objc_retain
CStrings:
+ "Enable Camera Viewer Debug Menu"
+ "HOSLocalizedStringWithFormat: couldn't format localized string \"%@\": %@"
+ "currentLocale"
+ "initWithValidatedFormat:validFormatSpecifiers:locale:arguments:error:"
+ "isEqualToString:"
- ""
```

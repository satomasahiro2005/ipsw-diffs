## MercuryPosterExtension

> `/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/MercuryPosterExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfcde8` | `0xfd1e4` | **`+0x3fc`** |
| `__TEXT.__objc_methtype` | `0x32fe` | `0x3478` | **`+0x17a`** |
| `__TEXT.__objc_stubs` | `0x2d20` | `0x2de0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0xf030` | `0xf0e8` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x8188` | `0x81e8` | **`+0x60`** |
| `__DATA.__data` | `0x55f8` | `0x5638` | **`+0x40`** |
| `__DATA.__objc_const` | `0x6718` | `0x6758` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x427e` | `0x42be` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x18e0` | `0x1910` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x3668` | `0x3690` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x6d8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1e20` | `0x1e40` | **`+0x20`** |
| `__TEXT.__cstring` | `0x30f1` | `0x30d1` | **`-0x20`** |
| `__TEXT.__objc_classname` | `0xa84` | `0xa64` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x4350` | `0x4368` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x22a7` | `0x22bf` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xf18` | `0xf28` | **`+0x10`** |
| `__TEXT.__const` | `0xb2c8` | `0xb2d8` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x57c` | `0x58c` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-82.0.0.0.0
+84.0.0.0.0

-  Functions: 2734
-  Symbols:   390
-  CStrings:  2130
+  Functions: 2740
+  Symbols:   394
+  CStrings:  2137
Symbols:
+ _NSProcessInfoPowerStateDidChangeNotification
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_CLASS_$_NSProcessInfo
CStrings:
+ "addObserverForName:object:queue:usingBlock:"
+ "defaultCenter"
+ "isLowPowerModeEnabled"
+ "lowPowerModeObserver"
+ "mainQueue"
+ "processInfo"
+ "removeObserver:"
+ "v16@?0@\"NSNotification\"8"
- "Color picker action label"
```

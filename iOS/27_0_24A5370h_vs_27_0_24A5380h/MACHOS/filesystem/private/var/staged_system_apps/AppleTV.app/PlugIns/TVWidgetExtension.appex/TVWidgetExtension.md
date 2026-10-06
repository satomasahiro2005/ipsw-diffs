## TVWidgetExtension

> `/private/var/staged_system_apps/AppleTV.app/PlugIns/TVWidgetExtension.appex/TVWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbd508` | `0xbcc38` | **`-0x8d0`** |
| `__TEXT.__swift5_typeref` | `0x120b0` | `0x11a5c` | **`-0x654`** |
| `__DATA.__bss` | `0x12f48` | `0x13128` | **`+0x1e0`** |
| `__TEXT.__objc_stubs` | `0x1ac0` | `0x1be0` | **`+0x120`** |
| `__DATA.__data` | `0x6298` | `0x6188` | **`-0x110`** |
| `__TEXT.__objc_methname` | `0x161a` | `0x16e5` | **`+0xcb`** |
| `__TEXT.__const` | `0xee94` | `0xedf4` | **`-0xa0`** |
| `__TEXT.__constg_swiftt` | `0x2978` | `0x28e4` | **`-0x94`** |
| `__TEXT.__auth_stubs` | `0x33f0` | `0x3370` | **`-0x80`** |
| `__DATA.__objc_selrefs` | `0x710` | `0x758` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x1a08` | `0x19c8` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x2ad` | `0x2dd` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x1488` | `0x14b0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x5ec0` | `0x5e98` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x2f9c` | `0x2f74` | **`-0x28`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x4a8` | `0x4bc` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xa78` | `0xa88` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x95c` | `0x96c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x390d` | `0x38fd` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2d20` | `0x2d18` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2d0` | `0x2cc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1143.0.0.0.2
+1145.0.2.0.1

-  Functions: 3847
-  Symbols:   346
-  CStrings:  1073
+  Functions: 3839
+  Symbols:   347
+  CStrings:  1084
Symbols:
+ _NSFontAttributeName
+ _NSForegroundColorAttributeName
+ _OBJC_CLASS_$_UIBezierPath
+ _OBJC_CLASS_$_UIGraphicsImageRenderer
+ _UIFontDescriptorSystemDesignRounded
+ _UIFontWeightSemibold
+ _swift_isEscapingClosureAtFileLocation
- _UIGraphicsBeginImageContextWithOptions
- _UIGraphicsEndImageContext
- _UIGraphicsGetImageFromCurrentImageContext
- _UIRectFill
- _swift_cvw_instantiateLayoutString
- _swift_getObjCClassFromMetadata
CStrings:
+ "LIVE"
+ "bezierPathWithRoundedRect:cornerRadius:"
+ "drawAtPoint:withAttributes:"
+ "fill"
+ "fontDescriptor"
+ "fontDescriptorWithDesign:"
+ "fontWithDescriptor:size:"
+ "imageWithActions:"
+ "initWithSize:"
+ "sizeWithAttributes:"
+ "systemFontOfSize:weight:"
+ "v16@?0@\"UIGraphicsImageRendererContext\"8"
+ "whiteColor"
- "CGImage"
- "initWithCGImage:"
```

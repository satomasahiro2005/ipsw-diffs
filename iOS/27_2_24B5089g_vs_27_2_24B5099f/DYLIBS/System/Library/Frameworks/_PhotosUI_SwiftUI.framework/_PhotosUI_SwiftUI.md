## _PhotosUI_SwiftUI

> `/System/Library/Frameworks/_PhotosUI_SwiftUI.framework/_PhotosUI_SwiftUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2af94` | `0x2db60` | **`+0x2bcc`** |
| `__AUTH_CONST.__const` | `0x1a08` | `0x1c48` | **`+0x240`** |
| `__TEXT.__constg_swiftt` | `0x1cb8` | `0x1ebc` | **`+0x204`** |
| `__TEXT.__const` | `0x2fb8` | `0x3158` | **`+0x1a0`** |
| `__DATA.__bss` | `0x2840` | `0x29c0` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x2b5` | `0x405` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0x528` | `0x668` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x1570` | `0x1688` | **`+0x118`** |
| `__TEXT.__swift5_capture` | `0x6e0` | `0x7b0` | **`+0xd0`** |
| `__AUTH.__data` | `0x678` | `0x738` | **`+0xc0`** |
| `__DATA.__data` | `0xde0` | `0xea0` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0xa08` | `0xab8` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0xb70` | `0xc08` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0xc60` | `0xcf8` | **`+0x98`** |
| `__TEXT.__eh_frame` | `0x6e8` | `0x778` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0xa00` | `0xa7c` | **`+0x7c`** |
| `__AUTH.__objc_data` | `0x160` | `0x1b0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x278` | `0x2c8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x45c` | `0x47c` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1e8` | `0x200` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x170` | `0x17c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x104` | `0x110` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x30` | `0x34` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x30` | `0x34` | **`+0x4`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0
+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

-  Functions: 1459
-  Symbols:   844
-  CStrings:  40
+  Functions: 1517
+  Symbols:   875
+  CStrings:  46
Symbols:
+ _CGImageDestinationAddImage
+ _CGImageDestinationCreateWithURL
+ _CGImageDestinationFinalize
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _OBJC_CLASS_$_NSFileManager
+ _OBJC_CLASS_$_PVSAdjustedImageSurface
+ __DATA__TtC17_PhotosUI_SwiftUI20PVSAdjustedImageFile
+ __IVARS__TtC17_PhotosUI_SwiftUI20PVSAdjustedImageFile
+ __METACLASS_DATA__TtC17_PhotosUI_SwiftUI20PVSAdjustedImageFile
+ ___swift_closure_destructor.81Tm
+ ___unnamed_46
+ ___unnamed_49
+ __swift_stdlib_bridgeErrorToNSError
+ _associated conformance So11CFStringRefa14CoreFoundation9_CFObjectSCSH
+ _associated conformance So11CFStringRefaSHSCSQ
+ _kCGImagePropertyTIFFCompression
+ _kCGImagePropertyTIFFDictionary
+ _objc_retain_x9
+ _symbolic SDy_____SiG So11CFStringRefa
+ _symbolic So23PVSAdjustedImageSurfaceCSgSg
+ _symbolic So8NSObjectCIego_
+ _symbolic So8NSObjectCSg
+ _symbolic So8NSObjectCSgIego_
+ _symbolic _____ 015_PhotosUI_SwiftB020PVSAdjustedImageFileC
+ _symbolic _____ So10CGImageRefa
+ _symbolic _____3url_SS21sandboxExtensionTokent 10Foundation3URLV
+ _symbolic _____3url_SS21sandboxExtensionTokentSg 10Foundation3URLV
+ _symbolic _____Sg So10CGImageRefa
+ _symbolic _____SgSg 015_PhotosUI_SwiftB020PVSAdjustedImageFileC
+ _symbolic ______pIego_ s5ErrorP
+ _symbolic _____y______SDyABSiGtG s23_ContiguousArrayStorageC So11CFStringRefa
+ _symbolic _____y______SitG s23_ContiguousArrayStorageC So11CFStringRefa
- ___unnamed_45
- ___unnamed_48
CStrings:
+ "Failed to create a sandbox extension token for the adjusted image: %s"
+ "Failed to create an image destination for the adjusted image."
+ "Failed to create temporary directory for adjusted image: %s"
+ "Failed to get sandbox extension for fileURL for uuid: %s: %@"
+ "Failed to write the %ldx%ld adjusted image; its pixel data may be unreadable."
+ "Sending adjusted image at %{public}s for uuid: %s."
+ "Sending the adjusted image's %ldx%ld surface for uuid: %s."
+ "adjusted-image.tiff"
- "Failed to get sandbox extension for fileURL for uuid: %s."
- "Failed to start accessing security scoped resource for uuid: %s."
```

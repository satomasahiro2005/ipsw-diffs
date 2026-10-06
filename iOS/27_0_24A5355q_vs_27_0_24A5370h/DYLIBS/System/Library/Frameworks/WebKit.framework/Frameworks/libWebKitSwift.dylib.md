## libWebKitSwift.dylib

> `/System/Library/Frameworks/WebKit.framework/Frameworks/libWebKitSwift.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65560` | `0x687f8` | **`+0x3298`** |
| `__AUTH.__data` | `0x1110` | `0xfb0` | **`-0x160`** |
| `__AUTH_CONST.__auth_got` | `0x1688` | `0x1798` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0xd54` | `0xc74` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x1c04` | `0x1ce4` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x3b30` | `0x3a60` | **`-0xd0`** |
| `__TEXT.__const` | `0x1e68` | `0x1f18` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x123a` | `0x12e8` | **`+0xae`** |
| `__DATA.__data` | `0xe80` | `0xf20` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x1418` | `0x1468` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x4a6` | `0x4f6` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x8ac` | `0x868` | **`-0x44`** |
| `__DATA.__bss` | `0x1728` | `0x1768` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1a90` | `0x1ad0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x988` | `0x9b0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xea8` | `0xed0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1730` | `0x1708` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x2068` | `0x2048` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x40c8` | `0x40b0` | **`-0x18`** |
| `__DATA.__common` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x74c` | `0x760` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x280` | `0x26c` | **`-0x14`** |
| `__TEXT.__swift_as_cont` | `0x2d8` | `0x2cc` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x228` | `0x21c` | **`-0xc`** |
| `__DATA_CONST.__const` | `0x1f0` | `0x1e8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x190` | `0x188` | **`-0x8`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 1700
-  Symbols:   993
-  CStrings:  163
+  Functions: 1699
+  Symbols:   1005
+  CStrings:  167
Symbols:
+ _CGColorCreate
+ _CGColorGetColorSpace
+ _CGColorSpaceCopyName
+ _CGColorSpaceCreateWithName
+ ___swift_closure_destructor.37Tm
+ ___swift_closure_destructor.41Tm
+ _kCGColorSpaceExtendedLinearSRGB
+ _symbolic SDySSSay_____GG s6UInt32V
+ _symbolic SS3key______5valuet 11ShaderGraph07_Proto_a4NodeB0C0D0V
+ _symbolic _____Sg 11ShaderGraph07_Proto_aB14NodeDefinitionV
+ _symbolic _____Sg 19RealityCoreRenderer08LowLevelC0C9ResourcesV
+ _symbolic _____Sg 19RealityCoreRenderer31LowLevelRenderContextStandaloneC9ResourcesV
+ _symbolic _____Sg 6USDKit10TokenArrayV
+ _symbolic _____Sg 6USDKit12UsdAttributeV
+ _symbolic _____Sg 6USDKit15UsdRelationshipV
+ _symbolic _____Sg 6USDKit7SdfPathV
+ _symbolic _____Sg 6USDKit7UsdPrimV
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____ySSSay_____GG s18_DictionaryStorageC 11ShaderGraph07_Proto_c4NodeD0C4EdgeV
+ _symbolic _____ySSSay_____GG s18_DictionaryStorageC s6UInt32V
+ _symbolic _____ySS_____G s18_DictionaryStorageC So16WKBridgeConstantV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11ShaderGraph07_Proto_d4NodeE0C4EdgeV
- _CACurrentMediaTime
- _CGColorCreateGenericRGB
- __DATA__TtC11WebKitSwift11IBLTextures
- __METACLASS_DATA__TtC11WebKitSwift11IBLTextures
- ___swift_closure_destructor.39Tm
- ___swift_closure_destructor.43Tm
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_WebKitSwift
- _objc_retain_x28
- _symbolic _____ 11WebKitSwift11IBLTexturesC
CStrings:
+ " could not form a CGColor with colorSpace "
+ "Exception creating material compiler "
+ "Exception creating renderer resources "
+ "Exception creating standalone resources "
+ "extendedLinearSRGB could not be constructed, should never occur"
- "Failed to make command buffer"
```

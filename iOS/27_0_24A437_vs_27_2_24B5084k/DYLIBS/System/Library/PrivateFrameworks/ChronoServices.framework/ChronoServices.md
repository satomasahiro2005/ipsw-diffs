## ChronoServices

> `/System/Library/PrivateFrameworks/ChronoServices.framework/ChronoServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x101af4` | `0x102890` | **`+0xd9c`** |
| `__AUTH.__data` | `0x3558` | `0x37f8` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_const` | `0x20298` | `0x20410` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x567e` | `0x57ee` | **`+0x170`** |
| `__TEXT.__constg_swiftt` | `0x3278` | `0x3384` | **`+0x10c`** |
| `__DATA.__data` | `0x3368` | `0x3458` | **`+0xf0`** |
| `__TEXT.__const` | `0x7a48` | `0x7b28` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x5cb0` | `0x5d68` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x3e20` | `0x3ec0` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x18b4` | `0x1920` | **`+0x6c`** |
| `__TEXT.__swift5_reflstr` | `0x19a5` | `0x19ff` | **`+0x5a`** |
| `__TEXT.__cstring` | `0x5b15` | `0x5b55` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x6c28` | `0x6c58` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x52c0` | `0x52e0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x2628` | `0x2648` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x82ec` | `0x8304` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xad8` | `0xae8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x668` | `0x678` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x31b8` | `0x31c8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x244` | `0x250` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1580` | `0x1588` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xacc0` | `0xacc8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x750` | `0x754` | **`+0x4`** |

### Other Changes

```diff

-749.0.2.0.0
+749.2.4.0.0

-  Functions: 7347
-  Symbols:   6569
-  CStrings:  1334
+  Functions: 7372
+  Symbols:   6584
+  CStrings:  1339
Symbols:
+ -[CHSMutableWidgetDescriptor setHasSnapshotSensitiveContent:]
+ -[CHSWidgetDescriptor hasSnapshotSensitiveContent]
+ GCC_except_table98
+ OBJC_IVAR_$_CHSWidgetDescriptor._hasSnapshotSensitiveContent
+ __DATA__TtCVV14ChronoServices9Signposts7Widgets23PlaceholderLoadSignpost
+ __DATA__TtCVV14ChronoServices9Signposts7Widgets29PlaceholderGenerationSignpost
+ __IVARS__TtC14ChronoServices13SmallLRUCache
+ __METACLASS_DATA__TtCVV14ChronoServices9Signposts7Widgets23PlaceholderLoadSignpost
+ __METACLASS_DATA__TtCVV14ChronoServices9Signposts7Widgets29PlaceholderGenerationSignpost
+ ___unnamed_1
+ _symbolic SDyxq_G
+ _symbolic SayxG
+ _symbolic _____ 14ChronoServices13SmallLRUCacheC
+ _symbolic _____ 14ChronoServices9SignpostsV7WidgetsV23PlaceholderLoadSignpostC
+ _symbolic _____ 14ChronoServices9SignpostsV7WidgetsV29PlaceholderGenerationSignpostC
CStrings:
+ "PlaceholderGeneration"
+ "PlaceholderLoad"
+ "Placeholders generated, <Completed>=%{name=Completed, signpost.telemetry:number1,public}ld, <Canceled>=%{name=Canceled, signpost.telemetry:number2,public}ld, %{public}s"
+ "Placeholders loaded, <TotalFetched>=%{name=TotalFetched, signpost.telemetry:number1,public}ld, <error.present>=%{name=error.present, signpost.telemetry:number2,public}s, %{public}s"
+ "hasSnapshotSensitiveContent"
```

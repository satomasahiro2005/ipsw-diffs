## TVWidgetExtension

> `/private/var/staged_system_apps/AppleTV.app/PlugIns/TVWidgetExtension.appex/TVWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcc38` | `0xbf6bc` | **`+0x2a84`** |
| `__TEXT.__const` | `0xedf4` | `0xf1b4` | **`+0x3c0`** |
| `__DATA.__data` | `0x6188` | `0x6480` | **`+0x2f8`** |
| `__DATA.__bss` | `0x13128` | `0x13348` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0x2444` | `0x225c` | **`-0x1e8`** |
| `__TEXT.__swift5_typeref` | `0x11a5c` | `0x118e8` | **`-0x174`** |
| `__TEXT.__auth_stubs` | `0x3370` | `0x3480` | **`+0x110`** |
| `__DATA_CONST.__const` | `0x5e98` | `0x5f88` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x28e4` | `0x29c4` | **`+0xe0`** |
| `__DATA.__objc_data` | `0x868` | `0x938` | **`+0xd0`** |
| `__DATA.__objc_const` | `0xf80` | `0x1038` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x2f74` | `0x3014` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x6de1` | `0x6e71` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x19c8` | `0x1a50` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0x16e5` | `0x174e` | **`+0x69`** |
| `__TEXT.__unwind_info` | `0x2d18` | `0x2d78` | **`+0x60`** |
| `__TEXT.__swift_as_entry` | `0x304` | `0x34c` | **`+0x48`** |
| `__TEXT.__swift_as_ret` | `0x24c` | `0x294` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0x331` | `0x371` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x47c` | `0x4bc` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x2dd` | `0x31b` | **`+0x3e`** |
| `__DATA_CONST.__auth_ptr` | `0x14b0` | `0x14d0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1be0` | `0x1c00` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x38fd` | `0x391d` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x4bc` | `0x4d8` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x758` | `0x770` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x1af0` | `0x1b08` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xa0` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xa88` | `0xa98` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x96c` | `0x97c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x2cc` | `0x2d8` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1cc` | `0x1d4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1145.0.2.0.1
+1145.0.6.0.0

-  Functions: 3839
-  Symbols:   347
-  CStrings:  1084
+  Functions: 3913
+  Symbols:   345
+  CStrings:  1093
Symbols:
+ _OBJC_CLASS_$__TtC17TVWidgetExtension23VUINetworkResponseProxy
+ _OBJC_CLASS_$__TtC17TVWidgetExtension25VUIUTSNetworkManagerProxy
+ _OBJC_METACLASS_$__TtC17TVWidgetExtension23VUINetworkResponseProxy
+ _OBJC_METACLASS_$__TtC17TVWidgetExtension25VUIUTSNetworkManagerProxy
+ _swift_cvw_instantiateLayoutString
- _NSForegroundColorAttributeName
- _OBJC_CLASS_$_UIBezierPath
- _OBJC_CLASS_$_UIGraphicsImageRenderer
- _OBJC_CLASS_$__TtC17TVWidgetExtension24TVUTSNetworkManagerProxy
- _OBJC_METACLASS_$__TtC17TVWidgetExtension24TVUTSNetworkManagerProxy
- _objc_retain_x9
- _swift_isEscapingClosureAtFileLocation
CStrings:
+ "?"
+ "@40@0:8@16@24^@32"
+ "T@\"NSData\",N,R"
+ "T@\"NSDictionary\",N,R"
+ "TVWidgetExtension.VUINetworkResponseProxy"
+ "_TtC17TVWidgetExtension23VUINetworkResponseProxy"
+ "_TtC17TVWidgetExtension25VUIUTSNetworkManagerProxy"
+ "caller"
+ "createURLRequestFromRequestProperties:urlRequest:completion:"
+ "headerFields"
+ "headers"
+ "httpBody"
+ "httpMethod"
+ "options"
+ "queryParameters"
+ "timeout"
+ "v24@?0@\"_TtC17TVWidgetExtension23VUINetworkResponseProxy\"8@\"NSError\"16"
+ "v28@0:8B16@?<v@?@\"_TtC17TVWidgetExtension23VUINetworkResponseProxy\"@\"NSError\">20"
+ "vui_sortedQueryItemsFromDictionary:"
- "_TtC17TVWidgetExtension24TVUTSNetworkManagerProxy"
- "bezierPathWithRoundedRect:cornerRadius:"
- "drawAtPoint:withAttributes:"
- "fill"
- "imageWithActions:"
- "initWithSize:"
- "setFill"
- "v16@?0@\"UIGraphicsImageRendererContext\"8"
- "v28@0:8B16@?<v@?@\"AMSURLResult\"@\"NSError\">20"
- "whiteColor"
```

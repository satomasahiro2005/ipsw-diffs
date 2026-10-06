## TVIntentsExtension

> `/private/var/staged_system_apps/AppleTV.app/PlugIns/TVIntentsExtension.appex/TVIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36dc` | `0x5948` | **`+0x226c`** |
| `__TEXT.__auth_stubs` | `0x530` | `0x830` | **`+0x300`** |
| `__DATA.__bss` | `0x10` | `0x190` | **`+0x180`** |
| `__DATA_CONST.__auth_got` | `0x2a8` | `0x428` | **`+0x180`** |
| `__TEXT.__const` | `0x158` | `0x288` | **`+0x130`** |
| `__TEXT.__objc_methname` | `0x5c8` | `0x6f7` | **`+0x12f`** |
| `__TEXT.__objc_stubs` | `0x4e0` | `0x5e0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x358` | `0x440` | **`+0xe8`** |
| `__DATA.__objc_data` | `0x1d0` | `0x2a0` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x2c0` | `0x378` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x398` | `0x440` | **`+0xa8`** |
| `__DATA_CONST.__auth_ptr` | `0x20` | `0xb0` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x268` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0xd2` | `0x141` | **`+0x6f`** |
| `__DATA.__data` | `0x118` | `0x180` | **`+0x68`** |
| `__TEXT.__objc_methtype` | `0x35d` | `0x3c2` | **`+0x65`** |
| `__TEXT.__constg_swiftt` | `0x94` | `0xf4` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x238` | `0x290` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x20` | `0x70` | **`+0x50`** |
| `__TEXT.__cstring` | `0xa1` | `0xe2` | **`+0x41`** |
| `__TEXT.__objc_classname` | `0xb3` | `0xf4` | **`+0x41`** |
| `__TEXT.__objc_methlist` | `0x23c` | `0x27c` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x3e` | **`+0x3e`** |
| `__DATA_CONST.__got` | `0x98` | `0xc8` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x2c` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__swift5_capture`

### Other Changes

```diff

-1145.0.2.0.1
+1145.0.6.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /usr/lib/swift/libswiftCoreImage.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 90
-  Symbols:   113
-  CStrings:  127
+  Functions: 138
+  Symbols:   135
+  CStrings:  146
Symbols:
+ _OBJC_CLASS_$__TtC18TVIntentsExtension23VUINetworkResponseProxy
+ _OBJC_CLASS_$__TtC18TVIntentsExtension25VUIUTSNetworkManagerProxy
+ _OBJC_METACLASS_$__TtC18TVIntentsExtension23VUINetworkResponseProxy
+ _OBJC_METACLASS_$__TtC18TVIntentsExtension25VUIUTSNetworkManagerProxy
+ __swiftEmptyArrayStorage
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_stdlib_reportUnimplementedInitializer
+ _malloc_size
+ _objc_autorelease
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x25
+ _swift_allocError
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_bridgeObjectRetain
+ _swift_deletedMethodError
+ _swift_dynamicCast
+ _swift_getWitnessTable
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release_x19
+ _swift_retain
+ _swift_willThrow
- _OBJC_CLASS_$__TtC18TVIntentsExtension24TVUTSNetworkManagerProxy
- _OBJC_METACLASS_$__TtC18TVIntentsExtension24TVUTSNetworkManagerProxy
- _swift_release_x23
CStrings:
+ ".cxx_destruct"
+ "?"
+ "@40@0:8@16@24^@32"
+ "T@\"NSData\",N,R"
+ "T@\"NSDictionary\",N,R"
+ "TVIntentsExtension.VUINetworkResponseProxy"
+ "_TtC18TVIntentsExtension23VUINetworkResponseProxy"
+ "_TtC18TVIntentsExtension25VUIUTSNetworkManagerProxy"
+ "caller"
+ "createURLRequestFromRequestProperties:urlRequest:completion:"
+ "headerFields"
+ "headers"
+ "httpBody"
+ "httpMethod"
+ "init()"
+ "options"
+ "queryParameters"
+ "timeout"
+ "v16@0:8"
+ "v28@0:8B16@?<v@?@\"_TtC18TVIntentsExtension23VUINetworkResponseProxy\"@\"NSError\">20"
+ "vui_sortedQueryItemsFromDictionary:"
- "_TtC18TVIntentsExtension24TVUTSNetworkManagerProxy"
- "v28@0:8B16@?<v@?@\"AMSURLResult\"@\"NSError\">20"
```

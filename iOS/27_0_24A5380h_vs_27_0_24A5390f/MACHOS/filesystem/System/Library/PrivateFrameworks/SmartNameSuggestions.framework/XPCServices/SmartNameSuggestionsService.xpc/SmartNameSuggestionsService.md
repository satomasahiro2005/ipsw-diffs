## SmartNameSuggestionsService

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/XPCServices/SmartNameSuggestionsService.xpc/SmartNameSuggestionsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17230` | `0x171f0` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x510` | `0x540` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x14a0` | `0x1490` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xa58` | `0xa50` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-19.0.0.0.0
+21.0.0.0.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib

-  Symbols:   197
+  Symbols:   203
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftModelIO
Functions:
~ sub_100001c58 -> sub_100001e08 : 604 -> 600
~ sub_100002178 -> sub_100002324 : 620 -> 616
~ sub_100002428 -> sub_1000025d0 : 3032 -> 3028
~ sub_10000356c -> sub_100003710 : 1476 -> 1472
~ sub_100006280 -> sub_100006420 : 3032 -> 3028
~ sub_10000aa50 -> sub_10000abec : 1500 -> 1496
~ sub_10000e7c8 -> sub_10000e960 : 3640 -> 3600
```

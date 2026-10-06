## FindMyWidgetItems

> `/private/var/staged_system_apps/FindMy.app/PlugIns/FindMyWidgetItems.appex/FindMyWidgetItems`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33b54` | `0x33c04` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0xdf4` | `0xe1c` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1068` | `0x1080` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x24f0` | `0x2500` | **`+0x10`** |
| `__TEXT.__const` | `0x25c4` | `0x25d4` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1280` | `0x1288` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xb30` | `0xb38` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x610` | `0x618` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb70` | `0xb78` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x7c` | `0x80` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x80` | `0x84` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-470.30.6.14.10
+470.30.6.14.19

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCallKit.dylib

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Functions: 951
-  Symbols:   189
+  Functions: 952
+  Symbols:   192
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
Functions:
+ sub_100022628
```

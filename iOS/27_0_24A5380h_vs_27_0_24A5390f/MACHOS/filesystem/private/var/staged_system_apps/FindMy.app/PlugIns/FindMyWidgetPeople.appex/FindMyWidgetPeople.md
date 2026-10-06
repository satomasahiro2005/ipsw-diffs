## FindMyWidgetPeople

> `/private/var/staged_system_apps/FindMy.app/PlugIns/FindMyWidgetPeople.appex/FindMyWidgetPeople`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x335dc` | `0x336cc` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0x2280` | `0x22c0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1044` | `0x106c` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x1148` | `0x1168` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xf80` | `0xf98` | **`+0x18`** |
| `__TEXT.__const` | `0x23b4` | `0x23c4` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xa80` | `0xa88` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x590` | `0x598` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb80` | `0xb88` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x7c` | `0x80` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x90` | `0x94` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
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

-  Functions: 930
-  Symbols:   180
+  Functions: 931
+  Symbols:   185
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ _objc_release_x26
+ _objc_retain_x24
```

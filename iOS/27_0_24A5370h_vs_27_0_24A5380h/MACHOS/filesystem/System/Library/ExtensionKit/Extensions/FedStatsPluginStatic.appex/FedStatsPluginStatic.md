## FedStatsPluginStatic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginStatic.appex/FedStatsPluginStatic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd90` | `0x98c` | **`-0x404`** |
| `__TEXT.__swift5_typeref` | `0x74` | `0x46` | **`-0x2e`** |
| `__DATA_CONST.__const` | `0xc8` | `0xe8` | **`+0x20`** |
| `__DATA.__data` | `0x28` | `0x10` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x38` | `0x20` | **`-0x18`** |
| `__TEXT.__const` | `0x12a` | `0x112` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0xc0` | `0xa8` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x1f0` | `0x200` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x68` | `0x60` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x4` | `0x8` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-31.0.0.0.0
+35.0.0.0.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 24
+  Functions: 19
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ _swift_bridgeObjectRelease
+ _swift_release_x21
+ _swift_release_x8
- __swiftEmptyArrayStorage
- __swiftEmptyDictionarySingleton
- _swift_bridgeObjectRetain
- _swift_getTypeByMangledNameInContext2
- _swift_release_x20
- _swift_release_x23
- _swift_retain_x20
```

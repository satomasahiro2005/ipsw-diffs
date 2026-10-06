## SiriMailFlowTools

> `/System/Library/FlowTools/Tools/SiriMailFlowTools.flowtool/SiriMailFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4840c` | `0x46c0c` | **`-0x1800`** |
| `__TEXT.__eh_frame` | `0x3e90` | `0x3e10` | **`-0x80`** |
| `__DATA_CONST.__const` | `0xa30` | `0xa60` | **`+0x30`** |
| `__TEXT.__const` | `0x14f0` | `0x14c0` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x318` | `0x2f0` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0x1330` | `0x1350` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x5fe` | `0x616` | **`+0x18`** |
| `__DATA.__bss` | `0x1460` | `0x1450` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x9a0` | `0x9b0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xe0` | `0xf0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x13a8` | `0x1398` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x748` | `0x740` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.17.4.0.0
+3600.23.4.0.0

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Functions: 1496
-  Symbols:   141
+  Functions: 1471
+  Symbols:   142
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
```

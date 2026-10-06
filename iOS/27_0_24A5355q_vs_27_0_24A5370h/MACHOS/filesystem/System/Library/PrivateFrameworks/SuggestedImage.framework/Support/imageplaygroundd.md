## imageplaygroundd

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfdf8` | `0x1004c` | **`+0x254`** |
| `__TEXT.__oslogstring` | `0x6df` | `0x72f` | **`+0x50`** |
| `__DATA.__objc_const` | `0x5d0` | `0x5b0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x459` | `0x439` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1c7` | `0x1a7` | **`-0x20`** |
| `__DATA.__data` | `0xaa0` | `0xa90` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x4b0` | `0x4a0` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0xe50` | `0xe60` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x258` | `0x24c` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x730` | `0x738` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x178` | `0x170` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0xd50` | `0xd48` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x34d` | `0x347` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-186.1.101.0.0
+190.0.0.0.0

-  - /usr/lib/swift/libswiftAccelerate.dylib

-  - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 278
-  Symbols:   351
+  Functions: 277
+  Symbols:   349
Symbols:
+ _$sScT6cancelyyF
+ _swift_release_x22
- _$s14SuggestedImage0aB8ProviderCMn
- __swift_FORCE_LOAD_$_swiftAccelerate
- __swift_FORCE_LOAD_$_swiftsimd
- _swift_retain_x23
CStrings:
+ "Personalization producer background task expired - cancelling task"
- "suggestedImageProvider"
```

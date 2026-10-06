## HomeControlService

> `/Applications/HomeControlService.app/HomeControlService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31ac` | `0x3264` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x198` | `0x1c8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x199` | `0x1ba` | **`+0x21`** |
| `__TEXT.__objc_methname` | `0x1c8d` | `0x1ca0` | **`+0x13`** |
| `__TEXT.__cstring` | `0xd8` | `0xe8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x73c` | `0x74c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x730` | `0x738` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1232.3.0.0.0
+1238.0.0.0.0

+  - /usr/lib/swift/libswiftCallKit.dylib

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

+  - /usr/lib/swift/libswiftMLCompute.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib
+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 86
-  Symbols:   168
-  CStrings:  381
+  Functions: 87
+  Symbols:   174
+  CStrings:  385
Symbols:
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
Functions:
+ sub_1000031e8
CStrings:
+ "%@ hcs_setForeground: %{public}s"
+ "background"
+ "foreground"
+ "hcs_setForeground:"
```

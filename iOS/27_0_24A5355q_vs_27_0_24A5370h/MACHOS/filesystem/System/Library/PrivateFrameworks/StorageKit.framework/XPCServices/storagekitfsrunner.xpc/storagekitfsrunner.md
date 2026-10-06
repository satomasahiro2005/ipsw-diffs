## storagekitfsrunner

> `/System/Library/PrivateFrameworks/StorageKit.framework/XPCServices/storagekitfsrunner.xpc/storagekitfsrunner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3afc` | `0x3be4` | **`+0xe8`** |
| `__TEXT.__objc_methname` | `0xd4c` | `0xd71` | **`+0x25`** |
| `__DATA.__objc_selrefs` | `0x490` | `0x498` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5a4` | `0x5ac` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1075.0.0.0.0
+1076.0.0.0.0

-  Functions: 126
+  Functions: 127

-  CStrings:  295
+  CStrings:  296
Functions:
~ _SKLogArrayRedacted : 444 -> 440
~ _SKLogSetRedacted : 444 -> 440
+ sub_100001f64
CStrings:
+ "errorWithCode:underlyingError:error:"
```

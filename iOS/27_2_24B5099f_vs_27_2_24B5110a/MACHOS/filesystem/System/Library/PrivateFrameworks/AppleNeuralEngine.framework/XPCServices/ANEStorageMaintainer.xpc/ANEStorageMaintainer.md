## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/ANEStorageMaintainer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8720` | `0x7fa4` | **`-0x77c`** |
| `__TEXT.__gcc_except_tab` | `0x168` | `—` | **`-0x168`** |
| `__TEXT.__oslogstring` | `0x107a` | `0xfec` | **`-0x8e`** |
| `__DATA_CONST.__const` | `0x118` | `0xc8` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x590` | `0x550` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x198` | `0x158` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x2d8` | `0x2b0` | **`-0x28`** |
| `__TEXT.__cstring` | `0x1ee` | `0x1d0` | **`-0x1e`** |
| `__DATA.__bss` | `0x38` | `0x30` | **`-0x8`** |
| `__TEXT.__const` | `0xd0` | `0xc8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-382.101.0.0.0
+382.101.2.0.0

-  Functions: 115
-  Symbols:   405
-  CStrings:  343
+  Functions: 112
+  Symbols:   393
+  CStrings:  338
Symbols:
- GCC_except_table11
- GCC_except_table6
- __43+[_ANEStorageHelper memoryMapWeightAtPath:]_block_invoke
- __72+[_ANEStorageHelper memoryMapModelAtPath:isPrecompiled:modelAttributes:]_block_invoke
- __Unwind_Resume
- ___block_descriptor_192_e8_32r_e5_v8?0lr32l8
- ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
- ___objc_personality_v0
- __gAsyncIOq
- _dispatch_async
- _dispatch_queue_attr_make_with_autorelease_frequency
- _fcntl
CStrings:
- "%@: fcntl(F_RDADVISE). errno=%d : %s"
- "_ANED_MODEL_READ_ADVISE"
- "_ANED_WEIGHT_READ_ADVISE"
- "com.apple.aned.storageAsyncIO"
- "size=%d\n %{public, signpost.description:begin_time}llu "
```

## ANECompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANECompilerService.xpc/ANECompilerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19cdc` | `0x19590` | **`-0x74c`** |
| `__TEXT.__gcc_except_tab` | `0x1288` | `0x1120` | **`-0x168`** |
| `__TEXT.__oslogstring` | `0x25e2` | `0x2554` | **`-0x8e`** |
| `__DATA_CONST.__const` | `0x348` | `0x2f8` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x440` | `0x410` | **`-0x30`** |
| `__TEXT.__cstring` | `0x1303` | `0x12e5` | **`-0x1e`** |
| `__TEXT.__auth_stubs` | `0x8a0` | `0x890` | **`-0x10`** |
| `__DATA.__bss` | `0x88` | `0x80` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x468` | `0x460` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-382.101.0.0.0
+382.101.2.0.0

-  Functions: 314
-  Symbols:   968
-  CStrings:  882
+  Functions: 313
+  Symbols:   963
+  CStrings:  877
Symbols:
- __43+[_ANEStorageHelper memoryMapWeightAtPath:]_block_invoke
- __72+[_ANEStorageHelper memoryMapModelAtPath:isPrecompiled:modelAttributes:]_block_invoke
- ___block_descriptor_192_e8_32r_e5_v8?0lr32l8
- ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
- _fcntl
CStrings:
- "%@: fcntl(F_RDADVISE). errno=%d : %s"
- "_ANED_MODEL_READ_ADVISE"
- "_ANED_WEIGHT_READ_ADVISE"
- "com.apple.aned.storageAsyncIO"
- "size=%d\n %{public, signpost.description:begin_time}llu "
```

## libBKDM2.dylib

> `/usr/lib/libBKDM2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7cabc` | `0x7c2d8` | **`-0x7e4`** |
| `__AUTH_CONST.__cfstring` | `0x65a0` | `0x65e0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x730` | `0x768` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x4720` | `0x46ec` | **`-0x34`** |
| `__AUTH_CONST.__objc_const` | `0x9a28` | `0x9a58` | **`+0x30`** |
| `__TEXT.__cstring` | `0x7041` | `0x7066` | **`+0x25`** |
| `__TEXT.__unwind_info` | `0xe20` | `0xe30` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x17c0` | `0x17b4` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x450` | `0x448` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d58` | `0x3d60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xac8` | `0xacc` | **`+0x4`** |

### Other Changes

```diff

-980.0.18.0.0
+980.0.26.0.0

-  Functions: 2904
-  Symbols:   4344
-  CStrings:  1608
+  Functions: 2905
+  Symbols:   4348
+  CStrings:  1613
Symbols:
+ -[BioLog cameraRotation]
+ -[BioLog setCameraRotation:]
+ _OBJC_IVAR_$_BioLog._cameraRotation
+ _OUTLINED_FUNCTION_59
+ _OUTLINED_FUNCTION_60
+ ___error
+ _fclose
+ _ferror
+ _fileno
+ _fopen
+ _fread
+ _fstat
- +[BLRetention applyCustomerPolicyForType:withSequenceDirs:withSize:]
- +[BLRetention applyCustomerPolicyWithPath:]
- ___62+[BLRetention applyPolicyWithPath:sizeLimit:freeMissingSpace:]_block_invoke_2
- ___68+[BLRetention applyCustomerPolicyForType:withSequenceDirs:withSize:]_block_invoke
- ___68+[BLRetention applyCustomerPolicyForType:withSequenceDirs:withSize:]_block_invoke_2
- ___68+[BLRetention applyCustomerPolicyForType:withSequenceDirs:withSize:]_block_invoke_3
- ___68+[BLRetention applyCustomerPolicyForType:withSequenceDirs:withSize:]_block_invoke_4
- __dispatch_queue_attr_concurrent
CStrings:
+ "Limiting latest sequences (last %u minutes), count %lu ...\n"
+ "bytesRead == fileSize"
+ "file"
+ "fileSize > 0"
+ "fopen:%@ failed, errno:%u\n"
+ "fread:%@ failed\n"
+ "fstat:%@ failed, errno:%u\n"
+ "rb"
+ "sec-"
- "Applying customer retention policy...\n"
- "Customer retention fullfilled! Turn customer logging off for some time?\n"
- "Customer retention policy removed %.3fMB in %fs, resulting size %luMB\n"
- "dcnKernels"
```

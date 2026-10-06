## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12d45c` | `0x12dc84` | **`+0x828`** |
| `__TEXT.__objc_methlist` | `0xe97c` | `0xe9dc` | **`+0x60`** |
| `__TEXT.__cstring` | `0x14e47` | `0x14ea2` | **`+0x5b`** |
| `__AUTH_CONST.__objc_const` | `0x25008` | `0x25060` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x115a0` | `0x115e0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x70a8` | `0x70e0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x5918` | `0x5948` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x61f8` | `0x6220` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x8b04` | `0x8b24` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x10d4` | `0x10d8` | **`+0x4`** |

### Other Changes

```diff

-4838.0.93.0.0
+4838.0.125.0.0

-  Functions: 7455
-  Symbols:   11203
-  CStrings:  4058
+  Functions: 7467
+  Symbols:   11219
+  CStrings:  4062
Symbols:
+ +[FPTask exec:environment:stdinHandle:stdoutString:stderrString:error:]
+ +[FPTask freePreparedEnvpArray:]
+ -[FPItemManager outOfBandIndexItemIDs:completionHandler:]
+ -[FPTask environment]
+ -[FPTask newPreparedEnvpArray]
+ -[FPTask setEnvironment:]
+ -[NSURL(FPAdditions) fp_pathOnlyRelationshipToItemAtURL:]
+ GCC_except_table104
+ GCC_except_table115
+ GCC_except_table137
+ GCC_except_table90
+ GCC_except_table95
+ _FPPrivateNormalizedPath
+ _FPURLIsFSKitStorage
+ _OBJC_IVAR_$_FPTask._environment
+ ___30-[FPTask newPreparedEnvpArray]_block_invoke
+ ___71+[FPTask exec:environment:stdinHandle:stdoutString:stderrString:error:]_block_invoke
+ ___block_descriptor_48_e8_32r_e35_v32?0"NSString"8"NSString"16^B24lr32l8
+ _fpfs_get_provider_content_version
+ _fpfs_remove_provider_content_version
- GCC_except_table121
- GCC_except_table136
- GCC_except_table79
- ___59+[FPTask exec:stdinHandle:stdoutString:stderrString:error:]_block_invoke
CStrings:
+ "%@=%@"
+ "/private/"
+ "4838.0.125"
+ "com.apple.genstore.fp_provider_cver#C"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
- "4838.0.93"
```

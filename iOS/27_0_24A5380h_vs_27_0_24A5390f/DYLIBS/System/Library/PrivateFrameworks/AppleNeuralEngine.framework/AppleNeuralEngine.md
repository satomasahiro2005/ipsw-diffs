## AppleNeuralEngine

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x569b4` | `0x57ec0` | **`+0x150c`** |
| `__TEXT.__oslogstring` | `0xb6c8` | `0xb883` | **`+0x1bb`** |
| `__TEXT.__gcc_except_tab` | `0x676c` | `0x67d0` | **`+0x64`** |
| `__AUTH_CONST.__cfstring` | `0x4a60` | `0x4a80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x387b` | `0x3893` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a18` | `0x1a28` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x678` | `0x680` | **`+0x8`** |
| `__DATA.__data` | `0x710` | `0x718` | **`+0x8`** |
| `__TEXT.__const` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2b8c` | `0x2b94` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1410` | `0x1418` | **`+0x8`** |

### Other Changes

```diff

-382.11.0.0.0
+382.12.0.0.0

-  Functions: 1718
+  Functions: 1726

-  CStrings:  1421
+  CStrings:  1433
Symbols:
+ +[_ANECloneHelper stageInBundleFileConstantsForModel:srcDir:dstDir:cloneDirectory:]
+ _OUTLINED_FUNCTION_39
+ ___block_descriptor_116_e8_32s40s48s56s64r72r80r_e5_v8?0ls32l8r64l8s40l8r72l8s48l8s56l8r80l8
+ ___block_descriptor_116_e8_32s40s48s56s64r72r80r_e5_v8?0ls32l8r64l8s40l8s48l8r72l8s56l8r80l8
+ ___block_descriptor_116_e8_32s40s48s56s64r72r80r_e5_v8?0ls32l8r64l8s40l8s48l8s56l8r72l8r80l8
+ ___block_descriptor_124_e8_32s40s48s56s64s72r80r88r_e5_v8?0ls32l8r72l8s40l8s48l8s56l8r80l8s64l8r88l8
+ ___block_descriptor_124_e8_32s40s48s56s64s72r80r88r_e5_v8?0ls32l8r72l8s40l8s48l8s56l8s64l8r80l8r88l8
+ _kANEDCompilerQoSHintKey
+ _strnlen
- ___44-[_ANEClient doLoadModel:options:qos:error:]_block_invoke_2
- ___45-[_ANEClient compileModel:options:qos:error:]_block_invoke_2
- ___46-[_ANEClient doUnloadModel:options:qos:error:]_block_invoke_2
- ___71-[_ANEClient doPrepareChainingWithModel:options:chainingReq:qos:error:]_block_invoke_2
- ___block_descriptor_100_e8_32s40s48s56s64r72r_e5_v8?0ls32l8s40l8r64l8s48l8s56l8r72l8
- ___block_descriptor_100_e8_32s40s48s56s64r72r_e5_v8?0ls32l8s40l8s48l8s56l8r64l8r72l8
- ___block_descriptor_92_e8_32s40s48s56r64r_e5_v8?0ls32l8r56l8s40l8s48l8r64l8
- ___block_descriptor_92_e8_32s40s48s56r64r_e5_v8?0ls32l8s40l8r56l8s48l8r64l8
- ___block_descriptor_92_e8_32s40s48s56r64r_e5_v8?0ls32l8s40l8s48l8r56l8r64l8
CStrings:
+ "%@: buildVersion (%zu bytes) larger than max buffer size %d, truncated\n"
+ "%@: copyfile(%@, %@) FAILED errno=%d (%s)"
+ "%@: createDirectory(%@) FAILED: %@"
+ "%@: in-bundle FileConstants rebase failed for %@"
+ "%@: in-bundle FileConstants staging failed for %@"
+ "_ANEF_COMPILE_PRIORITY_WAIT"
+ "_ANEF_LOAD_NEW_INSTANCE_PRIORITY_WAIT"
+ "_ANEF_LOAD_PRIORITY_WAIT"
+ "_ANEF_PREP_CHAIN_PRIORITY_WAIT"
+ "_ANEF_UNLOAD_PRIORITY_WAIT"
+ "kANEDCompilerQoSHintKey"
+ "qos:%u model.string_id:%llu priorityWaitMs:%f"
```

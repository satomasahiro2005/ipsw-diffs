## HomeAI

> `/System/Library/PrivateFrameworks/HomeAI.framework/HomeAI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17a5ac` | `0x17a178` | **`-0x434`** |
| `__TEXT.__oslogstring` | `0xe312` | `0xe3b8` | **`+0xa6`** |
| `__AUTH_CONST.__cfstring` | `0x89a0` | `0x8a00` | **`+0x60`** |
| `__TEXT.__cstring` | `0xd954` | `0xd9b0` | **`+0x5c`** |
| `__TEXT.__gcc_except_tab` | `0xc208` | `0xc1ec` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0xc30` | `0xc48` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x47c8` | `0x47d0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xa21c` | `0xa214` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x5078` | `0x5080` | **`+0x8`** |

### Other Changes

```diff

-374.0.0.0.0
+377.0.0.0.0

-  CStrings:  3181
+  CStrings:  3188
Symbols:
+ -[HMIVideoAnalyzerScheduler deregisterAnalyzer:]
+ ___block_descriptor_72_e8_32s40r48r56r64r_e28_v24?0"MADHKSVCaption"8^B16lr40l8s32l8r48l8r56l8r64l8
- -[HMIVCPHomeKitAnalysisSession processVideoFragmentAssetData:withOptions:andCompletionHandler:]
- ___block_descriptor_64_e8_32s40r48r56r_e28_v24?0"MADHKSVCaption"8^B16lr40l8r48l8r56l8s32l8
CStrings:
+ "Noteworthiness caption text was nil"
+ "Received noteworthiness caption with nil text"
+ "Received summary caption with nil text"
+ "Received title caption with nil text"
+ "Summary caption text was nil"
+ "Title caption text was nil"
+ "[%{public}@] Received noteworthiness caption with nil text"
+ "[%{public}@] Received summary caption with nil text"
+ "[%{public}@] Received title caption with nil text"
- "Failed to create caption with title: %@ summary: %@"
- "[%{public}@] Failed to create caption with title: %@ summary: %@"
```

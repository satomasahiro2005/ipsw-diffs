## CloudDocs

> `/System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f0c0` | `0x7f248` | **`+0x188`** |
| `__AUTH.__objc_data` | `0x1770` | `0x16d0` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x780` | `0x820` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xb884` | `0xb830` | **`-0x54`** |
| `__TEXT.__oslogstring` | `0x8d76` | `0x8d46` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x2478` | `0x24a0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x5f20` | `0x5f00` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4250` | `0x4240` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x66ec` | `0x66dc` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2640` | `0x2650` | **`+0x10`** |

### Other Changes

```diff

-5140.0.0.0.2
+5168.0.5.0.2

-  Functions: 3030
-  Symbols:   5110
-  CStrings:  2202
+  Functions: 3032
+  Symbols:   5116
+  CStrings:  2199
Symbols:
+ -[BRContainer(BRInternalAdditions) deleteAllContentsOnClientAndServer:error:]
+ GCC_except_table100
+ GCC_except_table102
+ GCC_except_table105
+ GCC_except_table107
+ GCC_except_table108
+ GCC_except_table116
+ GCC_except_table118
+ GCC_except_table127
+ GCC_except_table131
+ GCC_except_table135
+ GCC_except_table140
+ GCC_except_table147
+ GCC_except_table153
+ GCC_except_table155
+ GCC_except_table161
+ GCC_except_table172
+ GCC_except_table176
+ GCC_except_table181
+ GCC_except_table189
+ GCC_except_table194
+ GCC_except_table204
+ GCC_except_table206
+ GCC_except_table230
+ GCC_except_table77
+ __OBJC_$_CLASS_METHODS_BRContainer(BRXcodeAdditions|BRXcodeInternalAdditions|BRFinderAdditions|BRInternalAdditions|BRPriorityHinting)
+ __OBJC_$_INSTANCE_METHODS_BRContainer(BRXcodeAdditions|BRXcodeInternalAdditions|BRFinderAdditions|BRInternalAdditions|BRPriorityHinting)
+ ___77-[BRContainer(BRInternalAdditions) deleteAllContentsOnClientAndServer:error:]_block_invoke
+ ___BRiWorkSharingGetFullSharingInfo_block_invoke_4
+ ___BRiWorkSharingGetFullSharingInfo_block_invoke_5
+ ___BRiWorkSharingSetSharingState_block_invoke_3
+ ___BRiWorkSharingSetSharingState_block_invoke_4
+ ___BRiWorkSharingSetSharingState_block_invoke_5
+ ___block_descriptor_48_e8_32s40bs_e69_v24?0"BRXPCAutomaticErrorProxy<BRItemServiceProtocol>"8"NSError"16ls32l8s40l8
+ ___block_descriptor_50_e8_32s40bs_e69_v24?0"BRXPCAutomaticErrorProxy<BRItemServiceProtocol>"8"NSError"16ls32l8s40l8
- +[NSString(BRPathAdditions) br_reimportDomainErrorInfoPath]
- -[BRContainer(BRFinderAdditions) deleteAllContentsOnClientAndServer:]
- -[BRContainer(BRFinderInternalAdditions) deleteAllContentsOnClientAndServer:error:]
- GCC_except_table104
- GCC_except_table112
- GCC_except_table128
- GCC_except_table133
- GCC_except_table136
- GCC_except_table141
- GCC_except_table148
- GCC_except_table154
- GCC_except_table157
- GCC_except_table164
- GCC_except_table170
- GCC_except_table175
- GCC_except_table182
- GCC_except_table191
- GCC_except_table195
- GCC_except_table205
- GCC_except_table207
- GCC_except_table231
- GCC_except_table73
- GCC_except_table92
- GCC_except_table94
- GCC_except_table99
- __OBJC_$_CLASS_METHODS_BRContainer(BRXcodeAdditions|BRXcodeInternalAdditions|BRFinderAdditions|BRFinderInternalAdditions|BRInternalAdditions|BRPriorityHinting)
- __OBJC_$_INSTANCE_METHODS_BRContainer(BRXcodeAdditions|BRXcodeInternalAdditions|BRFinderAdditions|BRFinderInternalAdditions|BRInternalAdditions|BRPriorityHinting)
- ___83-[BRContainer(BRFinderInternalAdditions) deleteAllContentsOnClientAndServer:error:]_block_invoke
- ___block_descriptor_56_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s40l8s48l8
CStrings:
+ "-[BRContainer(BRInternalAdditions) deleteAllContentsOnClientAndServer:error:]"
+ "-[BRContainer(BRInternalAdditions) deleteAllContentsOnClientAndServer:error:]_block_invoke"
+ "5168.0.5.0.2"
- "-[BRContainer(BRFinderInternalAdditions) deleteAllContentsOnClientAndServer:error:]"
- "-[BRContainer(BRFinderInternalAdditions) deleteAllContentsOnClientAndServer:error:]_block_invoke"
- "5140.0.0.0.2"
- "BRiWorkSharingSetSharingState_block_invoke_2"
- "[ERROR] Failed publishing document at %@ - %@%@"
- "reimport_domain_error_info"
```

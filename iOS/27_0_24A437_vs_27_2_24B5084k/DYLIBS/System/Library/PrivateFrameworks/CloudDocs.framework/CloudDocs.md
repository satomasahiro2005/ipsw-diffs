## CloudDocs

> `/System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f1b0` | `0x7ea40` | **`-0x770`** |
| `__TEXT.__gcc_except_tab` | `0x3b68` | `0x3c28` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x1060` | `0x10c0` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0xdb30` | `0xdb88` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x8d22` | `0x8d78` | **`+0x56`** |
| `__TEXT.__cstring` | `0xb89c` | `0xb8ea` | **`+0x4e`** |
| `__DATA_CONST.__const` | `0x24a8` | `0x24e8` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x66e4` | `0x6724` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x4248` | `0x4270` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2648` | `0x2660` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xa60` | `0xa68` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x8d8` | `0x8e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5e8` | `0x5ec` | **`+0x4`** |

### Other Changes

```diff

-5168.0.55.0.0
+5168.40.149.0.1

-  Functions: 3032
-  Symbols:   5118
-  CStrings:  2202
+  Functions: 3045
+  Symbols:   5130
+  CStrings:  2204
Symbols:
+ +[BRFileProviderHelper br_appHasNonUploadedFiles:completion:]
+ +[BRXPCClientUtils executeWithMaxRetries:retriableError:error:block:]
+ -[BRWaitForContainersDownloadOperation setUnregisterPriorityHintOnFinish:]
+ -[BRWaitForContainersDownloadOperation unregisterPriorityHintOnFinish]
+ _ACErrorDomain
+ _FPAppHasNonUploadedFiles
+ _OBJC_IVAR_$_BRWaitForContainersDownloadOperation._unregisterPriorityHintOnFinish
+ ___57+[BRXPCClientUtils executeXPCWithMaxRetries:error:block:]_block_invoke
+ ___64-[ACAccountStore(BRAdditions) _br_getAllAppleAccountsWithError:]_block_invoke
+ ___64-[ACAccountStore(BRAdditions) _br_getAllAppleAccountsWithError:]_block_invoke_2
+ ___77-[NSFileProviderDomain(BRAdditions) br_volumeUUIDForDataSeparated:withError:]_block_invoke
+ ___block_descriptor_32_e17_B16?0"NSError"8l
+ ___block_descriptor_48_e8_32s40r_e9_B16?0^8lr40l8s32l8
- _BRReadOnlyShareUploadErrorCategory
CStrings:
+ "+[BRXPCClientUtils executeWithMaxRetries:retriableError:error:block:]"
+ "5168.40.149.0.1"
+ "B16@?0@\"NSError\"8"
+ "Failed fetching the apple accounts from the accounts store: %@"
+ "Got a nil accounts array back from the accounts store without an error"
+ "[NOTICE] Accounts store returned %lu apple accounts, %lu of them active%@"
+ "[NOTICE] Block execution failed with a retriable error - retrying: %@%@"
- "+[BRXPCClientUtils executeXPCWithMaxRetries:error:block:]"
- "5168.0.55"
- "Got nil accounts array back from Accounts Store accountsWithAccountType"
- "[NOTICE] Block execution failed because of XPC - retrying%@"
- "readOnlyShareUpload"
```

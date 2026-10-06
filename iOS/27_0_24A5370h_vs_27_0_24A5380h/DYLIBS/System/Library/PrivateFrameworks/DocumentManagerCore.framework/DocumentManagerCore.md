## DocumentManagerCore

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ebb8` | `0x6f144` | **`+0x58c`** |
| `__AUTH.__objc_data` | `0x558` | `0x438` | **`-0x120`** |
| `__DATA_DIRTY.__objc_data` | `0x1010` | `0x1130` | **`+0x120`** |
| `__DATA_DIRTY.__data` | `0x698` | `0x718` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x4772` | `0x47e2` | **`+0x70`** |
| `__AUTH.__data` | `0x58` | `—` | **`-0x58`** |
| `__AUTH_CONST.__objc_const` | `0x6d80` | `0x6db0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4400` | `0x4428` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3040` | `0x3060` | **`+0x20`** |
| `__DATA.__bss` | `0x1800` | `0x17e0` | **`-0x20`** |
| `__DATA.__data` | `0x1110` | `0x10f0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x4f5a` | `0x4f7a` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x758` | `0x740` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2950` | `0x2968` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x6e0` | `0x6cc` | **`-0x14`** |
| `__DATA_DIRTY.__bss` | `0xa10` | `0xa20` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdb8` | `0xdb0` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0xbc8` | `0xbc2` | **`-0x6`** |
| `__DATA.__objc_ivar` | `0x29c` | `0x2a0` | **`+0x4`** |

### Other Changes

```diff

-392.0.0.0.0
+394.0.0.0.0

-  Functions: 2899
-  Symbols:   3043
-  CStrings:  889
+  Functions: 2904
+  Symbols:   3044
+  CStrings:  891
Symbols:
+ +[DOCAXIdentifier newFolderWithSelectionAction]
+ -[DOCManagedPermission _dataOwnerStateForBundleIdentifier:withHostIdentifier:hostDataOwnerState:]
+ -[DOCManagedPermission canHostWithIdentifier:dataOwnerState:performAction:fileProviderDomain:]
+ GCC_except_table52
+ _OBJC_IVAR_$_DOCManagedPermission._hostAccountDataOwnerStateLock
+ ___block_descriptor_56_e8_32s40s_e26_B16?0"FPProviderDomain"8ls32l8s40l8
+ _isNilOrEmpty
- GCC_except_table34
- GCC_except_table47
- ___block_descriptor_48_e8_32s40s_e26_B16?0"FPProviderDomain"8ls32l8s40l8
- _get_type_metadata l15Synchronization5MutexVySbG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Could not resolve real location for CoreSpotlight-backed Local Storage item %{private}@; managed state may be inaccurate"
+ "newFolderWithSelectionAction"
```

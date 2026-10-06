## DocumentManagerCore

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e428` | `0x6ebb8` | **`+0x790`** |
| `__AUTH_CONST.__objc_const` | `0x6c68` | `0x6d80` | **`+0x118`** |
| `__AUTH.__objc_data` | `0x458` | `0x558` | **`+0x100`** |
| `__TEXT.__cstring` | `0x4e9a` | `0x4f5a` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x790` | `0x6e0` | **`-0xb0`** |
| `__AUTH_CONST.__const` | `0x17f8` | `0x1778` | **`-0x80`** |
| `__TEXT.__objc_methlist` | `0x43a8` | `0x4400` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x55c` | `0x5b0` | **`+0x54`** |
| `__AUTH_CONST.__cfstring` | `0x3000` | `0x3040` | **`+0x40`** |
| `__DATA.__data` | `0x10d8` | `0x1110` | **`+0x38`** |
| `__AUTH.__data` | `0x28` | `0x58` | **`+0x30`** |
| `__TEXT.__const` | `0x1770` | `0x17a0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x244` | `0x264` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xba8` | `0xbc8` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xa0` | **`-0x14`** |
| `__DATA_CONST.__const` | `0x1950` | `0x1960` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x6a8` | `0x698` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x4762` | `0x4772` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1de0` | `0x1df0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x290` | `0x29c` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x328` | `0x334` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xdb0` | `0xdb8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x750` | `0x758` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x198` | `0x1a0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2948` | `0x2950` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xf70` | `0xf68` | **`-0x8`** |

### Other Changes

```diff

-389.2.0.0.0
+392.0.0.0.0

-  Functions: 2873
-  Symbols:   3030
-  CStrings:  884
+  Functions: 2899
+  Symbols:   3043
+  CStrings:  889
Symbols:
+ +[DOCAXIdentifier renameSidebarButtonIdentifier]
+ _DOCIsRunningTests
+ _DOCIsRunningUITests
+ _NSDebugDescriptionErrorKey
+ _OBJC_CLASS_$__TtC19DocumentManagerCore25DOCContentUnavailableNode
+ _OBJC_IVAR_$_DOCManagedPermission._hostIdentifierLock
+ _OBJC_IVAR_$_DOCManagedPermission._personaLock
+ _OBJC_IVAR_$_DOCManagedPermission._sharedConnectionLock
+ _OBJC_METACLASS_$__TtC19DocumentManagerCore25DOCContentUnavailableNode
+ __DATA__TtC19DocumentManagerCore25DOCContentUnavailableNode
+ __INSTANCE_METHODS__TtC19DocumentManagerCore25DOCContentUnavailableNode
+ __IVARS__TtC19DocumentManagerCore25DOCContentUnavailableNode
+ __METACLASS_DATA__TtC19DocumentManagerCore25DOCContentUnavailableNode
+ __PROPERTIES__TtC19DocumentManagerCore25DOCContentUnavailableNode
+ _objc_retain_x10
+ _symbolic SS_ypt
+ _symbolic _____ 19DocumentManagerCore25DOCContentUnavailableNodeC
+ _symbolic _____Sg 19DocumentManagerCore11DOCRootNodeC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 19DocumentManagerCore25DOCContentUnavailableNodeC
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
- GCC_except_table1
- GCC_except_table57
- GCC_except_table60
- GCC_except_table61
- ___swift_memcpy4_4
- _symbolic _____ So16os_unfair_lock_sV
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
CStrings:
+ "Content unavailable: rootNode was nil for domain '"
+ "Could not create rootNode because storageURLs.first is nil for providerDomain '%{public}@'"
+ "Creating DOCRootNode from FPFS domain '%{public}@' first storageURL: '%s'"
+ "DOCIsBeingUITested"
+ "Did not find FINode for FPv2 domain '%{public}@'"
+ "DocumentManagerCore.DOCContentUnavailableNode"
+ "Found FINode for FPv2 domain '%{public}@'"
+ "Retrying because we did not find FINode for FPv2 domain '%{public}@': %ld"
+ "SignificantChange"
+ "rename-sidebar-button"
- "Could not create rootNode because storageURLs.first is nil for providerDomain '%s'"
- "Creating DOCRootNode from FPFS domain '%s' first storageURL: '%s'"
- "Did not find FINode for FPv2 domain '%s'"
- "Found FINode for FPv2 domain '%s'"
- "Retrying because we did not find FINode for FPv2 domain '%s': %ld"
```

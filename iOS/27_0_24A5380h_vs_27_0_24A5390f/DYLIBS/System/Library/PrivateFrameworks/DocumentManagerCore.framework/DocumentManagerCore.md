## DocumentManagerCore

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f144` | `0x7153c` | **`+0x23f8`** |
| `__AUTH_CONST.__objc_intobj` | `0x18` | `0xd8` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x47e2` | `0x4872` | **`+0x90`** |
| `__TEXT.__cstring` | `0x4f7a` | `0x4fda` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2968` | `0x29b8` | **`+0x50`** |
| `__TEXT.__const` | `0x17a0` | `0x17f0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x4428` | `0x4478` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1df0` | `0x1e38` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x3060` | `0x30a0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xdb0` | `0xde8` | **`+0x38`** |
| `__DATA.__data` | `0x10f0` | `0x1118` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0xf68` | `0xf40` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x1778` | `0x1798` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x6db0` | `0x6dc8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xbc2` | `0xbd6` | **`+0x14`** |
| `__DATA.__bss` | `0x17e0` | `0x17f0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x718` | `0x728` | **`+0x10`** |

### Other Changes

```diff

-394.0.0.0.0
+396.0.0.0.0

-  Functions: 2904
-  Symbols:   3044
-  CStrings:  891
+  Functions: 2926
+  Symbols:   3052
+  CStrings:  897
Symbols:
+ -[FINode(DOCNode) actionsForPermissions:]
+ -[FINode(DOCNode) doc_eligibleActionsFor:]
+ -[FINode(DOCNode) permissionsForActions:]
+ -[FPItem(DOCNode) doc_eligibleActionsFor:]
+ -[FPItem(DOCNode) shouldUseDSEnumeration]
+ GCC_except_table199
+ GCC_except_table204
+ GCC_except_table78
+ _FPActionPin
+ ___41-[FPItem(DOCNode) shouldUseDSEnumeration]_block_invoke
+ ___42-[FINode(DOCNode) doc_eligibleActionsFor:]_block_invoke
+ _getuid
+ _shouldUseDSEnumeration.onceToken
+ _shouldUseDSEnumeration.sProviderIDToDSEnumerationState
+ _swift_dynamicCastObjCClassUnconditional
+ _symbolic _____ySiG s16PartialRangeFromV
+ _symbolic _____ySiG s16PartialRangeUpToV
- GCC_except_table193
- GCC_except_table198
- GCC_except_table77
- _FPActionDownloadNoContextMenu
- _FPActionDownloadRecursivelyNoContextMenu
- _FPActionFetchPublishingURL
- _FPActionIgnore
- _FPActionUnignore
- _FPActionUnpin
CStrings:
+ "%{public}s: failed to get FINode for item: %{public}@\n\t error: %{public}@"
+ "%{public}s: failed to get cached domain from item: %{public}@\n\t error: %{public}@"
+ "-[FPItem(DOCNode) doc_eligibleActionsFor:]"
+ "-[FPItem(DOCNode) shouldUseDSEnumeration]"
+ ".Trash"
+ ".Trashes"
+ "I"
+ "Received Permissions bits that were not requested.\n\t node: %{public}@\n\t Requested: %u\n\t Received: %u\n\t Not Requested: %u"
- "Unknown/Unexpected action: %{public}@. Falling back to FPItem: %{public}@"
- "Unsupported action: %{public}@. Falling back to FPItem: %{public}@"
```

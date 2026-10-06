## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172194` | `0x171ea8` | **`-0x2ec`** |
| `__TEXT.__cstring` | `0x18c90` | `0x18cd0` | **`+0x40`** |
| `__TEXT.__const` | `0x6598` | `0x6568` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x24528` | `0x24500` | **`-0x28`** |
| `__TEXT.__eh_frame` | `0x5a08` | `0x5a30` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x6bf8` | `0x6c18` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x67a8` | `0x6790` | **`-0x18`** |
| `__DATA.__bss` | `0x81b0` | `0x81c0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8538` | `0x8530` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x121a4` | `0x1219c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xfb4` | `0xfb0` | **`-0x4`** |
| `__TEXT.__gcc_except_tab` | `0x1240` | `0x123c` | **`-0x4`** |

### Other Changes

```diff

-821.0.13.1.2
+821.0.16.0.0

-  Functions: 11205
+  Functions: 11198

-  CStrings:  4164
+  CStrings:  4165
Symbols:
+ GCC_except_table32
+ _GKSavedGameDocumentCoordinationQueue
+ _GKSavedGameDocumentCoordinationQueue.onceToken
+ _GKSavedGameDocumentCoordinationQueue.sQueue
+ ___GKSavedGameDocumentCoordinationQueue_block_invoke
+ ___swift_get_extra_inhabitant_index.17Tm
+ ___swift_store_extra_inhabitant_index.18Tm
- -[GKPlayerCredentialController gameBundleId]
- -[GKPlayerCredentialController setGameBundleId:]
- GCC_except_table35
- GCC_except_table39
- _OBJC_IVAR_$_GKPlayerCredentialController._gameBundleId
- ___swift_get_extra_inhabitant_index.8Tm
- ___swift_store_extra_inhabitant_index.9Tm
CStrings:
+ "com.apple.GameKit.GKSavedGameDocument.coordination"
```

## DocumentManagerCore

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83dc8` | `0x84020` | **`+0x258`** |
| `__TEXT.__eh_frame` | `0x2520` | `0x24c8` | **`-0x58`** |
| `__TEXT.__oslogstring` | `0x4b82` | `0x4bb2` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1a58` | `0x1a80` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1c50` | `0x1c70` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2ac8` | `0x2ae8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xd32` | `0xd14` | **`-0x1e`** |
| `__DATA.__bss` | `0x17f0` | `0x1800` | **`+0x10`** |
| `__DATA.__data` | `0xa28` | `0xa18` | **`-0x10`** |
| `__TEXT.__const` | `0x19f8` | `0x19e8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x45f0` | `0x4600` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x770` | `0x778` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xf4` | `0xf0` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x13c` | `0x138` | **`-0x4`** |

### Other Changes

```diff

-403.1.8.0.0
+403.1.10.0.0

-  Symbols:   3135
+  Symbols:   3140
Symbols:
+ -[FPItem(DOCNode) doc_shouldRedirectEligibleActionsToDSFor:]
+ -[NSURL(DOCNoFollow) doc_hasNoFollow]
+ GCC_except_table214
+ GCC_except_table219
+ GCC_except_table82
+ _DOCNodeErrorDomain_block_invoke.contestedActions
+ _DOCNodeErrorDomain_block_invoke.onceToken
+ _OBJC_CLASS_$_FILocalAppContainerCollection
+ ___60-[FPItem(DOCNode) doc_shouldRedirectEligibleActionsToDSFor:]_block_invoke
+ ___60-[FPItem(DOCNode) doc_shouldRedirectEligibleActionsToDSFor:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e5_B8?0ls32l8s40l8
+ ___swift_closure_destructor.145Tm
+ ___swift_closure_destructor.193Tm
+ ___swift_closure_destructor.293Tm
+ ___swift_closure_destructor.74Tm
+ ___swift_closure_destructor.80Tm
+ _fcntl
+ _symbolic ______pShy_____GAC______pIeghHggozo_ So7DOCNodeP So8FPActiona s5ErrorP
- -[FPItem(DOCNode) doc_shouldRedirectEligibleActionsToDS]
- GCC_except_table212
- GCC_except_table217
- GCC_except_table80
- ___swift_closure_destructor.147Tm
- ___swift_closure_destructor.195Tm
- ___swift_closure_destructor.295Tm
- ___swift_closure_destructor.76Tm
- ___swift_closure_destructor.82Tm
- _swift_retain_x24
- _symbolic SayShy_____GSgG So8FPActiona
- _symbolic Shy_____GSg So8FPActiona
- _symbolic ______pShy_____GSgAC______pIeghHggozo_ So7DOCNodeP So8FPActiona s5ErrorP
CStrings:
+ "[NoFollow] Resolving canonical path failed for %@ realpath: %{errno}d F_GETPATH: %{errno}d"
- "[NoFollow] realpath failed for %@: %{errno}d"
```

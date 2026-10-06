## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Transparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x230` | `0xe58` | **`+0xc28`** |
| `__DATA.__data` | `0x10d0` | `0x9f0` | **`-0x6e0`** |
| `__AUTH.__data` | `0x5e8` | `0x98` | **`-0x550`** |
| `__AUTH.__objc_data` | `0x2d8` | `—` | **`-0x2d8`** |
| `__DATA_DIRTY.__objc_data` | `0x1af8` | `0x1dd0` | **`+0x2d8`** |
| `__TEXT.__text` | `0x81f00` | `0x82154` | **`+0x254`** |
| `__TEXT.__oslogstring` | `0x204b` | `0x20db` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x8020` | `0x8050` | **`+0x30`** |
| `__TEXT.__cstring` | `0x30dc` | `0x310c` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4aa0` | `0x4ad0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x3a80` | `0x3aa0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3ff8` | `0x4018` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2038` | `0x2058` | **`+0x20`** |
| `__TEXT.__const` | `0x4ec0` | `0x4ed0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2d18` | `0x2d28` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3b0` | `0x3b4` | **`+0x4`** |

### Other Changes

```diff

-1766.40.47.0.0
+1766.40.50.0.0

-  Functions: 3887
-  Symbols:   3579
-  CStrings:  783
+  Functions: 3893
+  Symbols:   3585
+  CStrings:  785
Symbols:
+ -[KTQueryOptions queryReason]
+ -[KTQueryOptions setQueryReason:]
+ -[KTVerifierResult showsTreeResetWarning]
+ -[KTVerifierResult updateTreeResetInProgress:]
+ -[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:isFailureIgnoredForDate:]
+ GCC_except_table160
+ GCC_except_table188
+ GCC_except_table221
+ _OBJC_IVAR_$_KTQueryOptions._queryReason
+ ___46-[KTVerifierResult updateTreeResetInProgress:]_block_invoke
+ ___87-[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:isFailureIgnoredForDate:]_block_invoke
- -[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:]
- GCC_except_table158
- GCC_except_table186
- GCC_except_table219
- ___63-[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:]_block_invoke
CStrings:
+ "<KTQueryOptions: flags: %08x timeout: %f reason: %ld>"
+ "queryReason"
+ "updateTreeResetInProgress: %{mask.hash}@ was computed with treeReset=%{BOOL}d, no tree reset is in progress now, uiStatus %{public}@ is stale"
- "<KTQueryOptions: flags: %08x>"
```

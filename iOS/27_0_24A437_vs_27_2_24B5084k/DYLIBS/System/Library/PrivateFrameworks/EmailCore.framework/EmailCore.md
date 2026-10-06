## EmailCore

> `/System/Library/PrivateFrameworks/EmailCore.framework/EmailCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5bab8` | `0x5be50` | **`+0x398`** |
| `__TEXT.__gcc_except_tab` | `0x71e8` | `0x728c` | **`+0xa4`** |
| `__TEXT.__oslogstring` | `0xc7f` | `0xcc5` | **`+0x46`** |
| `__TEXT.__objc_methlist` | `0x50b8` | `0x50e8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2a80` | `0x2aa8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a50` | `0x2a60` | **`+0x10`** |

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 2043
-  Symbols:   4165
-  CStrings:  1533
+  Functions: 2048
+  Symbols:   4170
+  CStrings:  1534
Symbols:
+ +[ECDKIMServerStatement(Testing) serverStatementWithBuilderBlock:]
+ +[ECMessageAuthenticationResult(Testing) authenticationResultWithBuilderBlock:]
+ __OBJC_$_CLASS_METHODS_ECDKIMServerStatement(Testing)
+ __OBJC_$_CLASS_METHODS_ECMessageAuthenticationResult(Testing)
+ ___60-[ECTransferActionReplayer _downLoadSourceMessagesInAction:]_block_invoke_2
CStrings:
+ "<%{public}@>. Download skipped for item missing remote ID: %{public}@"
```

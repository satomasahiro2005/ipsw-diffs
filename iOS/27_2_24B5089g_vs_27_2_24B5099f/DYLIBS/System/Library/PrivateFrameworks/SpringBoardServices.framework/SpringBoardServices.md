## SpringBoardServices

> `/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7cb78` | `0x7ccf8` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x4b4a` | `0x4ba5` | **`+0x5b`** |
| `__TEXT.__objc_methlist` | `0x8e70` | `0x8ea0` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x279d8` | `0x279e8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x35b8` | `0x35c8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2a60` | `0x2a68` | **`+0x8`** |

### Other Changes

```diff

-4637.1.8.101.0
+4637.1.12.101.0

-  Functions: 4361
-  Symbols:   8058
-  CStrings:  2139
+  Functions: 4364
+  Symbols:   8060
+  CStrings:  2140
Symbols:
+ -[SBSHomeScreenService replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:options:]
+ -[SBSHomeScreenService swapApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
CStrings:
+ "SBSHomeScreenService: failed swapApplicationIconsWithBundleIdentifier request (no target)."
```

## SpringBoardServices

> `/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ccf8` | `0x7cebc` | **`+0x1c4`** |
| `__TEXT.__cstring` | `0xdff9` | `0xe051` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x4ba5` | `0x4bed` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0xaf20` | `0xaf60` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x35c8` | `0x35d8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x8ea0` | `0x8eb0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x279e8` | `0x279f0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a68` | `0x2a70` | **`+0x8`** |

### Other Changes

```diff

-4637.1.12.101.0
+4637.1.14.103.0

-  Functions: 4364
-  Symbols:   8060
-  CStrings:  2140
+  Functions: 4367
+  Symbols:   8062
+  CStrings:  2143
Symbols:
+ -[SBSHomeScreenService simulateCampoEnablementChange]
+ -[SBSHomeScreenService stashHomeScreenLayoutWithName:error:]
+ _SBSHomeScreenServiceNoConnectionError
- -[SBSHomeScreenService stashHomeScreenLayoutWithName:]
CStrings:
+ "SBSHomeScreenService: failed simulateCampoEnablementChange (no target)."
+ "SBSHomeScreenServiceErrorDomain"
+ "Unable to connect to SpringBoard's Home Screen service."
```

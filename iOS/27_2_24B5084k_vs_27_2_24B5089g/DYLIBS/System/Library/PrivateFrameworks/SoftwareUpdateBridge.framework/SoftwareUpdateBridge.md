## SoftwareUpdateBridge

> `/System/Library/PrivateFrameworks/SoftwareUpdateBridge.framework/SoftwareUpdateBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82a4` | `0x832c` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x1260` | `0x1280` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1485` | `0x149a` | **`+0x15`** |
| `__DATA.__bss` | `0x48` | `0x58` | **`+0x10`** |

### Other Changes

```diff

-393.40.5.0.0
+393.40.6.0.0

-  Functions: 219
-  Symbols:   586
-  CStrings:  298
+  Functions: 222
+  Symbols:   590
+  CStrings:  299
Symbols:
+ _SUShouldSkipTermsRequirement
+ _SUShouldSkipTermsRequirement.onceToken
+ _SUShouldSkipTermsRequirement.result
+ ___SUShouldSkipTermsRequirement_block_invoke
CStrings:
+ "SkipTermsRequirement"
```

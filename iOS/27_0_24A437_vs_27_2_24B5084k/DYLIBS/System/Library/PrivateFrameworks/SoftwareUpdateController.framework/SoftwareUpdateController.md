## SoftwareUpdateController

> `/System/Library/PrivateFrameworks/SoftwareUpdateController.framework/SoftwareUpdateController`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf508` | `0xf530` | **`+0x28`** |
| `__TEXT.__cstring` | `0x3b96` | `0x3bad` | **`+0x17`** |
| `__TEXT.__const` | `0xb0` | `0xc0` | **`+0x10`** |
| `__DATA.__data` | `0x348` | `0x350` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xf30` | `0xf38` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x158c` | `0x1594` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-196.0.1.0.0
+201.40.1.0.0

-  Functions: 425
-  Symbols:   943
-  CStrings:  462
+  Functions: 426
+  Symbols:   945
+  CStrings:  463
Symbols:
+ -[SUControllerManager installUpdate:rediscoverNetwork:]
+ _SUControllerMessageManagerRediscoverNetworkKey
Functions:
~ -[SUControllerManager installUpdate:] : 192 -> 8
+ -[SUControllerManager installUpdate:rediscoverNetwork:]
CStrings:
+ "RaveBSeed"
+ "RediscoverNetwork"
- "Rave"
```

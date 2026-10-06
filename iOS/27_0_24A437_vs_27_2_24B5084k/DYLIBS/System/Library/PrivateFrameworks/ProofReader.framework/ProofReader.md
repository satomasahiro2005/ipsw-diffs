## ProofReader

> `/System/Library/PrivateFrameworks/ProofReader.framework/ProofReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbdf10` | `0xbe74c` | **`+0x83c`** |
| `__AUTH_CONST.__auth_got` | `0x788` | `0x818` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x288` | `0x2b8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x96f4` | `0x9712` | **`+0x1e`** |
| `__DATA_CONST.__const` | `0xa328` | `0xa318` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x14c8` | `0x14d8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c88` | `0x1c90` | **`+0x8`** |

### Other Changes

```diff

-696.0.0.0.0
+697.0.0.0.0

-  - /System/Library/PrivateFrameworks/Sage.framework/Sage
+  - /System/Library/PrivateFrameworks/TextComposer.framework/TextComposer

-  - /usr/lib/swift/libswiftCoreLocation.dylib

-  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 1809
-  Symbols:   3095
-  CStrings:  4768
+  Functions: 1811
+  Symbols:   3093
+  CStrings:  4769
Symbols:
+ _swift_release_x23
+ _swift_release_x24
+ _symbolic _____ 12TextComposer11RewriteTypeV
+ _symbolic _____ 12TextComposer14DocumentFormatV
+ _symbolic _____Sg 12TextComposer11RewriteTypeV
+ _symbolic _____Sg 12TextComposer14DocumentFormatV
- __swift_FORCE_LOAD_$_swiftCoreLocation
- __swift_FORCE_LOAD_$_swiftCoreLocation_$_ProofReader
- __swift_FORCE_LOAD_$_swiftIntents
- __swift_FORCE_LOAD_$_swiftIntents_$_ProofReader
- _symbolic _____ 4Sage21TextCompositionClientC13RewritingTypeO
- _symbolic _____ 4Sage21TextCompositionClientC14TCDocumentTypeO
- _symbolic _____Sg 4Sage21TextCompositionClientC13RewritingTypeO
- _symbolic _____Sg 4Sage21TextCompositionClientC14TCDocumentTypeO
CStrings:
+ "OpenEndedExtended"
```

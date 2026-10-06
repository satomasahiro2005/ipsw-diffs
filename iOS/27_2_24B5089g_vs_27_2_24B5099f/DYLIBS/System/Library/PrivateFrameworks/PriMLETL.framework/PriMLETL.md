## PriMLETL

> `/System/Library/PrivateFrameworks/PriMLETL.framework/PriMLETL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9740` | `0xb9d04` | **`+0x5c4`** |
| `__TEXT.__eh_frame` | `0x61d0` | `0x6210` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1da7` | `0x1de7` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x1b83` | `0x1bbf` | **`+0x3c`** |
| `__AUTH_CONST.__const` | `0x4d60` | `0x4d88` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1558` | `0x1548` | **`-0x10`** |
| `__TEXT.__const` | `0x8f58` | `0x8f68` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2770` | `0x2780` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1fc` | `0x208` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x408` | `0x40c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x19c` | `0x1a0` | **`+0x4`** |

### Other Changes

```diff

-46.0.0.0.0
+47.0.0.0.0

-  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

+  - /System/Library/Frameworks/WebKit.framework/WebKit

-  - /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation

-  Functions: 2996
-  Symbols:   1066
-  CStrings:  311
+  Functions: 3000
+  Symbols:   1064
+  CStrings:  312
Symbols:
+ ___swift_project_boxed_opaque_existential_0Tm
+ _associated conformance So38NSAttributedStringDocumentAttributeKeyaSHSCSQ
+ _associated conformance So38NSAttributedStringDocumentAttributeKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So38NSAttributedStringDocumentAttributeKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _symbolic ScCySo18NSAttributedStringC_SDy_____ypGt______pG So38NSAttributedStringDocumentAttributeKeya s5ErrorP
+ _symbolic So18NSAttributedStringC_SDy_____ypGt So38NSAttributedStringDocumentAttributeKeya
+ _symbolic _____ So38NSAttributedStringDocumentAttributeKeya
- _NSCharacterEncodingDocumentOption
- _NSDocumentTypeDocumentOption
- _NSHTMLTextDocumentType
- _associated conformance So30NSAttributedStringDocumentTypeaSHSCSQ
- _associated conformance So30NSAttributedStringDocumentTypeas20_SwiftNewtypeWrapperSCSY
- _associated conformance So30NSAttributedStringDocumentTypeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _symbolic _____ So30NSAttributedStringDocumentTypea
- _symbolic ______ypt So42NSAttributedStringDocumentReadingOptionKeya
- _symbolic _____y______yptG s23_ContiguousArrayStorageC So42NSAttributedStringDocumentReadingOptionKeya
CStrings:
+ "WebKit HTML conversion failed; returning the input unchanged."
```

## SpeakThisServices

> `/System/Library/PrivateFrameworks/SpeakThisServices.framework/SpeakThisServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1414` | `0x1608` | **`+0x1f4`** |
| `__TEXT.__cstring` | `0x378` | `0x3f8` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x400` | `0x440` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x198` | `0x1c8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x68` | `0x78` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x34c` | `0x354` | **`+0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 44
-  Symbols:   154
-  CStrings:  43
+  Functions: 46
+  Symbols:   161
+  CStrings:  46
Symbols:
+ -[SpeakThisServices speechControllerPresentation:completionHandler:]
+ _NSLocalizedDescriptionKey
+ _STSMessageReplyKeyPresentation
+ ___68-[SpeakThisServices speechControllerPresentation:completionHandler:]_block_invoke
+ ___NSDictionary0__struct
+ ___block_descriptor_48_e8_32bs40bs_e22_v16?0"NSDictionary"8ls32l8s40l8
+ _objc_retain
CStrings:
+ "STSMessageReplyKeyPresentation"
+ "Speech Controller presentation reply did not contain a presentation value"
+ "v16@?0@\"NSDictionary\"8"
```

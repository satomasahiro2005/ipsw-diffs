## IntentsUI

> `/System/Library/Frameworks/IntentsUI.framework/IntentsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xb60` | `0xc20` | **`+0xc0`** |
| `__TEXT.__text` | `0xf934` | `0xf9d8` | **`+0xa4`** |
| `__TEXT.__cstring` | `0x167c` | `0x16cc` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x3b0` | `0x3c8` | **`+0x18`** |

### Other Changes

```diff

-4016.0.51.1.102
+4016.1.8.0.0

-  Symbols:   1106
-  CStrings:  195
+  Symbols:   1109
+  CStrings:  201
Symbols:
+ _UTTypeBMP
+ _UTTypeICO
+ _UTTypeWebP
Functions:
~ ____INUIImageSourceCreationOptions_block_invoke : 380 -> 544
CStrings:
+ "public.avci"
+ "public.avcs"
+ "public.avif"
+ "public.avis"
+ "public.jpeg-2000"
+ "public.jpeg-xl"
```

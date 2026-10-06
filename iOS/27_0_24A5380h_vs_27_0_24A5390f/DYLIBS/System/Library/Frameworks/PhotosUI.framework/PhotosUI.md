## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/PhotosUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41874` | `0x42370` | **`+0xafc`** |
| `__DATA.__bss` | `0x30a0` | `0x3220` | **`+0x180`** |
| `__TEXT.__const` | `0x2e68` | `0x2f78` | **`+0x110`** |
| `__AUTH_CONST.__const` | `0x20f0` | `0x2180` | **`+0x90`** |
| `__TEXT.__cstring` | `0x4b7b` | `0x4bcb` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x18e8` | `0x1928` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xba4` | `0xbd8` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0xaf1` | `0xb21` | **`+0x30`** |
| `__DATA.__data` | `0x1ac8` | `0x1ae8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xb92` | `0xbb2` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xd04` | `0xd20` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0xa00` | `0xa18` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5f8` | `0x610` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x330` | `0x348` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x194` | `0x1a0` | **`+0xc`** |
| `__TEXT.__swift5_capture` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x114` | `0x118` | **`+0x4`** |

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

-  Functions: 2928
-  Symbols:   2901
-  CStrings:  551
+  Functions: 2953
+  Symbols:   2909
+  CStrings:  552
Symbols:
+ _NSLocalizedDescriptionKey
+ _OUTLINED_FUNCTION_90
+ _PHLocalIdentifiersErrorKey
+ _PHPhotosErrorDomain
+ _associated conformance 8PhotosUI8PVSErrorO18SanitizedErrorCodeOSHAASQ
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 8PhotosUI8PVSErrorO18SanitizedErrorCodeO
+ _symbolic _____ySSypG s17_NativeDictionaryV
CStrings:
+ "The target shared album is currently migrating. Operation not allowed."
```

## CookingKit

> `/System/Library/PrivateFrameworks/CookingKit.framework/CookingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x367d34` | `0x36ad1c` | **`+0x2fe8`** |
| `__DATA.__bss` | `0x3c308` | `0x3c688` | **`+0x380`** |
| `__AUTH_CONST.__const` | `0x16478` | `0x16758` | **`+0x2e0`** |
| `__TEXT.__const` | `0x3a914` | `0x3abe4` | **`+0x2d0`** |
| `__TEXT.__swift5_typeref` | `0x2d5de` | `0x2d8ae` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0x7252` | `0x7402` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x64c0` | `0x65f0` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0xbcac` | `0xbd94` | **`+0xe8`** |
| `__TEXT.__unwind_info` | `0xbb78` | `0xbc30` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x95af` | `0x965f` | **`+0xb0`** |
| `__AUTH.__data` | `0x8690` | `0x8730` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0xc5d4` | `0xc66c` | **`+0x98`** |
| `__DATA.__data` | `0xd5c8` | `0xd638` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x3598` | `0x35e0` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xb80` | `0xbc0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1068` | `0x10a0` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x1c88` | `0x1cb8` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x2160` | `0x217c` | **`+0x1c`** |
| `__AUTH.__objc_data` | `0xb10` | `0xb28` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x3eb0` | `0x3ec8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x2648` | `0x2660` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xf2c` | `0xf3c` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x358` | **`+0x8`** |

### Other Changes

```diff

-5934.2.0.0.0
+5934.3.0.0.0

-  Functions: 18034
-  Symbols:   509
-  CStrings:  608
+  Functions: 18107
+  Symbols:   511
+  CStrings:  617
Symbols:
+ _CGRectIntersectsRect
+ _OBJC_CLASS_$_OS_os_log
CStrings:
+ "Attempting to begin appearance from invalid state, %@, state=%@, transition=%@"
+ "Attempting to end appearance state for view controller that is already transitioned, %@, state=%@"
+ "Attempting to end appearance state for view controller that is not tracked, %@"
+ "Transition manager, begin, %@, state=%@, animated=%d"
+ "Transition manager, end, %@, state=%@"
+ "appeared"
+ "appearing"
+ "disappeared"
+ "disappearing"
```

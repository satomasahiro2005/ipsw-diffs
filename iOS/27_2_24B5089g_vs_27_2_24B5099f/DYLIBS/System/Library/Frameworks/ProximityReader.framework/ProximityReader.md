## ProximityReader

> `/System/Library/Frameworks/ProximityReader.framework/ProximityReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xca9a4` | `0xcb030` | **`+0x68c`** |
| `__AUTH_CONST.__const` | `0x5db0` | `0x5e28` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b0` | `0x6e0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3868` | `0x3890` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x1e20` | `0x1e40` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xd64` | `0xd84` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x17d0` | `0x17e8` | **`+0x18`** |
| `__DATA.__bss` | `0xa270` | `0xa280` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x2a56` | `0x2a66` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2fc4` | `0x2fd4` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2b74` | `0x2b80` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x27ce` | `0x27d8` | **`+0xa`** |
| `__AUTH.__objc_data` | `0x5f8` | `0x600` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x9e0` | `0x9e8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x630` | `0x638` | **`+0x8`** |

### Other Changes

```diff

-151.2.0.0.0
+151.5.0.0.0

-  Functions: 4209
-  Symbols:   1260
-  CStrings:  560
+  Functions: 4222
+  Symbols:   1265
+  CStrings:  561
Symbols:
+ _OBJC_CLASS_$_UIHingeInteraction
+ ___swift_closure_destructor.101Tm
+ ___swift_closure_destructor.163Tm
+ ___swift_closure_destructor.86Tm
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic _____SgXw 15ProximityReader30DiscoveryArticleViewControllerC
- ___swift_closure_destructor.154Tm
- ___swift_closure_destructor.77Tm
- ___swift_closure_destructor.92Tm
CStrings:
+ "DiscoveryArticleViewController: landscape"
+ "DiscoveryArticleViewController: portrait"
+ "presentRotatedView - allowing all orientations"
- "DiscoveryArticleViewController: rotated to landscape"
- "DiscoveryArticleViewController: rotated to portrait"
```

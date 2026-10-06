## PodcastsUI

> `/System/Library/PrivateFrameworks/PodcastsUI.framework/PodcastsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13e774` | `0x13d670` | **`-0x1104`** |
| `__DATA.__bss` | `0x6de0` | `0x6a60` | **`-0x380`** |
| `__TEXT.__const` | `0xaa30` | `0xa838` | **`-0x1f8`** |
| `__AUTH_CONST.__const` | `0x86f0` | `0x8500` | **`-0x1f0`** |
| `__TEXT.__swift5_fieldmd` | `0x2ba4` | `0x2a4c` | **`-0x158`** |
| `__TEXT.__oslogstring` | `0x36ed` | `0x35cd` | **`-0x120`** |
| `__DATA_DIRTY.__bss` | `0x4b90` | `0x4c90` | **`+0x100`** |
| `__DATA.__data` | `0x2240` | `0x21d0` | **`-0x70`** |
| `__TEXT.__constg_swiftt` | `0x3140` | `0x30fc` | **`-0x44`** |
| `__TEXT.__swift5_reflstr` | `0x236b` | `0x2336` | **`-0x35`** |
| `__AUTH_CONST.__objc_const` | `0x7e08` | `0x7dd8` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x740` | `0x710` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x668c` | `0x665e` | **`-0x2e`** |
| `__DATA_DIRTY.__data` | `0x4880` | `0x48a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x46c9` | `0x46a9` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x490c` | `0x48f4` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x5f0` | `0x5d8` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x1e0` | `0x1cc` | **`-0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x41d0` | `0x41c0` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1594` | `0x1584` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x3628` | `0x3630` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1fd0` | `0x1fd8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x380` | `0x378` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x53c8` | `0x53d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3d0` | `0x3cc` | **`-0x4`** |

### Other Changes

```diff

-4027.100.70.0.0
+4027.100.75.0.0

-  Functions: 7164
-  Symbols:   4997
-  CStrings:  857
+  Functions: 7156
+  Symbols:   4987
+  CStrings:  852
Symbols:
+ ___swift_exist.box.addr_destructorTm
+ _associated conformance 10PodcastsUI17NowPlayingArtworkO4DataOSHAASQ
- -[IMPlayerItem secureKeyLoader]
- -[IMPlayerItem setSecureKeyLoader:]
- _OBJC_IVAR_$_IMPlayerItem._secureKeyLoader
- ___swift_exist.box.addr_destructor.53Tm
- ___swift_memcpy248_8
- _associated conformance So21UIContentSizeCategoryaSHSCSQ
- _associated conformance So21UIContentSizeCategoryas20_SwiftNewtypeWrapperSCSY
- _associated conformance So21UIContentSizeCategoryas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _symbolic _____ 10PodcastsUI39iOSNowPlayingEpisodeUpsellConfiguration33_7356E91B5F9CFCB46676D7EB93CF2B44LLV
- _symbolic _____ So21UIContentSizeCategorya
- _symbolic _____Sg So21UIContentSizeCategorya
- _type_layout_string 10PodcastsUI39iOSNowPlayingEpisodeUpsellConfiguration33_7356E91B5F9CFCB46676D7EB93CF2B44LLV
CStrings:
+ "\xf0\xf01"
- "%s Fetching artwork for placement: %{public}s."
- "%s Finished fetching chapter artwork for placement: %s."
- "%s Found artwork data for placement: %{public}s for item %{private,mask.hash}s."
- "%s Unable to find any artwork data for placement: %{public}s for item %{private,mask.hash}s."
- "[NowPlayingArtworkProvider]:"
- "\xf0\xf0A"
```

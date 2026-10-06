## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0xed0` | `0xee0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x83f0` | `0x83f8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x233d8` | `0x233d4` | **`-0x4`** |
| `__TEXT.__text` | `0x10bf5c` | `0x10bf60` | **`+0x4`** |

### Other Changes

```diff

-311.0.0.0.0
+313.0.0.0.0
Functions:
~ -[LPLinkMetadata _isCurrentlyLoadingOrIncomplete] : 100 -> 128
~ -[LPCollaborationFooterView initWithHost:properties:style:allowsSeparator:] : 3228 -> 3104
~ -[LPiTunesMediaMetadataProviderSpecialization cancel] : 56 -> 108
~ -[LPiTunesMediaMetadataProviderSpecialization fail] : 108 -> 128
~ -[LPiTunesMediaMetadataProviderSpecialization done] : 160 -> 188
```

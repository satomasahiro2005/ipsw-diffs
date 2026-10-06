## PhotosIntelligence

> `/System/Library/PrivateFrameworks/PhotosIntelligence.framework/PhotosIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63a7f4` | `0x6417fc` | **`+0x7008`** |
| `__AUTH_CONST.__const` | `0x4dae8` | `0x4e238` | **`+0x750`** |
| `__TEXT.__oslogstring` | `0x25705` | `0x25a85` | **`+0x380`** |
| `__TEXT.__swift5_capture` | `0xd510` | `0xd748` | **`+0x238`** |
| `__TEXT.__eh_frame` | `0x36eec` | `0x370dc` | **`+0x1f0`** |
| `__TEXT.__const` | `0x3bd88` | `0x3bef8` | **`+0x170`** |
| `__DATA.__bss` | `0x3eac0` | `0x3ebc0` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x180e8` | `0x181c0` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x24dd9` | `0x24e9f` | **`+0xc6`** |
| `__DATA.__data` | `0x89c0` | `0x8a40` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0xe300` | `0xe370` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x4928` | `0x4990` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x11168` | `0x111b8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0xd644` | `0xd67c` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x1f60` | `0x1f90` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x11033` | `0x11063` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4ea0` | `0x4ec0` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x2074` | `0x2090` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x31b8` | `0x31d0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x12700` | `0x12710` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x5b04` | `0x5b14` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xd74` | `0xd80` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x2d7c` | `0x2d84` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x12b8` | `0x12c0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xac8` | `0xad0` | **`+0x8`** |

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

-  Functions: 41647
-  Symbols:   9840
-  CStrings:  6105
+  Functions: 41742
+  Symbols:   9858
+  CStrings:  6125
Symbols:
+ +[PNUserDefaults useLEOForAmbientSuggestions]
+ GCC_except_table1046
+ GCC_except_table1048
+ GCC_except_table1085
+ GCC_except_table1087
+ GCC_except_table1145
+ GCC_except_table1150
+ GCC_except_table1152
+ GCC_except_table1155
+ GCC_except_table1163
+ GCC_except_table1165
+ GCC_except_table1243
+ GCC_except_table1259
+ GCC_except_table1262
+ GCC_except_table166
+ GCC_except_table274
+ GCC_except_table281
+ GCC_except_table307
+ GCC_except_table385
+ GCC_except_table391
+ GCC_except_table549
+ GCC_except_table558
+ GCC_except_table572
+ GCC_except_table735
+ GCC_except_table844
+ GCC_except_table932
+ GCC_except_table944
+ _OBJC_CLASS_$_PHAssetImageMediaMetadata
+ _PHFetchTypeCollection
+ ___swift_closure_destructor.82Tm
+ _associated conformance 18PhotosIntelligence21AmbientAssetSuggesterV0E8CategoryOSHAASQ
+ _get_enum_tag_for_layout_string 18PhotosIntelligence21AmbientAssetSuggesterV0E8CategoryO
+ _kCGImagePropertyOrientation
+ _kCGImagePropertyTIFFDictionary
+ _kCGImagePropertyTIFFOrientation
+ _symbolic SDy_____ypG So11CFStringRefa
+ _symbolic SDy_____ypGSg So11CFStringRefa
+ _symbolic SS15localIdentifier_t
+ _symbolic ScCy___________pG 10Foundation4DataV s5ErrorP
+ _symbolic _____ 18PhotosIntelligence21AmbientAssetSuggesterV
+ _symbolic _____ 18PhotosIntelligence21AmbientAssetSuggesterV0E8CategoryO
+ _symbolic _____y_____ypG s17_NativeDictionaryV So11CFStringRefa
+ _symbolic _____z_Xx 10Foundation4DataV
+ _type_layout_string 18PhotosIntelligence21AmbientAssetSuggesterV0E8CategoryO
- GCC_except_table1045
- GCC_except_table1047
- GCC_except_table1084
- GCC_except_table1086
- GCC_except_table1144
- GCC_except_table1149
- GCC_except_table1151
- GCC_except_table1154
- GCC_except_table1162
- GCC_except_table1164
- GCC_except_table1242
- GCC_except_table1258
- GCC_except_table1261
- GCC_except_table165
- GCC_except_table273
- GCC_except_table280
- GCC_except_table306
- GCC_except_table383
- GCC_except_table390
- GCC_except_table548
- GCC_except_table557
- GCC_except_table571
- GCC_except_table734
- GCC_except_table840
- GCC_except_table931
- GCC_except_table943
CStrings:
+ "%s: Before processing: %ld, after: %ld (dedupe=%{bool}d)"
+ "%s: Limited assets to top %ld. Now total %ld"
+ "AlchemistService returned a malformed scene (resolution %u×%u, %u layers, %ld triangles, %ld vertices); rejecting before persist."
+ "Could not build exclusive operand for person %s"
+ "Curation lexeme fetch failed: %@"
+ "Failed to fetch PHPerson for local identifier: %s"
+ "Failed to read media-metadata resource for asset %s: %@"
+ "No lexemes matched required curation properties 0x%s"
+ "No original media-metadata resource for asset %s"
+ "PNUseLEOForAmbientSuggestions"
+ "Person %s (%s): no assets matched curation properties"
+ "Person %s (%s): query failed: %@"
+ "Scene curation properties "
+ "Scene curation properties %lu: no matching assets"
+ "Scene query failed for curation properties %lu: %@"
+ "Unsupported detection type %hd for person %s"
+ "leoAmbientCityscape"
+ "leoAmbientLandscape"
+ "leoAmbientPersonOrPet-"
+ "photos://featuredPhoto?identifier=%@&uuid=%@&source=widget"
+ "requestResourceData(for:)"
- "photos://featuredPhoto?identifier=%@&source=widget"
```

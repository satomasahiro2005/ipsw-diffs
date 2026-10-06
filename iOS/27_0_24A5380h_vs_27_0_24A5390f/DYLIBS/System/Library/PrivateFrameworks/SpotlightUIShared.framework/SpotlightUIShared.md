## SpotlightUIShared

> `/System/Library/PrivateFrameworks/SpotlightUIShared.framework/SpotlightUIShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdf4e0` | `0xe1424` | **`+0x1f44`** |
| `__TEXT.__oslogstring` | `0x11c2` | `0x1372` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x39e0` | `0x3af8` | **`+0x118`** |
| `__DATA.__bss` | `0xe670` | `0xe730` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x6d01` | `0x6d91` | **`+0x90`** |
| `__TEXT.__const` | `0xa1cc` | `0xa25c` | **`+0x90`** |
| `__TEXT.__cstring` | `0x3328` | `0x33b8` | **`+0x90`** |
| `__DATA.__data` | `0x1c58` | `0x1ce0` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0xe98` | `0xf00` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x1530` | `0x1580` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1570` | `0x15c0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x41b8` | `0x4200` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x3400` | `0x3446` | **`+0x46`** |
| `__DATA_CONST.__got` | `0xfc8` | `0x1000` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x630` | `0x658` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x8dd4` | `0x8dfc` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1cf8` | `0x1d18` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x6e0` | `0x700` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xb08` | `0xb20` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2188` | `0x2194` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x1f8` | `0x200` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x7b0` | `0x7b4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x5a4` | `0x5a8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x508` | `0x50c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-236.0.4.100.0
+236.0.11.100.0

+  - /System/Library/PrivateFrameworks/CoreParsec.framework/CoreParsec

-  Functions: 5152
-  Symbols:   2226
-  CStrings:  415
+  Functions: 5181
+  Symbols:   2259
+  CStrings:  427
Symbols:
+ +[SUISCardLoader sharedSpotlightCardLoader]
+ +[SUISCardLoader spotlightPARSession]
+ -[SUISCardLoader canLoadCard:]
+ -[SUISCardLoader loadCard:completionHandler:]
+ _OBJC_CLASS_$_PARSession
+ _OBJC_CLASS_$_PARSessionConfiguration
+ _OBJC_CLASS_$_SFCollectionCardSection
+ _OBJC_CLASS_$_SUISCardLoader
+ _OBJC_METACLASS_$_SUISCardLoader
+ __OBJC_$_CLASS_METHODS_SUISCardLoader
+ __OBJC_$_INSTANCE_METHODS_SUISCardLoader
+ __OBJC_$_PROP_LIST_SUISCardLoader
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SFCardResourceLoader
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SFCardResourceLoader
+ __OBJC_$_PROTOCOL_REFS_SFCardResourceLoader
+ __OBJC_CLASS_PROTOCOLS_$_SUISCardLoader
+ __OBJC_CLASS_RO_$_SUISCardLoader
+ __OBJC_LABEL_PROTOCOL_$_SFCardResourceLoader
+ __OBJC_METACLASS_RO_$_SUISCardLoader
+ __OBJC_PROTOCOL_$_SFCardResourceLoader
+ ___37+[SUISCardLoader spotlightPARSession]_block_invoke
+ ___43+[SUISCardLoader sharedSpotlightCardLoader]_block_invoke
+ ___45-[SUISCardLoader loadCard:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e28_v24?0"SFCard"8"NSError"16ls32l8
+ ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
+ _associated conformance 17SpotlightUIShared11LogCategoryOs12CaseIterableAA8AllCasessADP_Sl
+ _sharedSpotlightCardLoader.onceToken
+ _sharedSpotlightCardLoader.shared
+ _spotlightPARSession.gSession
+ _spotlightPARSession.onceToken
+ _symbolic Say_____G 17SpotlightUIShared11LogCategoryO
+ _symbolic ___________t 17SpotlightUIShared11LogCategoryO 2os6LoggerV
+ _symbolic _____y__________G s18_DictionaryStorageC 17SpotlightUIShared11LogCategoryO 2os6LoggerV
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC 17SpotlightUIShared11LogCategoryO 2os6LoggerV
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSArray"8ls32l8s40l8
CStrings:
+ "            cardSections("
+ "        results("
+ "Duplicate values for key: '"
+ "Swift/NativeDictionary.swift"
+ "collecting expired pasteboard item for deletion hash:%@ title:%{sensitive}@"
+ "deleting continuity pasteboard items domain:%{public}@"
+ "deleting expired pasteboard items (%lu) hashes:%@"
+ "deleting pasteboard domains (%lu): %@"
+ "error: %@ indexing pasteboard item hash:%@"
+ "finished deleting continuity pasteboard items"
+ "finished deleting expired pasteboard items by hash"
+ "finished deleting pasteboard domains"
+ "finished indexing pasteboard item hash:%@"
+ "fte"
+ "got attributes: %lu for hash:%@ title:%{sensitive}@"
+ "indexing pasteboard item hash:%@ domain:%@ title:%{sensitive}@"
+ "slow-fetching attributes for re-copied pasteboard item hash:%@"
+ "spotlight/1.0"
+ "v24@?0@\"SFCard\"8@\"NSError\"16"
- "        results: [\n"
- "Deleting expired domains (%lu)"
- "Deleting expired items (%lu)"
- "error: %@ indexing pasteboard item :%@"
- "finished indexing pasteboard contents"
- "got attributes: %lu"
- "indexing pasteboard contents"
```

## findmylocated

> `/usr/libexec/findmylocated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a2ca4` | `0x5ad6a4` | **`+0xaa00`** |
| `__TEXT.__eh_frame` | `0x49770` | `0x4a270` | **`+0xb00`** |
| `__TEXT.__unwind_info` | `0x15dd8` | `0x16478` | **`+0x6a0`** |
| `__DATA.__data` | `0xf080` | `0xf380` | **`+0x300`** |
| `__DATA_CONST.__const` | `0x18588` | `0x18878` | **`+0x2f0`** |
| `__TEXT.__const` | `0x20648` | `0x20938` | **`+0x2f0`** |
| `__TEXT.__objc_methname` | `0x4f25` | `0x51f5` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x194ac` | `0x1974c` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0xbb12` | `0xbd92` | **`+0x280`** |
| `__DATA.__objc_const` | `0x6398` | `0x65a0` | **`+0x208`** |
| `__TEXT.__objc_methtype` | `0x11e8` | `0x13a8` | **`+0x1c0`** |
| `__DATA.__bss` | `0x2d900` | `0x2da80` | **`+0x180`** |
| `__TEXT.__swift5_capture` | `0x4e5c` | `0x4fdc` | **`+0x180`** |
| `__TEXT.__objc_stubs` | `0x2000` | `0x2100` | **`+0x100`** |
| `__TEXT.__swift_as_cont` | `0x4508` | `0x45d0` | **`+0xc8`** |
| `__DATA.__objc_data` | `0x1430` | `0x14f0` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x717c` | `0x7234` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0xf4c` | `0x1004` | **`+0xb8`** |
| `__TEXT.__objc_classname` | `0x12a6` | `0x1336` | **`+0x90`** |
| `__TEXT.__swift_as_ret` | `0x290c` | `0x299c` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0xd60` | `0xde8` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x71fe` | `0x727c` | **`+0x7e`** |
| `__TEXT.__swift5_reflstr` | `0x7e7d` | `0x7eed` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x90ac` | `0x9114` | **`+0x68`** |
| `__TEXT.__auth_stubs` | `0x5d30` | `0x5d90` | **`+0x60`** |
| `__TEXT.__swift_as_entry` | `0x1720` | `0x1778` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x2ea0` | `0x2ed0` | **`+0x30`** |
| `__DATA.__common` | `0x13d8` | `0x13f0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1da8` | `0x1dc0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x250` | `0x260` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x150` | `0x160` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1784` | `0x1790` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x1888` | `0x1890` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x7f8` | `0x800` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-141.31.6.16.17
+141.31.6.16.21

-  Functions: 17653
-  Symbols:   2830
-  CStrings:  3873
+  Functions: 17812
+  Symbols:   2839
+  CStrings:  3931
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s12FindMyLocate19LocalizationUtilityO09effectiveD0SSvgZ
+ _$sSS14_fromSubstringySSSshFZ
+ _$sSS5countSivg
+ _$sSS5index_8offsetBy07limitedC0SS5IndexVSgAE_SiAEtF
+ _OBJC_CLASS_$_CSSearchQuery
+ _OBJC_CLASS_$_CSSearchQueryContext
+ _OBJC_CLASS_$_CSSearchableItem
+ _swift_release_x3
- _$sSL2leoiySbx_xtFZTj
CStrings:
+ "%{public}s: %{public}ld of %{public}ld person entities missing, repairing"
+ "%{public}s: CoreSpotlight requested a full person entity reindex"
+ "%{public}s: CoreSpotlight requested reindex of %{public}ld person entit(y/ies)"
+ "%{public}s: Failed to persist contact signatures: %{public}s"
+ "%{public}s: No Find My contact changed; skipping re-donation"
+ "%{public}s: No LocalStorageService; skipping"
+ "%{public}s: all %{public}ld person entities present"
+ "%{public}s: failed to query CoreSpotlight"
+ "@\"NSData\"48@0:8@\"CSSearchableIndex\"16@\"NSString\"24@\"NSString\"32o^@40"
+ "@\"NSURL\"52@0:8@\"CSSearchableIndex\"16@\"NSString\"24@\"NSString\"32B40o^@44"
+ "@48@0:8@16@24@32o^@40"
+ "@52@0:8@16@24@32B40o^@44"
+ "CSSearchableIndexDelegate"
+ "Contacts changed; scheduling PersonEntity re-donation"
+ "EntityDonationService"
+ "EntityDonationService startup"
+ "Failed to handle contact change: %{public}s"
+ "FieldMatch(_kMDItemAppEntityTypeIdentifier, \"PersonEntity\")"
+ "_TtC13findmylocated21EntityDonationService"
+ "_TtC13findmylocated33PersonEntityDonationIndexDelegate"
+ "__ABDataBaseChangedByOtherProcessNotification"
+ "_kMDItemAppEntityInstanceIdentifier"
+ "_kMDItemAppEntityTypeIdentifier"
+ "appEntityInstanceId"
+ "attributeSet"
+ "dataForSearchableIndex:itemIdentifier:typeIdentifier:error:"
+ "dataManager"
+ "debounceTask"
+ "donatedContactSignatures"
+ "donatedPersonEntityLanguage"
+ "fileURLForSearchableIndex:itemIdentifier:typeIdentifier:inPlace:error:"
+ "findmylocated.PersonEntityDonationIndexDelegate"
+ "handleFullReindexRequestFromIndexDelegate()"
+ "handleTargetedReindexRequestFromIndexDelegate(identifiers:)"
+ "hasDonationPending"
+ "indexedPersonEntityIdentifiers()"
+ "initWithQueryString:queryContext:"
+ "personEntityIndexDelegate"
+ "reconcilePersonEntityDonations()"
+ "redonatePersonEntitiesIfContactsChanged()"
+ "searchableIndex:reindexAllSearchableItemsWithAcknowledgementHandler:"
+ "searchableIndex:reindexSearchableItemsWithIdentifiers:acknowledgementHandler:"
+ "searchableIndexDidFinishThrottle:"
+ "searchableIndexDidThrottle:"
+ "searchableItemsDidUpdate:"
+ "searchableItemsForIdentifiers:protectionClass:searchableItemsHandler:"
+ "searchableItemsForIdentifiers:searchableItemsHandler:"
+ "setBundleIDs:"
+ "setCompletionHandler:"
+ "setFetchAttributes:"
+ "setFoundItemsHandler:"
+ "setIndexDelegate:"
+ "v24@0:8@\"CSSearchableIndex\"16"
+ "v24@0:8@\"NSArray\"16"
+ "v32@0:8@\"CSSearchableIndex\"16@?<v@?>24"
+ "v32@0:8@\"NSArray\"16@?<v@?@\"NSArray\">24"
+ "v40@0:8@\"CSSearchableIndex\"16@\"NSArray\"24@?<v@?>32"
+ "v40@0:8@\"NSArray\"16@\"NSString\"24@?<v@?@\"NSArray\">32"
```

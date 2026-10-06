## searchpartyd

> `/usr/libexec/searchpartyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19aba84` | `0x19b9f2c` | **`+0xe4a8`** |
| `__TEXT.__eh_frame` | `0xfe8d4` | `0xff734` | **`+0xe60`** |
| `__TEXT.__objc_methname` | `0x1a748` | `0x1aa48` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x5167e` | `0x5193e` | **`+0x2c0`** |
| `__TEXT.__unwind_info` | `0x4ca70` | `0x4c820` | **`-0x250`** |
| `__TEXT.__const` | `0x9ad88` | `0x9afc8` | **`+0x240`** |
| `__DATA.__data` | `0x456a0` | `0x458d0` | **`+0x230`** |
| `__DATA_CONST.__const` | `0x74010` | `0x74210` | **`+0x200`** |
| `__TEXT.__objc_methtype` | `0x5bce` | `0x5d3e` | **`+0x170`** |
| `__TEXT.__cstring` | `0x338cc` | `0x33a2c` | **`+0x160`** |
| `__DATA.__objc_const` | `0x1f660` | `0x1f7b0` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x8500` | `0x8620` | **`+0x120`** |
| `__TEXT.__swift_as_cont` | `0xe6e0` | `0xe7dc` | **`+0xfc`** |
| `__TEXT.__swift5_capture` | `0x1aee4` | `0x1afc4` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x2375c` | `0x23828` | **`+0xcc`** |
| `__DATA.__objc_data` | `0x46d8` | `0x47a0` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x271c1` | `0x27281` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x4a34` | `0x4aec` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x25baf` | `0x25c53` | **`+0xa4`** |
| `__TEXT.__swift5_fieldmd` | `0x28404` | `0x2849c` | **`+0x98`** |
| `__DATA.__objc_selrefs` | `0x38c0` | `0x3948` | **`+0x88`** |
| `__DATA.__bss` | `0xb3a00` | `0xb3a80` | **`+0x80`** |
| `__TEXT.__swift_as_ret` | `0x8288` | `0x8308` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0x4df0` | `0x4e50` | **`+0x60`** |
| `__TEXT.__swift_as_entry` | `0x3e24` | `0x3e54` | **`+0x30`** |
| `__DATA.__common` | `0x3510` | `0x3528` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3da8` | `0x3db8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x3a8` | `0x3b8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x9f00` | `0x9f10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x4f88` | `0x4f90` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x4da8` | `0x4db0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x9f0` | `0x9f8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2134` | `0x213c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x5e14` | `0x5e18` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-449.31.6.16.19
+449.31.6.16.25

-  Functions: 69095
-  Symbols:   5118
-  CStrings:  14395
+  Functions: 69263
+  Symbols:   5123
+  CStrings:  14445
Symbols:
+ _$s10AppIntents12IntentPersonV4NameO07displayE0yAESScAEmFWC
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s10Foundation4UUIDV10FindMyBaseE16deprecated_bytesSays5UInt8VGvg
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
+ _OBJC_CLASS_$_CSSearchQuery
+ _OBJC_CLASS_$_CSSearchQueryContext
+ _OBJC_CLASS_$_CSSearchableItem
- _$s10Foundation4UUIDV10FindMyBaseE5bytesSays5UInt8VGvg
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _swift_conformsToProtocol2
CStrings:
+ "%{public}s: %{public}@"
+ "%{public}s: %{public}ld of %{public}ld item entities missing, repairing"
+ "%{public}s: CoreSpotlight requested a full item entity reindex"
+ "%{public}s: CoreSpotlight requested reindex of %{public}ld item entit(y/ies)"
+ "%{public}s: all %{public}ld item entities present"
+ "%{public}s: failed to build expected entities: %{public}@"
+ "%{public}s: failed to get BeaconStore"
+ "%{public}s: failed to query CoreSpotlight"
+ "@\"NSData\"48@0:8@\"CSSearchableIndex\"16@\"NSString\"24@\"NSString\"32o^@40"
+ "@\"NSURL\"52@0:8@\"CSSearchableIndex\"16@\"NSString\"24@\"NSString\"32B40o^@44"
+ "@48@0:8@16@24@32o^@40"
+ "@52@0:8@16@24@32B40o^@44"
+ "CSSearchableIndexDelegate"
+ "Disconnected from %{private,mask.hash}s, error: %{public}@"
+ "Disconnected from %{public}s, error: %{public}@"
+ "Dropped %ld aged-out buffered device(s), %ld remaining."
+ "Failed to read client code signing identity: %{public}@"
+ "Failed to unshare %@: %@"
+ "FieldMatch(_kMDItemAppEntityTypeIdentifier, \"ItemEntity\")"
+ "ItemEntityDonation: no owner name: %{public}@"
+ "Needs spotlight redonation. %s -> %s"
+ "_TtC12searchpartyd31ItemEntityDonationIndexDelegate"
+ "_kMDItemAppEntityInstanceIdentifier"
+ "_kMDItemAppEntityTypeIdentifier"
+ "appEntityInstanceId"
+ "attributeSet"
+ "dataForSearchableIndex:itemIdentifier:typeIdentifier:error:"
+ "fileURLForSearchableIndex:itemIdentifier:typeIdentifier:inPlace:error:"
+ "handleFullReindexRequestFromIndexDelegate()"
+ "handleTargetedReindexRequestFromIndexDelegate(identifiers:)"
+ "indexedItemEntityIdentifiers()"
+ "initWithQueryString:queryContext:"
+ "itemEntityIndexDelegate"
+ "reconcileItemEntityDonations()"
+ "searchableIndex:reindexAllSearchableItemsWithAcknowledgementHandler:"
+ "searchableIndex:reindexSearchableItemsWithIdentifiers:acknowledgementHandler:"
+ "searchableIndexDidFinishThrottle:"
+ "searchableIndexDidThrottle:"
+ "searchableItemsDidUpdate:"
+ "searchableItemsForIdentifiers:protectionClass:searchableItemsHandler:"
+ "searchableItemsForIdentifiers:searchableItemsHandler:"
+ "searchpartyd.ItemEntityDonationIndexDelegate"
+ "sessionAnchorResolver"
+ "sessionStartedAt"
+ "setBundleIDs:"
+ "setCompletionHandler:"
+ "setFetchAttributes:"
+ "setFoundItemsHandler:"
+ "setIndexDelegate:"
+ "v24@0:8@\"CSSearchableIndex\"16"
+ "v32@0:8@\"CSSearchableIndex\"16@?<v@?>24"
+ "v40@0:8@\"CSSearchableIndex\"16@\"NSArray\"24@?<v@?>32"
+ "v40@0:8@\"NSArray\"16@\"NSString\"24@?<v@?@\"NSArray\">32"
- "%{public}s: incomplete sources, version left unstamped"
- "Disconnected from %{private,mask.hash}s"
- "Failed to encode declineShareBeacon message: %@"
```

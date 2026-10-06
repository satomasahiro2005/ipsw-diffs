## StocksWidget

> `/private/var/staged_system_apps/Stocks.app/PlugIns/StocksWidget.appex/StocksWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2218` | `0x2138` | **`-0xe0`** |
| `__TEXT.__eh_frame` | `0x4428` | `0x43b8` | **`-0x70`** |
| `__TEXT.__objc_methtype` | `0xf36` | `0xf84` | **`+0x4e`** |
| `__TEXT.__objc_methname` | `0x3846` | `0x387b` | **`+0x35`** |
| `__TEXT.__const` | `0x9a14` | `0x9a34` | **`+0x20`** |
| `__DATA.__objc_const` | `0x3990` | `0x39a8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3458` | `0x3440` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x4710` | `0x4720` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xfb4` | `0xfc4` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xb98` | `0xba0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2390` | `0x2398` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1310` | `0x1308` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x2ec` | `0x2e4` | **`-0x8`** |
| `__TEXT.__text` | `0xdb888` | `0xdb88c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2018.0.0.0.0
+2020.0.0.0.0

-  Functions: 4624
-  Symbols:   272
-  CStrings:  1001
+  Functions: 4622
+  Symbols:   274
+  CStrings:  1002
Symbols:
+ _swift_task_localValuePop
+ _swift_task_localValuePush
CStrings:
+ "@\"<FCNetworkBehaviorMonitor>\"16@0:8"
+ "@\"NSArray\"32@0:8@\"NSArray\"16@?<@\"FCFeedPersonalizedItemScoreProfile\"@?@\"<FCFeedPersonalizingItem>\">24"
+ "@32@0:8@16@?24"
+ "T@\"<FCNetworkBehaviorMonitor>\",R,N"
+ "limitItemsByMinimumItemQuality:scoreProvider:"
+ "networkBehaviorMonitor"
+ "scoreTagsIDs:"
+ "sortTagIDsDescending:"
- "@\"NSArray\"32@0:8@\"NSArray\"16@\"FCMapTable\"24"
- "@32@0:8@16@24"
- "Non user-visible string used for sizing the redaction box of the symbol accessory inline complication"
- "Non user-visible string used for sizing the redaction box of the symbol accessory rectangular complication"
- "limitItemsByMinimumItemQuality:scoreProfiles:"
- "rankTagIDsDescending:"
- "scoresForTagIDs:"
```

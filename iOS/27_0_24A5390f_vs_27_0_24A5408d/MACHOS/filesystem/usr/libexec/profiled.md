## profiled

> `/usr/libexec/profiled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc88d8` | `0xc8fac` | **`+0x6d4`** |
| `__TEXT.__objc_methname` | `0x16b43` | `0x16c13` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x133e0` | `0x13480` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xa8ba` | `0xa8ea` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x54b0` | `0x54d8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3020` | `0x3048` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x625c` | `0x6284` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x86e0` | `0x86c0` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x23f2` | `0x2412` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1200` | `0x1210` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1b60` | `0x1b70` | **`+0x10`** |
| `__DATA.__objc_const` | `0x70a8` | `0x70b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2120` | `0x2118` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-2483.0.5.0.0
+2483.2.6.0.0

-  Functions: 2735
-  Symbols:   1798
-  CStrings:  5758
+  Functions: 2741
+  Symbols:   1797
+  CStrings:  5764
Symbols:
- _MCFeatureDelayedSoftwareUpdatesForced
CStrings:
+ "-[MCProfileServiceServer areAppRatingsLockedDownOnlyByScreenTimeWithCompletion:]_block_invoke"
+ "ERROR_PROFILE_NONUNIQUE_IDENTIFIER_P_ID"
+ "Failed to apply restrictions. Error: %{public}s"
+ "_migrateValueRestrictions:withAppID:forKey:keysToRestrictions:currentValueUserSettings:"
+ "areAppRatingsLockedDownOnlyByScreenTime"
+ "areAppRatingsLockedDownOnlyByScreenTimeWithCompletion:"
+ "boolFeaturesWithPayloadRestictionKeyAlias"
+ "boolPayloadRestrictionKeysForFeature:"
+ "memberQueueCombinedProfileRestrictions"
+ "v24@0:8@?<v@?@\"NSNumber\"@\"NSError\">16"
- "ERROR_PROFILE_NONUNIQUE_UUID_P_ID"
- "Failed to apply restricitons. Error: %{public}s"
- "_migrateValueRestrictions:withAppID:forKey:keysToRestricitons:currentValueUserSettings:"
- "restriction_forceDelayedSoftwareUpdates"
```

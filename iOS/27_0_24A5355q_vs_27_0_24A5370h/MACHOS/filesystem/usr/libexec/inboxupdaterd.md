## inboxupdaterd

> `/usr/libexec/inboxupdaterd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82f08` | `0x85ec4` | **`+0x2fbc`** |
| `__TEXT.__oslogstring` | `0x9946` | `0xa07d` | **`+0x737`** |
| `__DATA_CONST.__const` | `0xe368` | `0xe7d8` | **`+0x470`** |
| `__TEXT.__objc_methname` | `0x801b` | `0x83d5` | **`+0x3ba`** |
| `__TEXT.__objc_stubs` | `0x7d20` | `0x8080` | **`+0x360`** |
| `__DATA_CONST.__cfstring` | `0x4500` | `0x46c0` | **`+0x1c0`** |
| `__DATA.__objc_const` | `0x8730` | `0x88c0` | **`+0x190`** |
| `__TEXT.__cstring` | `0x4d5a` | `0x4ee9` | **`+0x18f`** |
| `__TEXT.__objc_methlist` | `0x3b84` | `0x3cf4` | **`+0x170`** |
| `__DATA.__objc_selrefs` | `0x2408` | `0x24f8` | **`+0xf0`** |
| `__DATA_CONST.__objc_intobj` | `0x19c8` | `0x1aa0` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x1d38` | `0x1db8` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x14fc` | `0x156c` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x155a` | `0x15bb` | **`+0x61`** |
| `__DATA_CONST.__objc_arrayobj` | `0x5d0` | `0x600` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x14b0` | `0x14e0` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x4b8` | `0x4d8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xa68` | `0xa80` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x3c4` | `0x3d8` | **`+0x14`** |
| `__TEXT.__const` | `0xce03` | `0xce13` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-253.0.0.0.0
+266.0.0.0.0

-  Functions: 3950
-  Symbols:   481
-  CStrings:  3453
+  Functions: 4050
+  Symbols:   484
+  CStrings:  3538
Symbols:
+ _CFPreferencesSetValue
+ _NSStringFromRange
+ _OBJC_CLASS_$_MIBURaptorQFileManifest
+ _OBJC_CLASS_$_NSThread
+ _objc_retain_x28
- _NSCocoaErrorDomain
- _OBJC_CLASS_$_NSValue
CStrings:
+ "@\"NSURL\""
+ "@\"NSURL\"16@0:8"
+ "BTLTKTimeOffset"
+ "BTLTKTimeOffset %ld out of range for deviceIDs.count=%lu; ignoring"
+ "BTLTKTimeOffset=%ld: using deviceIDs[%ld] as LTK to force OBD-side encryption timeout + rotation (rdar://171415202 test hook)"
+ "Calculated counts: fileNumberCount=%lu (%lu bytes / %lu)"
+ "ExpirationDate"
+ "FI file range [%lu] out of bounds: location=%u length=%u count=%lu"
+ "Facotry install file [#%lu] with range: %{public}@"
+ "FailBTAuthThenReboot"
+ "Failed to construct file manifest."
+ "Failed to convert record ID data to base64 string"
+ "Failed to deserialize file numbers from command"
+ "Failed to serialize stripped personalization data: %{public}@"
+ "Failed to start multicast download, no RQ file numbers"
+ "Failed to strip sensitive personalization data: %{public}@"
+ "Failed to write stripped personalization data: %{public}@"
+ "Handling assetAudienceID: xpc call"
+ "Handling delete personalization..."
+ "Handling pallasServerURL: xpc call"
+ "Mismatch: %lu file numbers vs %lu basic params"
+ "No personalization data found, nothing to strip"
+ "No valid expiration date found in personalization data"
+ "No valid expiration date found, treating as not expired"
+ "Personalization data has expired (expiration date: %{public}@), stripping sensitive data"
+ "RQFileNumbers"
+ "RebootAfterBTAuth"
+ "RebootAfterBTDisconnect"
+ "SU file range [%lu] out of bounds: location=%u length=%u count=%lu"
+ "Sensitive key already absent, no stripping needed"
+ "Software update file [#%lu] with range: %{public}@"
+ "Successfully stripped sensitive data from personalization file"
+ "T@\"NSData\",&,N,V_rqFileNumbers"
+ "T@\"NSNumber\",&,N,V_personalized"
+ "T@\"NSString\",&,N,V_assetAudienceID"
+ "T@\"NSString\",R,N"
+ "T@\"NSURL\",&,N,V_pallasServerURL"
+ "T@\"NSURL\",R,N"
+ "TB,N,V_useInternalSUConfig"
+ "TEST: FailBTAuthThenReboot armed; rebooting WITHOUT sending auth response — repro CBDevice re-discovery via connection-manager retry (rdar://172071996)"
+ "TEST: FailBTAuthThenReboot — reboot did not fire in 30s, returning synthetic error"
+ "TEST: RebootAfterBTAuth armed; rebooting in 50ms (cleared CurrentOperation) — repro CBDevice re-discovery (rdar://172071996)"
+ "TEST: RebootAfterBTDisconnect armed; rebooting in 50ms (cleared CurrentOperation) — repro CBDevice re-discovery (rdar://172071996)"
+ "TEST: reboot did not fire"
+ "URLByDeletingLastPathComponent"
+ "URLWithString:"
+ "Updated SU configuration: PallasURL=%{public}@ AudienceID=%{public}@"
+ "Updating SU configuration for internal: %{bool}d"
+ "UseInternalSUConfig"
+ "_assetAudienceID"
+ "_consumeOneShotBoolForKey:"
+ "_handleDeletePersonalization:"
+ "_pallasServerURL"
+ "_personalizationInfoFileURL"
+ "_personalized"
+ "_rqFileNumbers"
+ "_useInternalSUConfig"
+ "assetAudienceID"
+ "assetAudienceIDWithReply:"
+ "base64EncodedStringWithOptions:"
+ "btLTKTimeOffset"
+ "cd060049-2465-43e3-bbb5-d769a66da2d7"
+ "checkAndStripExpiredPersonalizationData:"
+ "compare:"
+ "consumeFailBTAuthThenReboot"
+ "consumeRebootAfterBTAuth"
+ "consumeRebootAfterBTDisconnect"
+ "dateByAddingTimeInterval:"
+ "ffc25f86-b83c-4139-b8ad-91131d0e5429"
+ "https://gdmf-auth-stg.apple.com/v2/assets"
+ "https://gdmf-auth.apple.com/v2/assets"
+ "initWithFileNumbers:basicParameters:extendedParameters:"
+ "initWithStopThreshold:fileManifests:outputFiles:"
+ "isPersonalized"
+ "pallasServerURL"
+ "pallasServerURLWithReply:"
+ "personalization"
+ "personalized"
+ "resetSUConfiguration"
+ "rqFileNumbers"
+ "setAssetAudienceID:"
+ "setPallasServerURL:"
+ "setPersonalized:"
+ "setRqFileNumbers:"
+ "setUseInternalSUConfig:"
+ "sleepForTimeInterval:"
+ "subarrayWithRange:"
+ "updateSUConfigurationForInternal:"
+ "useInternalSUConfig"
+ "v24@0:8@?<v@?@\"NSString\"@\"NSError\">16"
+ "v24@0:8@?<v@?@\"NSURL\"@\"NSError\">16"
- "&"
- "Failed to convert record ID data to hex string"
- "Personalization already completed"
- "chicago"
- "initWithBasicParametersArray:extendedParametersArray:threshold:fileRanges:outputFiles:"
- "valueWithRange:"
```

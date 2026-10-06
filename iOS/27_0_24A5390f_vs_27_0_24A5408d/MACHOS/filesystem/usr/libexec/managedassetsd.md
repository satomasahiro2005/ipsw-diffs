## managedassetsd

> `/usr/libexec/managedassetsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4364` | `0xe7204` | **`+0x2ea0`** |
| `__TEXT.__oslogstring` | `0xb2bf` | `0xb64f` | **`+0x390`** |
| `__DATA_CONST.__const` | `0x2d78` | `0x30a0` | **`+0x328`** |
| `__TEXT.__objc_methname` | `0x6ece` | `0x707e` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x6170` | `0x6268` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x9de6` | `0x9ec6` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x5580` | `0x5660` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x914` | `0x9c6` | **`+0xb2`** |
| `__TEXT.__swift5_capture` | `0x648` | `0x6ec` | **`+0xa4`** |
| `__TEXT.__const` | `0x2198` | `0x2238` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x2010` | `0x20a0` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0xd3d` | `0xdad` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x28d8` | `0x2940` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x4d40` | `0x4da0` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1018` | `0x1060` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x814` | `0x85c` | **`+0x48`** |
| `__DATA.__data` | `0x1878` | `0x18b8` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1960` | `0x19a0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2464` | `0x249c` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xa80` | `0xab4` | **`+0x34`** |
| `__DATA_CONST.__auth_ptr` | `0x760` | `0x790` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xa3c` | `0xa6c` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x2199` | `0x21c9` | **`+0x30`** |
| `__DATA.__objc_const` | `0x60d0` | `0x60f8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xa58` | `0xa80` | **`+0x28`** |
| `__DATA.__bss` | `0x2720` | `0x2740` | **`+0x20`** |
| `__DATA.__objc_data` | `0x9b8` | `0x9d0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xc8` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x4b8` | `0x4cc` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x9c` | `0xa0` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x2e4` | `0x2e8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x2c8` | `0x2cc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-279.0.0.0.0
+279.0.2.0.0

-  Functions: 2731
-  Symbols:   933
-  CStrings:  3237
+  Functions: 2790
+  Symbols:   951
+  CStrings:  3267
Symbols:
+ _$s2os21OSAllocatedUnfairLockVMn
+ _$s8Dispatch0A3QoSV0B6SClassO7defaultyA2EmFWC
+ _$s8Dispatch0A3QoSV0B6SClassO7utilityyA2EmFWC
+ _$s8Dispatch0A3QoSV0B6SClassOMa
+ _$sScT6cancelyyF
+ _$sSo17OS_dispatch_groupC8DispatchE6notify3qos5flags5queue7executeyAC0D3QoSV_AC0D13WorkItemFlagsVSo0a1_b1_H0CyyXBtF
+ _$sSo17OS_dispatch_queueC8DispatchE5async5group3qos5flags7executeySo0a1_b1_F0CSg_AC0D3QoSVAC0D13WorkItemFlagsVyyXBtF
+ _$sSo17OS_dispatch_queueC8DispatchE6global3qosAbC0D3QoSV0G6SClassO_tFZ
+ _$ss13ManagedBufferCMn
+ _$ss5NeverOMn
+ _$ss5NeverON
+ _$ss5NeverOs5ErrorsWP
+ _$ss6UInt32VMn
+ _NSFileTypeDirectory
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_notify
CStrings:
+ "+[MAUtilityHelper registerAssetsWithSpaceAttributesWithPath:logger:completion:]"
+ "B44@0:8Q16B24@?28^@36"
+ "B8@?0"
+ "RegisterAssetsWithSpaceAttributes_v2"
+ "SAPathManager defaultManager is nil (SpaceAttribution soft-link failed despite @available passing); cannot register space attribution paths"
+ "SpaceAttribution framework unavailable: SAPathManager defaultManager returned nil"
+ "User Default for %{public}@: %u"
+ "ack expiration failed: %@"
+ "addObjectsFromArray:"
+ "bgTask acked expiration (Default)"
+ "bgTask completed normally"
+ "cancelCheckPurgedMark"
+ "collectSpaceAttributionPathsForRoot:exemptNames:fileMgr:logger:error:"
+ "failed to enumerate %@ for space attribution: %@"
+ "failed to enumerate %@ to compute v1 unregister set: %@"
+ "failed to unregister v1 SAF paths under MA bundle: %@"
+ "fileType"
+ "postInstall bgTask acked expiration (Default)"
+ "postInstall bgTask completed normally"
+ "postInstall checkPurgedMark failed: %@"
+ "ppe_environments"
+ "repeatingCheckPurgedMarkTask"
+ "setTaskExpiredWithRetryAfter:error:"
+ "setupWithStorage:syncManager:isCloudSyncManagerStarted:"
+ "skip bgTask checkPurgedMark: cloudSyncManagerStarted=%d expired=%d"
+ "skip bgTask cloud sync work: cloudSyncManagerStarted=%d"
+ "skip postInstall checkPurgedMark: cloudSyncManager not started, will request retry"
+ "skipping kRegisteredKey latch: registered 0 paths, will retry next launch"
+ "startCheckPurgedMark:completionHandler:"
+ "unregisterURLs:forBundleID:completionHandler:"
+ "unregistered %lu v1 SAF paths under MA bundle"
+ "uploadOldAssetsWithOption cancelled before quota check (task expired)"
+ "uploadOldAssetsWithOption cancelled mid-loop (task expired); deferring remaining assets to next run"
+ "uploadOldAssetsWithOption:includeKVStoreData:cancellationCheck:error:"
+ "v28@0:8B16@?20"
+ "v40@0:8@16@?24@?32"
- "User Default for RegisterAssetsWithSpaceAttributes: %u"
- "bgTask complete"
- "expirationHandler fires"
- "postInstall bgTask complete"
- "setupWithStorage:syncManager:"
- "task expiration, terminate bgTask."
```

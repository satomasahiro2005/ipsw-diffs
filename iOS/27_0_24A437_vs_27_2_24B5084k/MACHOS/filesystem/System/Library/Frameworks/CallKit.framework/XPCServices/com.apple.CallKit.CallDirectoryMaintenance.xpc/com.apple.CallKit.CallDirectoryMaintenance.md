## com.apple.CallKit.CallDirectoryMaintenance

> `/System/Library/Frameworks/CallKit.framework/XPCServices/com.apple.CallKit.CallDirectoryMaintenance.xpc/com.apple.CallKit.CallDirectoryMaintenance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21b04` | `0x24584` | **`+0x2a80`** |
| `__TEXT.__objc_methname` | `0x4041` | `0x43c9` | **`+0x388`** |
| `__TEXT.__objc_stubs` | `0x2920` | `0x2b60` | **`+0x240`** |
| `__TEXT.__eh_frame` | `0x560` | `0x790` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x2754` | `0x2934` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0xb50` | `0xc90` | **`+0x140`** |
| `__TEXT.__objc_methtype` | `0xf0b` | `0xfdb` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x770` | `0x818` | **`+0xa8`** |
| `__DATA.__objc_selrefs` | `0xd88` | `0xe10` | **`+0x88`** |
| `__DATA.__objc_const` | `0x2968` | `0x29e8` | **`+0x80`** |
| `__TEXT.__const` | `0x440` | `0x4b8` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x1744` | `0x17bc` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0xdc` | `0x140` | **`+0x64`** |
| `__DATA_CONST.__cfstring` | `0x340` | `0x3a0` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x2f4` | `0x348` | **`+0x54`** |
| `__TEXT.__auth_stubs` | `0x10b0` | `0x1100` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x868` | `0x890` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x200` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x2c` | `0x54` | **`+0x28`** |
| `__TEXT.__cstring` | `0x823` | `0x843` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x2e7` | `0x307` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x44` | **`+0x1c`** |
| `__DATA.__data` | `0x7a0` | `0x7b8` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x28` | `0x40` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x140` | `0x14c` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x90` | `0x98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-153.100.1.2.29
+156.200.70.2.2

-  Functions: 754
-  Symbols:   246
-  CStrings:  1008
+  Functions: 796
+  Symbols:   248
+  CStrings:  1048
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
+ _swift_getObjCClassFromMetadata
+ _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_release_x24
CStrings:
+ "@\"NSUserDefaults\""
+ "Already updating config, skipping duplicate update"
+ "Error synchronizing call directory extensions during maintenance: %@"
+ "ExtensionsConfig"
+ "LastLiveLookupRefreshOSBuild"
+ "Successfully synchronized call directory extensions"
+ "T@\"NSUserDefaults\",&,N,V_defaults"
+ "TB,N,V_isUpdatingLiveLookupConfig"
+ "Tq,N,R"
+ "T{os_unfair_lock_s=I},R,N,V_configUpdateLock"
+ "_configUpdateLock"
+ "_defaults"
+ "_isUpdatingLiveLookupConfig"
+ "boolForKey:"
+ "callDirectoryHost:requestedMigrationOfAllDataFromExtensionWithBundleID:toExtensionWithBundleID:withCompletionHandler:"
+ "callDirectoryHost:requestedToSynchronizeExtensionsIfPlistValidationChangedWithCompletionHandler:"
+ "configUpdateLock"
+ "defaults"
+ "initWithType:endpoint:issuer:bearerToken:featureId:privacyProxyFailOpen:useUserTierTokenKey:fetchConfigViaProxy:"
+ "instancesRespondToSelector:"
+ "integerForKey:"
+ "integerValue"
+ "isUpdatingLiveLookupConfig"
+ "liveCallerIDOptions"
+ "liveCallerIDOptionsRawValue"
+ "liveCallerIDPlistValidationDisabled"
+ "livecalleridProfileEnabled"
+ "livelookupExtensionsValidated"
+ "migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:error:"
+ "not all previous fetches completed within %lu second(s) continuing with cache only"
+ "plistValidationEnabled"
+ "reconfigure in flight, skipping live lookup"
+ "refreshAllExtensionsConfigGroupsWithCompletionHandler:"
+ "refreshExtensionConfigGroup failed: %@"
+ "refreshLiveLookupIfVersionUpdated:"
+ "requested to synchronize extensions if plist validation changed"
+ "requestedMigrationOfAllDataFromExtensionWithBundleID:%@ fromBundleID:%@"
+ "server bag options changed (%@ -> %ld), reconfiguring active extensions"
+ "setBool:forKey:"
+ "setDefaults:"
+ "setInteger:forKey:"
+ "setIsUpdatingLiveLookupConfig:"
+ "shouldUpdateLiveLookupForServerBagChange:currentConfig:"
+ "standardUserDefaults"
+ "v12@?0B8"
+ "v24@0:8@?<v@?B>16"
+ "v32@0:8@16q24"
+ "v48@0:8@\"CXCallDirectoryHost\"16@\"NSString\"24@\"NSString\"32@?<v@?B@\"NSError\">40"
+ "{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}"
+ "{os_unfair_lock_s=I}16@0:8"
- "identity = %@"
- "immediateKeyExpirationEnabled"
- "liveCallerIDImmediateKeyExpirationDisabled"
- "liveCallerIDReducedMaxShardCountDisabled"
- "liveCallerIDRequirePowerOfTwoShardCountDisabled"
- "not all previous fetches completed within %lu second(s) continuing"
- "reducedMaxShardCountEnabled"
- "requirePowerOfTwoShardCountEnabled"
- "robustNetworkManagerDisabled"
- "robustNetworkManagerEnabled"
```

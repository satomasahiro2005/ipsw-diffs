## memoryanalyticsd

> `/usr/libexec/memoryanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1954c` | `0x1bf10` | **`+0x29c4`** |
| `__DATA.__objc_const` | `0x17d8` | `0x2210` | **`+0xa38`** |
| `__TEXT.__objc_methname` | `0x2b69` | `0x3415` | **`+0x8ac`** |
| `__TEXT.__objc_stubs` | `0x29e0` | `0x3120` | **`+0x740`** |
| `__TEXT.__objc_methlist` | `0xc7c` | `0x10d4` | **`+0x458`** |
| `__TEXT.__oslogstring` | `0x3662` | `0x3976` | **`+0x314`** |
| `__TEXT.__cstring` | `0x348e` | `0x3731` | **`+0x2a3`** |
| `__DATA.__objc_selrefs` | `0xb48` | `0xdc8` | **`+0x280`** |
| `__DATA.__objc_data` | `0x500` | `0x730` | **`+0x230`** |
| `__TEXT.__objc_methtype` | `0x3e8` | `0x610` | **`+0x228`** |
| `__DATA_CONST.__cfstring` | `0x35e0` | `0x37c0` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0xad8` | `0xc78` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x588` | `0x6d8` | **`+0x150`** |
| `__DATA.__data` | `0x448` | `0x568` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x1f4` | `0x2e4` | **`+0xf0`** |
| `__TEXT.__objc_classname` | `0x135` | `0x213` | **`+0xde`** |
| `__TEXT.__auth_stubs` | `0xa70` | `0xb40` | **`+0xd0`** |
| `__DATA.__objc_ivar` | `0x134` | `0x1a0` | **`+0x6c`** |
| `__DATA_CONST.__auth_got` | `0x548` | `0x5b0` | **`+0x68`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0xb8` | **`+0x38`** |
| `__DATA_CONST.__objc_superrefs` | `0x70` | `0xa8` | **`+0x38`** |
| `__DATA.__bss` | `0x210` | `0x238` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__const` | `0x208` | `0x220` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x228` | `0x238` | **`+0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-103.0.0.0.0
+105.0.0.0.0

+  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

+  - /System/Library/PrivateFrameworks/Trial.framework/Trial

-  Functions: 538
-  Symbols:   246
-  CStrings:  1438
+  Functions: 632
+  Symbols:   261
+  CStrings:  1629
Symbols:
+ _MKBDeviceUnlockedSinceBoot
+ _OBJC_CLASS_$_RBSProcessMonitor
+ _OBJC_CLASS_$_TRIClient
+ _access
+ _dispatch_after
+ _dispatch_assert_queue_not$V2
+ _dispatch_time
+ _mlock
+ _notify_cancel
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_retain_x4
+ _unlink
CStrings:
+ "#16@0:8"
+ "/private/var/db/com.apple.memoryanalyticsd.model-loading-trial-enrolled"
+ "@\"<MTCameraActivityObserving>\""
+ "@\"<MTTrialFactorProviding>\""
+ "@\"MTCameraActivityState\""
+ "@\"MTModelLoadingTrialConfig\""
+ "@\"MTModelLoadingTrialConfigReader\""
+ "@\"MTStaticMemoryCost\""
+ "@\"NSNumber\"32@0:8@\"NSString\"16@\"NSString\"24"
+ "@\"NSObject<OS_os_transaction>\""
+ "@\"NSString\"16@0:8"
+ "@\"RBSProcessMonitor\""
+ "@\"TRIClient\""
+ "@24@0:8:16"
+ "@24@0:8Q16"
+ "@32@0:8:16@24"
+ "@32@0:8@16@24"
+ "@32@0:8d16@24"
+ "@40@0:8:16@24@32"
+ "@64@0:8@16@24@32@40@48@56"
+ "AAA"
+ "B24@0:8#16"
+ "B24@0:8:16"
+ "B24@0:8@\"NSString\"16"
+ "B24@0:8@\"Protocol\"16"
+ "Camera %{public}@"
+ "Could not observe %{public}s (status %u)"
+ "Could not read %{public}@ state (status %u)"
+ "Could not remove %{public}@: %{darwin.errno}d; launchd will keep relaunching a daemon with nothing to do"
+ "Could not write %{public}@: %{darwin.errno}d; the trial will not resume after a reboot"
+ "MEMORY_ANALYSIS_MODEL_LOADING"
+ "MTCameraActivityObserver"
+ "MTCameraActivityObserving"
+ "MTCameraActivityState"
+ "MTModelLoadingTrialConfig"
+ "MTModelLoadingTrialConfigReader"
+ "MTModelLoadingTrialEngine"
+ "MTStaticMemoryCost"
+ "MTTrialClient"
+ "MTTrialFactorProviding"
+ "Model loading trial active: static cost %lu MiB"
+ "Model loading trial configuration unchanged"
+ "Model loading trial disabled, tearing down"
+ "ModelLoadingTrial"
+ "ModelManager game assertion tier: %{public}@"
+ "NSObject"
+ "Received XPC Event via notifyd: notification name = %{public}@"
+ "StaticMemoryCostMiB"
+ "T#,R"
+ "T@\"NSString\",?,R,C"
+ "T@\"NSString\",R,C"
+ "T@?,C,N,V_activeStateChangedHandler"
+ "TB,R,N,GisCameraActive,V_cameraActive"
+ "TB,R,N,GisHoldingResidency"
+ "TB,R,N,GisReadable"
+ "TB,R,N,GisTrialReadable"
+ "TQ,R"
+ "TQ,R,N,V_staticCostMiB"
+ "Trial factor %{public}@ is not a long (case %d), using default"
+ "Trial factor %{public}@ out of range (%lld), clamping"
+ "Trial unreadable before first unlock, deferring"
+ "Vv16@0:8"
+ "XPC Event via notifyd carried no notification name"
+ "^{_NSZone=}16@0:8"
+ "_activeStateChangedHandler"
+ "_address"
+ "_appliedConfig"
+ "_cameraActive"
+ "_cameraObserver"
+ "_client"
+ "_configReader"
+ "_cooldown"
+ "_factorProvider"
+ "_firstUnlockToken"
+ "_foregroundPIDs"
+ "_gameAssertionNotificationName"
+ "_gameAssertionPolicy"
+ "_gameAssertionToken"
+ "_heldMiB"
+ "_keepAliveMarkerPath"
+ "_lockStatusToken"
+ "_processMonitor"
+ "_releaseGeneration"
+ "_residencyTransaction"
+ "_state"
+ "_staticCost"
+ "_staticCostMiB"
+ "active"
+ "activeStateChangedHandler"
+ "applyConfigurationOnQueue:"
+ "autorelease"
+ "cacheFactorLevelsWithNamespaceName:"
+ "cameraActive"
+ "class"
+ "client"
+ "com.apple.CameraHostedService"
+ "com.apple.camera"
+ "com.apple.camera.CameraMessagesApp"
+ "com.apple.camera.lockscreen"
+ "com.apple.memoryanalyticsd.model-loading-trial"
+ "com.apple.mobile.keybagd.first_unlock"
+ "com.apple.mobile.keybagd.lock_status"
+ "com.apple.system.console_mode_model_manager_assertion_changed"
+ "com.apple.trial.NamespaceUpdate.MEMORY_ANALYSIS_MODEL_LOADING"
+ "conformsToProtocol:"
+ "dealloc"
+ "factorLevelsWithNamespaceName:"
+ "gameAssertionDidChangeOnQueue"
+ "hasFactorLevelsWithNamespaceName:"
+ "hash"
+ "holdingResidency"
+ "inactive"
+ "initWithConfigReader:staticCost:gameAssertionNotificationName:cameraObserver:keepAliveMarkerPath:queue:"
+ "initWithCooldown:queue:"
+ "initWithFactorProvider:"
+ "initWithQueue:"
+ "initWithStaticCostMiB:"
+ "integerLevelForFactor:withNamespaceName:"
+ "isCameraActive"
+ "isHoldingResidency"
+ "isKindOfClass:"
+ "isMemberOfClass:"
+ "isProxy"
+ "isReadable"
+ "isTrialReadable"
+ "keepAliveMarkerExists"
+ "levelForFactor:withNamespaceName:"
+ "levelOneOfCase"
+ "longLongValue"
+ "longValue"
+ "mach_vm_allocate failed: %d"
+ "mach_vm_deallocate failed: %d"
+ "mlock failed: %{darwin.errno}d"
+ "monitorWithConfiguration:"
+ "none"
+ "noteProcess:foreground:forState:"
+ "numberWithLongLong:"
+ "performSelector:"
+ "performSelector:withObject:"
+ "performSelector:withObject:withObject:"
+ "predicateMatchingBundleIdentifiers:"
+ "readAndApplyOnQueue"
+ "readConfig"
+ "readGameAssertionOnQueue"
+ "readable"
+ "reapplyConfiguration"
+ "reevaluate"
+ "refresh"
+ "release"
+ "releaseHold"
+ "removeKeepAliveMarkerOnQueue"
+ "residentMiB"
+ "resizeToMiB:"
+ "respondsToSelector:"
+ "retain"
+ "retainCount"
+ "self"
+ "set"
+ "setActive:"
+ "setActiveStateChangedHandler:"
+ "setEvents:"
+ "setPredicates:"
+ "setProcess:foreground:"
+ "setStateDescriptor:"
+ "setUpdateHandler:"
+ "standard"
+ "startObservingCameraOnQueue"
+ "startObservingGameAssertionOnQueue"
+ "startProcessMonitor"
+ "startWithHandler:"
+ "state"
+ "states"
+ "staticCostMiB"
+ "stopObservingCameraOnQueue"
+ "stopObservingGameAssertionOnQueue"
+ "stopWaitingForTrialOnQueue"
+ "superclass"
+ "takeHoldOfMiB:"
+ "takeResidencyOnQueue"
+ "tearDownOnQueue"
+ "trialReadable"
+ "unrecognized"
+ "updateStaticCostOnQueue"
+ "v12@?0B8"
+ "v16@?0@\"<RBSProcessMonitorConfiguring>\"8"
+ "v24@0:8@?<v@?B>16"
+ "v24@0:8i16B20"
+ "v32@0:8i16B20@24"
+ "v32@?0@\"RBSProcessMonitor\"8@\"RBSProcessHandle\"16@\"RBSProcessStateUpdate\"24"
+ "waitForTrialOnQueue"
+ "writeKeepAliveMarkerOnQueue"
+ "zone"
- "Received XPC Event via notifyd: notification name = %@"
```

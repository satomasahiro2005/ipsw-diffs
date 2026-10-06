## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x380df4` | `0x382b50` | **`+0x1d5c`** |
| `__TEXT.__oslogstring` | `0x491a6` | `0x49755` | **`+0x5af`** |
| `__TEXT.__cstring` | `0x54ba5` | `0x54fff` | **`+0x45a`** |
| `__DATA_CONST.__cfstring` | `0x12ca0` | `0x12f40` | **`+0x2a0`** |
| `__DATA.__objc_const` | `0x35708` | `0x35988` | **`+0x280`** |
| `__TEXT.__objc_methname` | `0x6388e` | `0x63aa3` | **`+0x215`** |
| `__TEXT.__objc_stubs` | `0x48400` | `0x48560` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x146a0` | `0x147f8` | **`+0x158`** |
| `__DATA_CONST.__objc_arraydata` | `0x480` | `0x530` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x24040` | `0x240f0` | **`+0xb0`** |
| `__TEXT.__gcc_except_tab` | `0x3c14` | `0x3cc0` | **`+0xac`** |
| `__DATA.__objc_data` | `0x85c0` | `0x8660` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x15ab0` | `0x15b28` | **`+0x78`** |
| `__DATA.__data` | `0x5db8` | `0x5e20` | **`+0x68`** |
| `__DATA_CONST.__objc_arrayobj` | `0x198` | `0x1f8` | **`+0x60`** |
| `__DATA.__bss` | `0xe40` | `0xe98` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xa800` | `0xa850` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x5273` | `0x52bc` | **`+0x49`** |
| `__TEXT.__objc_methtype` | `0x1021b` | `0x10250` | **`+0x35`** |
| `__DATA_CONST.__got` | `0x3ea0` | `0x3eb8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2760` | `0x2774` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xd60` | `0xd70` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x3900` | `0x3910` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1c90` | `0x1c98` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x730` | `0x738` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xb30` | `0xb38` | **`+0x8`** |
| `__TEXT.__const` | `0xede0` | `0xede8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-3605.23.1.1.1
+3605.24.1.1.1

-  Functions: 14866
-  Symbols:   3022
-  CStrings:  28469
+  Functions: 14889
+  Symbols:   3024
+  CStrings:  28547
Symbols:
+ _OBJC_CLASS_$_SCDADeviceNameInfo
+ _TCCAccessCopyBundleIdentifiersDisabledForService
CStrings:
+ "%s %{public}s activity error: %{public}@"
+ "%s Activity %{public}s completed but another path already owns its transition; not setting done"
+ "%s Activity %{public}s did not accept DEFER during clean exit; it had already left the state we tried to release"
+ "%s Activity %{public}s finished, but the registry slot holds a DIFFERENT run; leaving it for its own owner"
+ "%s Activity %{public}s started while a previous run was still tracked (%{public}s object); the displaced run is unaccounted for"
+ "%s App %@ is excluded from Siri, not speaking announcement on platform: %@"
+ "%s App exclusion check for %@: excluded=%{BOOL}d, denyCount=%lu, expandedCount=%lu"
+ "%s App exclusions disabled by feature flag; treating %@ as not excluded"
+ "%s Clean exit: %lu of %lu in-flight XPC activit(ies) accepted a terminal transition for a pending clean exit"
+ "%s Deferring activity:%{public}s deferred:%{public}s"
+ "%s Failed setting activity state to continue for %{public}s"
+ "%s Failed setting activity state to done for %{public}s"
+ "%s Not deferring %{public}s: another path already owns its transition"
+ "%s Not starting activity %{public}s: the daemon began exiting cleanly. Releasing it."
+ "%s Not starting activity %{public}s: the daemon is exiting cleanly. Releasing it."
+ "%s Pending asset-fetch backstop count is unexpectedly large: %lu (threshold %lu), most recent language '%{public}@'. Either a client is looping on the asset-status XPC, or a tracking entry is being orphaned."
+ "%s Skipping CDM asset-status registration: no language code at registration time."
+ "%s Unable to retrieve LSApplicationRecord for %@: %@"
+ "%s getCompanionInfoFor couldn't find sharedUserId: %@ (primary user is %{private}@)"
+ "-[ADAssetManager _registerCDMStatusTrackerForLanguage:]"
+ "-[ADAssetManager fetchAssetsAvailabilityForLanguage:completion:]_block_invoke"
+ "/System/Library/Frameworks/CoreServices.framework/CoreServices"
+ "@\"SCDADeviceNameInfo\"24@0:8@\"NSString\"16"
+ "ADAppIsExcludedFromSiri"
+ "ADSCDADeviceNameResolver"
+ "B16@?0@\"NSObject<OS_xpc_object>\"8"
+ "MobileAssistantDaemons-3605.24.1.1.1"
+ "SCDADeviceNameResolving"
+ "_ADBundleIDIsAppClip"
+ "_ADDeferActivityIfExitingCleanly"
+ "_ADDeferInFlightActivitiesForExit"
+ "_ADFinishInFlightActivity"
+ "_ADHandleActivityState"
+ "_ADReleaseActivityForExit"
+ "_ADRunActivity"
+ "_ADSyncReplyGraphCanary"
+ "_ADTrackInFlightActivity"
+ "_ADUntrackInFlightActivity"
+ "_assetFetchCancelGeneration"
+ "_cancelPendingAssetFetchBackstopsOnQueue"
+ "_existingSharedStore"
+ "_isAppExcludedFromSiri:"
+ "_maxObservedPendingAssetFetchBackstops"
+ "_pendingAssetFetchBackstops"
+ "_registerCDMStatusTrackerForLanguage:"
+ "_syncExitFinishers"
+ "_syncExitLock"
+ "_syncExit_armFinisher:"
+ "_syncExit_drainForReason:"
+ "_syncExit_handleDaemonWillExitCleanly:"
+ "_syncExit_retireFinisher:"
+ "appClipMetadata"
+ "appExcludedFromSiri"
+ "com.apple.Fitness"
+ "com.apple.Health"
+ "com.apple.HeartRate"
+ "com.apple.Mind"
+ "com.apple.NanoHeartRhythm"
+ "com.apple.NanoMedications"
+ "com.apple.NanoMenstrualCycles"
+ "com.apple.NanoOxygenSaturation.watchkitapp"
+ "com.apple.NanoSleep.watchkitapp"
+ "com.apple.NanoStopwatch"
+ "com.apple.NanoWorldClock"
+ "com.apple.Noise"
+ "com.apple.app-clips"
+ "com.apple.findmy"
+ "com.apple.findmy.finddevices"
+ "com.apple.findmy.finditems"
+ "com.apple.findmy.findpeople"
+ "com.apple.findmy.watchapp"
+ "com.apple.mobiletimer"
+ "counterpartIdentifiers"
+ "daemon began exiting cleanly mid-sync"
+ "deviceNameResolver"
+ "different"
+ "initWithRoomName:deviceName:"
+ "isAppExclusionsEnabled"
+ "kTCCServiceSiriAccess"
+ "namesForIdsDeviceUniqueIdentifier:"
+ "removeObjectIdenticalTo:"
+ "same"
+ "setDeviceNameResolver:"
+ "the settings connection was invalidated before the sync finished"
+ "the settings connection went away before the sync finished"
+ "v24@0:8r*16"
+ "v32@?0@\"NSString\"8@16^B24"
- "%s %s activity error: %@"
- "%s Deferring activity:%@ deferred:%@"
- "%s Failed setting activity state to continue"
- "%s Failed setting activity state to done"
- "%s getCompanionInfoFor couldn't find sharedUserId: %@"
- "-[ADAssetManager _registerCDMStatusTracker]"
- "MobileAssistantDaemons-3605.23.1.1.1"
- "_RegisterXPCActivity_block_invoke"
- "_registerCDMStatusTracker"
```

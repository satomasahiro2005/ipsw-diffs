## SwiftMedia

> `/System/Library/PrivateFrameworks/SwiftMedia.framework/SwiftMedia`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74150` | `0x59c78` | **`-0x1a4d8`** |
| `__AUTH_CONST.__const` | `0x3760` | `0x1fd8` | **`-0x1788`** |
| `__TEXT.__oslogstring` | `0x23f0` | `0x1356` | **`-0x109a`** |
| `__TEXT.__swift5_capture` | `0x1270` | `0x8e4` | **`-0x98c`** |
| `__AUTH.__data` | `0x6f8` | `—` | **`-0x6f8`** |
| `__DATA_DIRTY.__data` | `0xbd8` | `0x1258` | **`+0x680`** |
| `__TEXT.__cstring` | `0x1044` | `0xd54` | **`-0x2f0`** |
| `__TEXT.__const` | `0x2f06` | `0x2c80` | **`-0x286`** |
| `__DATA.__bss` | `0x1ac0` | `0x1840` | **`-0x280`** |
| `__TEXT.__unwind_info` | `0x1500` | `0x13b8` | **`-0x148`** |
| `__TEXT.__constg_swiftt` | `0x100c` | `0xf5c` | **`-0xb0`** |
| `__TEXT.__swift5_typeref` | `0x128c` | `0x11ec` | **`-0xa0`** |
| `__DATA.__data` | `0x908` | `0x870` | **`-0x98`** |
| `__TEXT.__swift5_assocty` | `0x228` | `0x1c8` | **`-0x60`** |
| `__TEXT.__swift5_fieldmd` | `0xb00` | `0xaac` | **`-0x54`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0x3c` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0xe65` | `0xe1f` | **`-0x46`** |
| `__AUTH_CONST.__auth_got` | `0xa40` | `0xa28` | **`-0x18`** |
| `__TEXT.__eh_frame` | `0x3024` | `0x300c` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0xf8` | `0xe4` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0xf0` | `0xdc` | **`-0x14`** |
| `__DATA.__common` | `0x18` | `0x10` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-70.4.1.0.0
+70.8.1.0.0

-  Functions: 1956
-  Symbols:   685
-  CStrings:  209
+  Functions: 1660
+  Symbols:   666
+  CStrings:  135
Symbols:
+ ___swift_closure_destructor.309Tm
+ ___unnamed_6
+ _objc_retain_x1
- ___swift_closure_destructor.157Tm
- ___swift_closure_destructor.200Tm
- ___swift_closure_destructor.207Tm
- ___swift_closure_destructor.438Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.60Tm
- _associated conformance So26FigPlaybackItemCreateFlagsVs10SetAlgebraSCSQ
- _associated conformance So26FigPlaybackItemCreateFlagsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
- _associated conformance So26FigPlaybackItemCreateFlagsVs9OptionSetSCSY
- _associated conformance So26FigPlaybackItemCreateFlagsVs9OptionSetSCs0G7Algebra
- _symbolic $ss10SetAlgebraP
- _symbolic $ss25ExpressibleByArrayLiteralP
- _symbolic $ss9OptionSetP
- _symbolic SSIego_
- _symbolic _____ 10SwiftMedia0077__FileSpecificFigNoteConfiguration_defined_by_FigNoteConfiguration_niIIAaqFdFb33_13BE075A13167314BB1BC0F1B2A8E441LLV
- _symbolic _____ So21FigAssetCreationFlagsV
- _symbolic _____ So22FigPlayerPlaybackStateV
- _symbolic _____ So26FigPlaybackItemCreateFlagsV
- _symbolic _____ So27FigPlaybackRateChangeReasonV
- _symbolic _____Sg So11FigAssetRefa
- _symbolic _____XMT 10SwiftMedia15FigAssetWrapperC
- _type_layout_string So21FigAssetCreationFlagsV
CStrings:
- "%{public}s %{public}s%{public}sActivated auxiliary audio session"
- "%{public}s %{public}s%{public}sAdding item %s to queue after %s"
- "%{public}s %{public}s%{public}sApply playback state: %s"
- "%{public}s %{public}s%{public}sApplying new values: %s"
- "%{public}s %{public}s%{public}sDefault playback controller snapshot"
- "%{public}s %{public}s%{public}sDid pause playback"
- "%{public}s %{public}s%{public}sDid set playback controller: nil"
- "%{public}s %{public}s%{public}sFinished getting snapshots"
- "%{public}s %{public}s%{public}sGot new content"
- "%{public}s %{public}s%{public}sGot new snapshots"
- "%{public}s %{public}s%{public}sInvoking callback for rate change %s (rateChangeID: %s)"
- "%{public}s %{public}s%{public}sLeaving playback controller as-is, compatible with new content"
- "%{public}s %{public}s%{public}sMedia services were lost (generation %llu)"
- "%{public}s %{public}s%{public}sMedia services were reset"
- "%{public}s %{public}s%{public}sNew snapshot: %s"
- "%{public}s %{public}s%{public}sNot invoking callback for client-initiated rate change (rateChangeID: %s)"
- "%{public}s %{public}s%{public}sPlayback controller changed before callback, ignoring"
- "%{public}s %{public}s%{public}sProcessing notification batch of %ld: %s"
- "%{public}s %{public}s%{public}sRecreated auxiliary audio session (generation %llu)"
- "%{public}s %{public}s%{public}sRecreating session after media services reset"
- "%{public}s %{public}s%{public}sRecycling playbackController: %s, snapshot: %s"
- "%{public}s %{public}s%{public}sRemoving item %s from queue"
- "%{public}s %{public}s%{public}sReused for shared source"
- "%{public}s %{public}s%{public}sSampling current timestamp from: %s"
- "%{public}s %{public}s%{public}sSeeking to: %s, toleranceBefore: %s, toleranceAfter: %s"
- "%{public}s %{public}s%{public}sSet AllowsAirPlayVideo: %{bool}d"
- "%{public}s %{public}s%{public}sSet AllowsNeroPlayback: %{bool}d"
- "%{public}s %{public}s%{public}sSet AudioSessionID: %u"
- "%{public}s %{public}s%{public}sSet EndTime: %@"
- "%{public}s %{public}s%{public}sSet Muted: %{bool}d"
- "%{public}s %{public}s%{public}sSet PickerContextUUID: %{private}s"
- "%{public}s %{public}s%{public}sSet RestrictsAutomaticMediaSelectionToAvailableOfflineOptions: %{bool}d"
- "%{public}s %{public}s%{public}sSet ReverseEndTime: %@"
- "%{public}s %{public}s%{public}sSet Volume: %f"
- "%{public}s %{public}s%{public}sSet currentTime: %@, seekID: %d"
- "%{public}s %{public}s%{public}sSet up snapshot observation"
- "%{public}s %{public}s%{public}sSetting didStopPlayback to false (rateChangeID: %s)"
- "%{public}s %{public}s%{public}sSetting isPlaying to false due to bottom-up playback stoppage"
- "%{public}s %{public}s%{public}sSetting playbackResult = .playedToEnd"
- "%{public}s %{public}s%{public}sSetting snapshot to default"
- "%{public}s %{public}s%{public}sSnapshot yield was dropped by a continuation"
- "%{public}s %{public}s%{public}sSnapshot: %s, sourceTimeline: %s"
- "%{public}s %{public}s%{public}sSuppressing CMSessionBecameInactive: side effect of this player's own auxiliary session deactivation (rateChangeID: %s)"
- "%{public}s %{public}s%{public}sTimeline asked for current time when no timebase was available"
- "%{public}s %{public}s%{public}sUnable to get current rate from notificationEntry: %s"
- "%{public}s %{public}s%{public}sUpdating configuration"
- "%{public}s %{public}s%{public}sWait for first snapshot"
- "%{public}s %{public}s%{public}sWait for next snapshot"
- "%{public}s %{public}s%{public}sWill set playback controller"
- "%{public}s %{public}s%{public}sWill start playback"
- "%{public}s %{public}s%{public}s[%s] Callback from FigAssetRemoteCreateWithURLAndRetryAsync with figAsset = %s, error = %d"
- "%{public}s %{public}s%{public}s[%s] Calling FigAssetRemoteCreateWithURLAndRetryAsync with URL: %s, flags: %s, options: %@"
- "%{public}s %{public}s%{public}s[%s] Calling FigPlayerCreatePlaybackItemFromAsset with flags: %s"
- "%{public}s %{public}s%{public}scalled"
- "%{public}s %{public}s%{public}swrappedIterator: %s"
- "<<< OptionalPlayable >>>"
- "OptionalPlayable"
- "defaultPlaybackConfiguration: "
- "defaultPlaybackControllerSnapshot: "
- "handleDidPlayToEnd(_:_:_:): "
- "handleNotificationThatAffectsRate(notificationEntry:updating:suppressCMSessionBecameInactive:): "
- "init(audioSession:loggingIdentifier:isolation:): "
- "init(isolation:): "
- "init(wrappedIterator:): "
- "makeAsyncIterator(): "
- "mutateSnapshotAndNotify(_:): "
- "next(isolation:): "
- "optional.playbackcontroller"
- "recreateSession(): "
- "recreateSessionIfNeeded(): "
- "sampleCurrentTimeStamp(from:): "
- "seek(_:to:toleranceBefore:toleranceAfter:): "
- "timeControlStatus: "
- "timeline(from:on:sourceTimeline:): "
```

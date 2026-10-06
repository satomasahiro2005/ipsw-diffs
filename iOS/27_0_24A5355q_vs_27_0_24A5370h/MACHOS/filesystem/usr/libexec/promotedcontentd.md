## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c9f70` | `0x3d7b64` | **`+0xdbf4`** |
| `__DATA.__data` | `0xd6e8` | `0xe5d8` | **`+0xef0`** |
| `__DATA.__objc_const` | `0x2a520` | `0x2b2f8` | **`+0xdd8`** |
| `__TEXT.__oslogstring` | `0x1022c` | `0x10adc` | **`+0x8b0`** |
| `__TEXT.__const` | `0x2a97a` | `0x2b18a` | **`+0x810`** |
| `__TEXT.__constg_swiftt` | `0x5df4` | `0x63a4` | **`+0x5b0`** |
| `__TEXT.__objc_classname` | `0x4747` | `0x4be7` | **`+0x4a0`** |
| `__TEXT.__auth_stubs` | `0x5760` | `0x5b60` | **`+0x400`** |
| `__DATA.__objc_data` | `0x93f0` | `0x9778` | **`+0x388`** |
| `__TEXT.__swift5_fieldmd` | `0x45bc` | `0x4938` | **`+0x37c`** |
| `__TEXT.__objc_methname` | `0x26cad` | `0x26fed` | **`+0x340`** |
| `__TEXT.__swift5_typeref` | `0x3f88` | `0x42ba` | **`+0x332`** |
| `__DATA.__bss` | `0xdb20` | `0xde40` | **`+0x320`** |
| `__TEXT.__cstring` | `0x15995` | `0x15c95` | **`+0x300`** |
| `__DATA_CONST.__const` | `0x1c3e8` | `0x1c6b8` | **`+0x2d0`** |
| `__TEXT.__swift5_reflstr` | `0x3376` | `0x3626` | **`+0x2b0`** |
| `__TEXT.__unwind_info` | `0x6ec0` | `0x7120` | **`+0x260`** |
| `__DATA_CONST.__auth_got` | `0x2bc0` | `0x2dc0` | **`+0x200`** |
| `__DATA_CONST.__cfstring` | `0xf620` | `0xf7e0` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x15070` | `0x151f0` | **`+0x180`** |
| `__DATA_CONST.__auth_ptr` | `0x1440` | `0x15a8` | **`+0x168`** |
| `__TEXT.__objc_stubs` | `0x1a0a0` | `0x1a1c0` | **`+0x120`** |
| `__DATA_CONST.__got` | `0x1590` | `0x1650` | **`+0xc0`** |
| `__DATA_CONST.__objc_classlist` | `0xf50` | `0xfe0` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x9420` | `0x9498` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0x4bcc` | `0x4c2c` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x50cd` | `0x512d` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1230` | `0x1288` | **`+0x58`** |
| `__TEXT.__swift5_proto` | `0x7f0` | `0x844` | **`+0x54`** |
| `__TEXT.__swift5_types` | `0x56c` | `0x5bc` | **`+0x50`** |
| `__DATA_CONST.__objc_intobj` | `0x19f8` | `0x1a28` | **`+0x30`** |
| `__TEXT.__swift5_protos` | `0x108` | `0x11c` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x1448` | `0x1458` | **`+0x10`** |
| `__DATA.__common` | `0xd68` | `0xd70` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x268` | `0x26c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xe8` | `0xec` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x114` | `0x118` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-557.1.16.0.0
+557.1.21.0.0

-  Functions: 11569
-  Symbols:   2288
-  CStrings:  11533
+  Functions: 11778
+  Symbols:   2296
+  CStrings:  11632
Symbols:
+ OBJC_IVAR_$_APPBAdSpaceStatusEventRequest._pageLayoutFinal
+ OBJC_IVAR_$_APPBLogImpressionRequest._pageLayoutFinal
+ OBJC_IVAR_$_APPBLogSysEventRequest._pageLayoutFinal
+ OBJC_IVAR_$_APPBLogVideoAnalyticsEventRequest._pageLayoutFinal
+ _OBJC_CLASS_$_ADCoreSettings
+ _OBJC_CLASS_$_EligibilitySnapshotRefresher
+ _OBJC_CLASS_$_NSFileHandle
+ _OBJC_METACLASS_$_EligibilitySnapshotRefresher
CStrings:
+ "%@\n%@\n"
+ "%s age noising configuration: %s"
+ "%s applying noise to the users age"
+ "APDumpServerResponses"
+ "APFilesEnumerator: objectsIterator is nil; skipping enumeration."
+ "Age noising bucket configuration: %s"
+ "EligibilitySnapshotRefresher"
+ "Failed to dump server response to %{public}@: %{public}@"
+ "Generated noised birth year is %{sensitive}s"
+ "Generating noised birth year for actual birth year  %{sensitive}s"
+ "Override random number"
+ "PageLayoutCompactLandscape"
+ "PageLayoutCompactPortrait"
+ "PageLayoutLargeLandscape"
+ "PageLayoutLargePortrait"
+ "PageLayoutUnspecified"
+ "StringAsPageLayoutFinal:"
+ "Ti,N,V_pageLayoutFinal"
+ "User aged %ld is %s for noising"
+ "User with unknown age is %s for noising"
+ "[APDumpServerResponses] Context (%{public}@): Server response too large; dumped to file.\nWriting to: %{public}@"
+ "[EligibilitySnapshotRefresher] Built snapshot — protoU13: %{bool}d, eduMode: %{bool}d, isChild: %{bool}d, maidEducation: %{bool}d"
+ "[EligibilitySnapshotRefresher] Deinit; removed apAccountChanged observer"
+ "[EligibilitySnapshotRefresher] Draining queued refresh that fired before init completed"
+ "[EligibilitySnapshotRefresher] Installed; observing apAccountChanged on DistributedNotificationCenter"
+ "[EligibilitySnapshotRefresher] Posting snapshotChangedNotification on DistributedNotificationCenter"
+ "[EligibilitySnapshotRefresher] Rebuilding snapshot from keychain + AdCore and writing to UserDefaults"
+ "[EligibilitySnapshotRefresher] Received apAccountChanged — scheduling UserDefaults refresh"
+ "[EligibilitySnapshotRefresher] Wrote snapshot to %{public}s/%{public}s (%ld bytes)"
+ "[EligibilitySnapshotRefresher] refreshUserDefaults called before init — queued for drain on install (startup race)"
+ "[EligibilitySnapshotRefresher] refreshUserDefaults — APCS sync trigger received"
+ "[EligibilitySnapshotRefresher] seedUserDefaultsIfMissing — UserDefaults empty; building snapshot from keychain + AdCore and writing"
+ "[EligibilitySnapshotRefresher] seedUserDefaultsIfMissing — skipped; UserDefaults already seeded"
+ "[EligibilitySnapshotRefresher] write — JSON encode failed: %{public}s"
+ "[EligibilitySnapshotRefresher] write — could not open suite %{public}s"
+ "[com.apple.adplatforms:LegacyInterface] Received %@ from %@ with identifiers {\"r\":%@, \"ctx\":[%@], \"cnt\":[%@]} :"
+ "_TtC16promotedcontentd22NullAgeNoiseApplicator"
+ "_TtC16promotedcontentd24TracingAgeNoiseGenerator"
+ "_TtC16promotedcontentd25TracingAgeNoiseApplicator"
+ "_TtC16promotedcontentd26EligibleAgeNoiseApplicator"
+ "_TtC16promotedcontentd26TracingAgeNoisingQualifier"
+ "_TtC16promotedcontentd29ConfigurableAgeNoiseGenerator"
+ "_TtC16promotedcontentd30PredeterminedAgeNoiseGenerator"
+ "_TtC16promotedcontentd31ConfigurableAgeNoisingQualifier"
+ "_TtC16promotedcontentd31DeviceInfoPersonalizedAdsSource"
+ "_TtC16promotedcontentd32PredeterminedAgeNoisingQualifier"
+ "_TtC16promotedcontentd34AgeNoisingIdentifierRotationSignal"
+ "_TtC16promotedcontentd42TracingAgeNoisingBucketConfigurationSource"
+ "_TtC16promotedcontentd45DefaultAgeNoisingQualifierConfigurationSource"
+ "_TtC16promotedcontentd45TracingAgeNoisingQualifierConfigurationSource"
+ "_TtC16promotedcontentd47ConfigSystemAgeNoisingBucketConfigurationSource"
+ "_TtC16promotedcontentd48PredeterminedAgeNoisingBucketConfigurationSource"
+ "_TtC16promotedcontentd50ConfigSystemAgeNoisingQualifierConfigurationSource"
+ "_pageLayoutFinal"
+ "accountInformation"
+ "actualBirthYearSource"
+ "applicator"
+ "birthYearSourceDiagnostics"
+ "closeAndReturnError:"
+ "com.apple.ap.eligibilitySnapshot.refresher"
+ "com.apple.ap.poiConfig.refresher"
+ "com.apple.ap.promotedcontentd.responseDump"
+ "configurationSource"
+ "dataForKey:"
+ "eligibility"
+ "eligibilitySnapshotRefresher"
+ "fileHandleForWritingAtPath:"
+ "hasPageLayoutFinal"
+ "isProtoU13state"
+ "kADIDManager_ChangedNotification"
+ "maximumRestrictedAge: "
+ "noisedBirthYear"
+ "observer"
+ "overrideAgeNoisingRandomNumber"
+ "oversized_responses.bak.log"
+ "oversized_responses.log"
+ "pageLayout"
+ "pageLayoutFinal"
+ "pageLayoutFinalAsString:"
+ "page_layout_final"
+ "pcd-responses"
+ "personalizedAdsSource"
+ "postNotificationName:object:userInfo:"
+ "predeterminedConfiguration"
+ "promotedcontentd.EligibilitySnapshotRefresher"
+ "promotedcontentd.RotatingIdentifierProviderFactory"
+ "qualifier"
+ "randomDoubleGenerator"
+ "registeredType"
+ "removeItemAtPath:error:"
+ "seedUserDefaultsIfMissing"
+ "seekToEndReturningOffset:error:"
+ "setHasPageLayoutFinal:"
+ "setPageLayoutFinal:"
+ "shouldSendAdSpaceStatusEvent: NOT sending ASE %{public}@ for content %{public}@ because 3000 was already recorded (UR ordering rule)."
+ "tracedApplicator"
+ "tracedGenerator"
+ "tracedQualifier"
+ "tracedSource"
+ "writeData:error:"
+ "{?=\"actionableDuration\"b1\"eventType\"b1\"pageLayoutFinal\"b1\"requestCount\"b1}"
+ "{?=\"currentPlaybackTime\"b1\"timestamp\"b1\"totalDuration\"b1\"visiblePercentage\"b1\"eventSequence\"b1\"pageLayoutFinal\"b1\"videoState\"b1\"volume\"b1}"
+ "{?=\"pageLayoutFinal\"b1\"playbackTime\"b1\"type\"b1\"insufficientPlaybackTime\"b1\"screenSaverActive\"b1\"visuallyEngaged\"b1}"
+ "{?=\"responseTime\"b1\"timestamp\"b1\"pageLayoutFinal\"b1\"screenfuls\"b1\"slotPosition\"b1\"statusCode\"b1\"adReused\"b1\"firstMessage\"b1}"
- "birthYearSourceAnalytics"
- "{?=\"actionableDuration\"b1\"eventType\"b1\"requestCount\"b1}"
- "{?=\"currentPlaybackTime\"b1\"timestamp\"b1\"totalDuration\"b1\"visiblePercentage\"b1\"eventSequence\"b1\"videoState\"b1\"volume\"b1}"
- "{?=\"playbackTime\"b1\"type\"b1\"insufficientPlaybackTime\"b1\"screenSaverActive\"b1\"visuallyEngaged\"b1}"
- "{?=\"responseTime\"b1\"timestamp\"b1\"screenfuls\"b1\"slotPosition\"b1\"statusCode\"b1\"adReused\"b1\"firstMessage\"b1}"
```

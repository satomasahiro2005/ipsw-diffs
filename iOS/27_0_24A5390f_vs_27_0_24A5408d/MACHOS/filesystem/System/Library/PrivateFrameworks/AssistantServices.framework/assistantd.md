## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3708a8` | `0x371fcc` | **`+0x1724`** |
| `__TEXT.__oslogstring` | `0x45808` | `0x45d7e` | **`+0x576`** |
| `__TEXT.__objc_methname` | `0x61874` | `0x61bac` | **`+0x338`** |
| `__TEXT.__cstring` | `0x52b52` | `0x52dfa` | **`+0x2a8`** |
| `__TEXT.__objc_stubs` | `0x472e0` | `0x47440` | **`+0x160`** |
| `__DATA.__objc_const` | `0x34b30` | `0x34c58` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x235e8` | `0x23710` | **`+0x128`** |
| `__DATA_CONST.__cfstring` | `0x12320` | `0x123e0` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x15540` | `0x155e0` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x3800` | `0x3840` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x3a70` | `0x3aac` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0xa4e8` | `0xa520` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0xff0f` | `0xff45` | **`+0x36`** |
| `__DATA_CONST.__auth_got` | `0x1c10` | `0x1c30` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x267c` | `0x2694` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x8b8` | `0x8d0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3e80` | `0x3e78` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-3600.68.45.0.0
+3600.68.61.11.1

-  Functions: 14601
-  Symbols:   3001
-  CStrings:  27824
+  Functions: 14626
+  Symbols:   3004
+  CStrings:  27881
Symbols:
+ _AFCanSyncIFPVoices
+ _NSStringFromAFSiriRestrictionReasons
+ _objc_sync_enter
+ _objc_sync_exit
- _SANPMediaTypeVideoValue
CStrings:
+ "%s #IFToolbox Reinitializing Intelligence Toolbox Readiness delegate for locale: %{public}@"
+ "%s #SiriAvailability Synchronously updating capabilities for language code %@"
+ "%s #SiriAvailability recomputing: current locale changed"
+ "%s #hal Skipping context donation for type %{public}@: serialized context is nil"
+ "%s #hal Skipping context donation: nil type from metadata %@"
+ "%s #unredactedMeCard -cachedUnredactedMeCard invoked (meCard present: %d)"
+ "%s Asset manager is nil."
+ "%s Cannot re-initialize Intelligence Flow assets delegate, languageCode: '%{public}@' is invalid for locale creation."
+ "%s Cannot re-initialize Intelligence Flow assets delegate, languageCode: '%{public}@' is nil."
+ "%s Could not get AFHearablesExperienceManager shared instance to wire internal delegate"
+ "%s Dictation Sampling: Stopping adding audio samples after adding %ld bytes since the permit monitor requested an abort (e.g. background task expiration)."
+ "%s Dictation originates from the Siri app; forcing context clear to start a fresh dictation session."
+ "%s Reinitializing Intelligence Flow assets delegate for locale: %{public}@"
+ "%s Reply after the announce finished reading; completing %lu already-read announce(s) (current %@) instead of re-reading"
+ "%s Siri restriction imposed (%@) — disabling assistant"
+ "%s Synching Voice Trigger data in %f seconds (vtFireTime %llu requestedFireTime %llu)"
+ "%s Voice Trigger sync timer already scheduled to fire no later than %f seconds from now; not rescheduling (vtFireTime %llu requestedFireTime %llu)"
+ "%s siriAvailability is nil in _clearContextAndStartAssistantSessionWithInvocationContext:; triggering synchronous capabilities update"
+ "%s siriAvailability is nil in resumeSessionWithOptions:completion:; triggering synchronous capabilities update"
+ "%s ‼️ Forcing shake to dismiss for confirmation reject during announce! Active confirmation contexts: %@"
+ "%s 🫨🔍 ADDaemon: Internal delegate already wired, skipping"
+ "-[ADAssetManager registerAssetProvidersForLanguage:]"
+ "-[ADAssistantDataManager cachedUnredactedMeCard]"
+ "-[ADCommandCenter _clearContextAndStartAssistantSessionWithInvocationContext:]"
+ "-[ADCommandCenter handleSiriAvailabilityDidChange:]_block_invoke"
+ "-[ADCommandCenter resumeSessionWithOptions:completion:]_block_invoke"
+ "-[ADHearablesExperienceManager _wireInternalDelegateToClientManager]"
+ "-[ADSiriCapabilitiesStore handleCurrentLocaleDidChange:]"
+ "-[ADSiriCapabilitiesStore performFullUpdate]"
+ "-[ADSiriCapabilitiesStore updateCapabilitiesSynchronouslyForLanguageCode:]"
+ "-[AFMutableDeviceContext setSerializedContextSnapshot:withMetadata:]"
+ "37"
+ "@\"SAPerson\"16@0:8"
+ "ADSiriCapabilitiesStoreAvailabilityDidChangeNotification"
+ "ADSiriCapabilitiesStoreNewAvailabilityKey"
+ "ADSiriCapabilitiesStoreOldAvailabilityKey"
+ "MobileAssistantDaemons-3600.68.61.11.1"
+ "T@\"<AFHearablesExperienceManagerInternalDelegate>\",&,N,V_internalDelegateAdapter"
+ "TQ,N,V_voiceTriggerSyncFireTime"
+ "Ti,N,V_expressivityPreset"
+ "Ti,N,V_pacePreset"
+ "_expressivityPreset"
+ "_getIsLLMSiriAvailable"
+ "_internalDelegateAdapter"
+ "_pacePreset"
+ "_preferredMediaUserInfoSnapshot"
+ "_preferredMediaUserInfoSnapshotLock"
+ "_publishPreferredMediaUserInfoSnapshot"
+ "_voiceTriggerSyncFireTime"
+ "_wireInternalDelegateToClientManager"
+ "cachedUnredactedMeCard"
+ "com.apple.WebKit.GPU"
+ "com.apple.campo"
+ "expressivity_preset"
+ "handleCurrentLocaleDidChange:"
+ "handleSiriAvailabilityDidChange:"
+ "hasExpressivityPreset"
+ "hasPacePreset"
+ "internalDelegateAdapter"
+ "pace_preset"
+ "restrictionReasons"
+ "setExpressivityPreset:"
+ "setHasExpressivityPreset:"
+ "setHasPacePreset:"
+ "setInternalDelegateAdapter:"
+ "setIsLLMSiriAvailable:"
+ "setPacePreset:"
+ "setVoiceTriggerSyncFireTime:"
+ "unredactedMeCard"
+ "updateCapabilitiesSynchronouslyForLanguageCode:"
+ "voiceTriggerSyncFireTime"
+ "{?=\"expressivityPreset\"b1\"gender\"b1\"pacePreset\"b1}"
- "%s #IFToolbox Reinitializing Intelligence Toolbox Readiness delegate for new locale: %{public}@"
- "%s Asset manager is deallocated."
- "%s Cannot re-initialize Intelligence Flow assets delegate, new languageCode: '%{public}@' is invalid for locale creation."
- "%s Cannot re-initialize Intelligence Flow assets delegate, new languageCode: '%{public}@' is nil."
- "%s Interrupted media is video. It should not be resumed."
- "%s Reinitializing Intelligence Flow assets delegate for new locale: %{public}@"
- "%s Synching Voice Trigger data in %f seconds"
- "-[ADAssetManager languageCodeWasChangedTo:]_block_invoke"
- "-[ADSiriCapabilitiesStore updateCapabilitiesStore]"
- "15"
- "MobileAssistantDaemons-3600.68.45"
- "SiriExpressiveVoicesEnabled"
- "SiriSetup"
- "linwood_voices_seed"
- "{?=\"gender\"b1}"
```

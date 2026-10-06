## TranslationDaemon

> `/System/Library/PrivateFrameworks/TranslationDaemon.framework/TranslationDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a6db0` | `0x1a9d1c` | **`+0x2f6c`** |
| `__TEXT.__oslogstring` | `0xd5e0` | `0xd880` | **`+0x2a0`** |
| `__AUTH_CONST.__cfstring` | `0x7b20` | `0x7da0` | **`+0x280`** |
| `__TEXT.__cstring` | `0x627b` | `0x639b` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x4420` | `0x4510` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x1a2d8` | `0x1a390` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0xf9a8` | `0xfa40` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x2d088` | `0x2d118` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b30` | `0x6ba0` | **`+0x70`** |
| `__DATA.__data` | `0xcb8` | `0xd00` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x1b3d4` | `0x1b41c` | **`+0x48`** |
| `__DATA_CONST.__got` | `0xeb8` | `0xef8` | **`+0x40`** |
| `__DATA.__bss` | `0x7a0` | `0x7d0` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x10a8` | `0x10c8` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x2e8` | `0x300` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x11cc` | `0x11e0` | **`+0x14`** |
| `__DATA_DIRTY.__bss` | `0x380` | `0x370` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x278` | `0x268` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x342` | `0x34f` | **`+0xd`** |
| `__AUTH_CONST.__auth_got` | `0xcf8` | `0xd00` | **`+0x8`** |
| `__TEXT.__const` | `0xa9a` | `0xaa0` | **`+0x6`** |

### Other Changes

```diff

-385.0.0.0.0
+388.0.0.0.0

-  Functions: 10395
-  Symbols:   18731
-  CStrings:  2227
+  Functions: 10429
+  Symbols:   18768
+  CStrings:  2262
Symbols:
+ +[MTSchemaMTAppInvocationMetadata(LTTranslationAdditions) lt_initWithTranslateAppContext:resolvedLocalePair:]
+ +[_LTDLanguageAssetService _currentSyncSignatureFromAssets:]
+ +[_LTDUAFAssetService _catalogLookupThrottleEnabled]
+ +[_LTDUAFAssetService _startCatalogChangeObservationIfNeeded]
+ +[_LTDUAFAssetService _updateCatalogCooldownWithSubscribedCount:resolvedCount:catalog:]
+ +[_LTTranslationResult(Daemon) passthroughResultWithString:sanitizedString:locale:engineInfo:]
+ +[_LTTranslationResult(Daemon) resultWithLocale:translations:engineInfo:]
+ -[_LTActivityLogger _sendCommonEventForTask:appIdentifier:contentType:]
+ -[_LTActivityLogger beginCommonEventSession:appIdentifier:]
+ -[_LTActivityLogger beginCommonEventSession:appIdentifier:contentType:]
+ -[_LTActivityLogger endCommonEventSession]
+ -[_LTActivityLogger registerActivity:appIdentifier:]
+ -[_LTActivityLogger registerActivity:appIdentifier:contentType:]
+ -[_LTClientConnection _applyConnectionTrustToContext:]
+ -[_LTTranslationServer _registerTextActivityForContext:]
+ -[_LTTranslationServer _scheduleMessagingSessionReset]
+ -[_LTTranslationServer endCommonEventSession]
+ -[_LTTranslationServer registerActivity:appIdentifier:]
+ -[_LTTranslationServer registerActivity:appIdentifier:contentType:]
+ _LTDResolvedConferencingLocale
+ _LTDResolvedConferencingLocalePairWithSupportedLocales
+ _OBJC_IVAR_$__LTActivityLogger._activeCommonEventSessionHint
+ _OBJC_IVAR_$__LTActivityLogger._commonEventSessionLock
+ _OBJC_IVAR_$__LTClientConnection._canOverrideClientPID
+ _OBJC_IVAR_$__LTClientConnection._speechTaskHint
+ _OBJC_IVAR_$__LTTranslationServer._messagingSessionResetTimer
+ __LTPreferencesThrottleCatalogLookups
+ ___31+[_LTDUAFAssetService _catalog]_block_invoke
+ ___42-[_LTActivityLogger endCommonEventSession]_block_invoke
+ ___54-[_LTTranslationServer _scheduleMessagingSessionReset]_block_invoke
+ ___61+[_LTDUAFAssetService _startCatalogChangeObservationIfNeeded]_block_invoke
+ ___61+[_LTDUAFAssetService _startCatalogChangeObservationIfNeeded]_block_invoke_2
+ ___64-[_LTActivityLogger registerActivity:appIdentifier:contentType:]_block_invoke
+ ___71-[_LTActivityLogger beginCommonEventSession:appIdentifier:contentType:]_block_invoke
+ ___87+[_LTDUAFAssetService _updateCatalogCooldownWithSubscribedCount:resolvedCount:catalog:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e5_v8?0ls32l8w40l8
+ ___block_descriptor_48_e8_32s_e5_B8?0ls32l8
+ ___block_descriptor_49_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_56_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ __cachedCatalog
+ __catalogCooldownInterval
+ __catalogLookupSuppressed
+ __lastSyncedLocaleSignature
+ __localesWithVoice
+ __localesWithVoiceLock
+ __startCatalogChangeObservationIfNeeded.onceToken
+ _os_unfair_lock_assert_owner
+ _swift_allocError
+ _symbolic _____Sg 20TranslationInference0A9ModelInfoV
+ _symbolic _____Sg 20TranslationInference0A9ModelInfoV0C4TypeO
+ _symbolic _____Sg_ABt 20TranslationInference0A9ModelInfoV0C4TypeO
+ _symbolic _____y_____G s11_SetStorageC 10Foundation6LocaleV
- +[MTSchemaMTAppInvocationMetadata(LTTranslationAdditions) lt_initWithTranslateAppContext:]
- +[_LTDTTSAssetService _allTTSAssets]
- +[_LTTranslationResult(Daemon) passthroughResultWithString:sanitizedString:locale:]
- +[_LTTranslationResult(Daemon) resultWithLocale:translations:]
- -[_LTActivityLogger registerActivity:]
- -[_LTTranslationServer registerActivity:]
- __CLASS_METHODS__LTAIAdapterImplementation
- __IVARS__LTModelModalities
- ___36+[_LTDTTSAssetService _allTTSAssets]_block_invoke
- ___64+[_LTDLanguageAssetService _syncInstalledLocalesWithCompletion:]_block_invoke_2
- ___block_descriptor_40_e28_"NSString"16?0"NSString"8l
- ___swift_destroy_boxed_opaque_existential_1
- __cachedTTSAssets
- _swift_retain
- _symbolic _____ySSG s23_ContiguousArrayStorageC
- _symbolic _____y__________G 12ModelCatalog0B5AssetV AA016TranslateFMAssetC8MetadataV AA0deC8ContentsV
CStrings:
+ "2"
+ "Asset set changed but catalog still unresolved; keeping catalog lookup cooldown"
+ "B8@?0"
+ "Catalog cooldown check: subscribed=%lu resolved=%lu -> %{public}s"
+ "Connection can-override-client-pid: %{BOOL}i"
+ "Etiquette URL available for locale %{public}s"
+ "Failed to get etiquette URL: phrasebook asset unavailable"
+ "Healthy catalog rebuild resolved assets; clearing catalog lookup cooldown"
+ "Messages"
+ "Overriding client PID %d with originating PID %d"
+ "PT"
+ "PhoneCall"
+ "Skipping UAF catalog rebuild during lookup cooldown, returning cached catalog"
+ "Sync install no-op: signature unchanged"
+ "System"
+ "ThrottleCatalogLookups"
+ "UAF Asset in the _catalog (lookup throttle %{public}s)"
+ "UAF catalog lookup cooldown elapsed"
+ "UAF catalog resolved no assets while subscribed; suppressing lookups for %.0fs"
+ "UAF catalog resolved, cleared catalog lookup cooldown"
+ "action"
+ "automatic"
+ "button"
+ "clear"
+ "com.apple.translation.can-override-client-pid"
+ "disabled"
+ "enabled"
+ "identifierForDownloads"
+ "initiated_by"
+ "input_mode"
+ "intelligence.CommonEvent"
+ "is_saved_content"
+ "origin_surface"
+ "request_made"
+ "result_surface"
+ "source_app"
+ "sub_feature"
+ "suppress"
+ "|"
- "@\"NSString\"16@?0@\"NSString\"8"
- "Failed to get etiquette URL from phrasebook asset: %@"
- "UAF Asset in the _catalog"
- "a"
```

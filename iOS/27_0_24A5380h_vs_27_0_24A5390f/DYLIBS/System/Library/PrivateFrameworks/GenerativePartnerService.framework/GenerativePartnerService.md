## GenerativePartnerService

> `/System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c294` | `0x8ec50` | **`+0x29bc`** |
| `__TEXT.__oslogstring` | `0x3efd` | `0x419d` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x1cab` | `0x1f3b` | **`+0x290`** |
| `__DATA.__bss` | `0x40a0` | `0x41a0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x4bd0` | `0x4cb8` | **`+0xe8`** |
| `__TEXT.__unwind_info` | `0x2680` | `0x2728` | **`+0xa8`** |
| `__AUTH_CONST.__const` | `0x62a0` | `0x6210` | **`-0x90`** |
| `__AUTH.__data` | `0x740` | `0x7c0` | **`+0x80`** |
| `__DATA_DIRTY.__bss` | `0x1500` | `0x1480` | **`-0x80`** |
| `__TEXT.__const` | `0x4c98` | `0x4cf8` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x14b8` | `0x14e8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x13a1` | `0x13d1` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x390` | `0x3bc` | **`+0x2c`** |
| `__TEXT.__constg_swiftt` | `0x15b4` | `0x15dc` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1721` | `0x16ff` | **`-0x22`** |
| `__DATA.__data` | `0x8c8` | `0x8e8` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x15f8` | `0x15d8` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x15e4` | `0x1600` | **`+0x1c`** |
| `__DATA.__common` | `0x88` | `0xa0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x7b0` | `0x7c8` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x168` | `0x150` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x300` | `0x310` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x137c` | `0x138c` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2bc` | `0x2c0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1c8` | `0x1cc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1bc` | `0x1b8` | **`-0x4`** |

### Other Changes

```diff

-287.0.6.0.0
+291.1.0.5.0

-  Functions: 4413
-  Symbols:   233
-  CStrings:  430
+  Functions: 4483
+  Symbols:   236
+  CStrings:  457
Symbols:
+ _os_transaction_create
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
- _TCCAccessRequest
CStrings:
+ "\nsettingsVoiceSelection = "
+ " (forced initial update)"
+ "%{public}s finished in %{public}ldms"
+ ") - load provider decl"
+ ") - partner availability ("
+ ", debugVoiceType: "
+ ", isLocallyAvailable: "
+ "AvailabilityStore.GMAvailability.current() - .%{public}s"
+ "AvailabilityStore.GMAvailability.current() - .%{public}s, info: %{public}s"
+ "AvailabilityStore.PerProviderAvailability.current(availabilityIdentifier: "
+ "AvailabilityStore.PerProviderAvailability.current(for:) - for useCaseIdentifier=%{public}s: .%{public}s"
+ "AvailabilityStore.PerProviderAvailability.current(for:) - for useCaseIdentifier=%{public}s: .%{public}s, info: %{public}s"
+ "AvailabilityStore.UserFacingExternalAIRestrictedReason.current() - %{public}s"
+ "ChatGPT availability"
+ "EPS init start"
+ "EPS init task - ChatGPT defaults report:\nGPS state = %{public}s\nGAS state = %{public}s"
+ "GPSProvider init"
+ "GPSProvider init - updateLLMAvailability initial load"
+ "GPSProvider init start"
+ "GenerativePartnerService.getAppStoreMetadata"
+ "TCCUtils - resetting %{public}s for %{public}s"
+ "TCCUtils - toggling on %{public}s for %{public}s"
+ "User-facing restricted reason"
+ "VoiceSelection(name: "
+ "VoiceSelection: Unable to convert string to UTF-8 data"
+ "VoiceSelection: Unable to decode data to SiriVoiceAssetMetadata; string value:\n%{public}s"
+ "VoiceSelection: Unable to encode %{public}s"
+ "VoiceSelection:Unable to convert encoded data to UTF-8 string"
+ "[DEBUG] EPS init task - TCC state report:\nkTCCServiceExternalAIVisibleToSystem bundles = %{public}s\nkTCCServiceExternalAIProviderBlocked bundles = %{public}s"
+ "[ERROR] TCCUtils - FAILED to reset %{public}s for %{public}s"
+ "[ERROR] TCCUtils - FAILED to toggle on %{public}s for %{public}s"
+ "[ERROR] This process does not have the entitlement to read/write to %{public}s. Will not use a cache for external provider lists, and other features will be missing."
+ "[Non-XPC-client path] Setting the internal change handler"
+ "[XPC-client path] Setting the internal change handler through XPC"
+ "com.apple.externalproviderservice-xpc"
+ "extensionConnectionTime"
+ "externalProviders() fetching"
+ "externalProviders() returning %{public}ld providers"
+ "generativeexperiencesd"
+ "requestCompletion_v3: opensIntent %s"
+ "requestCompletion_v3: opensIntent: missing url parameter on toolInvocation"
+ "settingsVoiceSelection"
+ "updateLLMAvailability(isInitialLoad: "
- "Entitlement found for %s"
- "ExternalProviderService initialization"
- "No entitlement found for %s"
- "Setting the internal change handler"
- "Setting the internal change handler through XPC"
- "This process does not have the entitlement to read/write to %{public}s. Will not use a cache for external provider lists, and other features will be missing."
- "[AvailabilityStore.GMAvailability.current()] Retrieved GM status: .%{public}s, info: %{public}s"
- "[AvailabilityStore.PerProviderAvailability.current(for:)] Retrieved availability status for useCaseIdentifier=%{public}s: .%{public}s, info: %{public}s"
- "[AvailabilityStore.UserFacingExternalAIRestrictedReason.current()] retrieved value: %s"
- "externalProviders() returning %ld providers in: %{public}ld ms"
- "isLocallyAvailable"
- "requestUserAuthorization(appBundleID:)"
- "selectedSiriTTSVoiceForExternalAgent getter: Unable to convert string to UTF-8 data"
- "selectedSiriTTSVoiceForExternalAgent getter: Unable to decode data to SiriVoiceAssetMetadata; stored value:\n%{public}s"
- "selectedSiriTTSVoiceForExternalAgent setter: Unable to convert encoded data to UTF-8 string"
- "selectedSiriTTSVoiceForExternalAgent setter: Unable to encode %{public}s"
```

## GenerativePartnerService

> `/System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94298` | `0x9ce30` | **`+0x8b98`** |
| `__DATA.__bss` | `0x4320` | `0x4ba0` | **`+0x880`** |
| `__TEXT.__const` | `0x5018` | `0x5648` | **`+0x630`** |
| `__AUTH_CONST.__const` | `0x6330` | `0x6820` | **`+0x4f0`** |
| `__TEXT.__eh_frame` | `0x4e10` | `0x51c8` | **`+0x3b8`** |
| `__TEXT.__swift5_typeref` | `0x1733` | `0x1993` | **`+0x260`** |
| `__TEXT.__unwind_info` | `0x2980` | `0x2bd0` | **`+0x250`** |
| `__TEXT.__cstring` | `0x244b` | `0x267b` | **`+0x230`** |
| `__DATA.__data` | `0x910` | `0xb38` | **`+0x228`** |
| `__AUTH_CONST.__objc_const` | `0x11b8` | `0x1370` | **`+0x1b8`** |
| `__TEXT.__swift5_fieldmd` | `0x16e4` | `0x187c` | **`+0x198`** |
| `__TEXT.__oslogstring` | `0x41dd` | `0x434d` | **`+0x170`** |
| `__TEXT.__objc_methlist` | `0x21c` | `0x36c` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0x15dc` | `0x1714` | **`+0x138`** |
| `__AUTH.__data` | `0x7c0` | `0x8b8` | **`+0xf8`** |
| `__TEXT.__swift5_reflstr` | `0x15a1` | `0x1691` | **`+0xf0`** |
| `__DATA_DIRTY.__data` | `0x15d0` | `0x1508` | **`-0xc8`** |
| `__AUTH.__objc_data` | `0x190` | `0x250` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x348` | `0x408` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x1588` | `0x1630` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x13ec` | `0x1444` | **`+0x58`** |
| `__TEXT.__swift5_proto` | `0x2cc` | `0x310` | **`+0x44`** |
| `__TEXT.__swift5_assocty` | `0x358` | `0x388` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x1cc` | `0x1f0` | **`+0x24`** |
| `__TEXT.__swift_as_cont` | `0x3f0` | `0x404` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1cc` | `0x1dc` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1d8` | `0x1e4` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x28` | **`+0x8`** |

### Other Changes

```diff

-291.6.0.5.102
+297.6.0.5.0

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 4629
-  Symbols:   236
-  CStrings:  485
+  Functions: 4820
+  Symbols:   237
+  CStrings:  508
Symbols:
+ _objc_retain_x2
CStrings:
+ "%{public}s failed with exception: %{public}@"
+ "%{public}s: EPS init start"
+ "%{public}s: First unlock: warming provider cache"
+ "%{public}s: Registering first-unlock provider-cache warm-up"
+ "%{public}s: [Non-XPC-client path] Setting the internal change handler"
+ "%{public}s: [XPC-client path] Setting the internal change handler through XPC"
+ "%{public}s: fetched and stored %{public}ld external providers"
+ "%{public}s: fetching providers via XPC"
+ "%{public}s: no cache populated this lifetime; fetching fresh"
+ "%{public}s: returning %{public}ld external providers from XPC"
+ "%{public}s: returning %{public}ld providers"
+ "%{public}s: serving provider %{public}s"
+ "%{public}s: using cached external providers"
+ "/System/Library/PrivateFrameworks/IntelligenceFlowPlannerSupport.framework"
+ "Enhanced Siri is not opted in; skipping the vip metadata refresh"
+ "Enhanced Siri turned on; refreshing the vip metadata skipped while it was off"
+ "Loaded %{public}ld invocation patterns (locale=%{public}s version=%{public}s)"
+ "No invocation patterns for %{public}s: %{public}s"
+ "No invocation patterns: %{public}s"
+ "Refreshed metadata for %{public}ld providers"
+ "Skipping VIP provider \"%s\": not available on %s"
+ "Skipping uncompilable pattern: %{public}s"
+ "action"
+ "converted_patterns"
+ "could not parse "
+ "export produced no output file"
+ "externalProviders()"
+ "fetchAndStoreExternalProviders()"
+ "installedExternalProviders()"
+ "no Enigma asset for "
+ "no ask_provider patterns in "
+ "no enigma_patterns directory in "
+ "no locale given and none to resolve from"
+ "pattern"
+ "priority"
+ "regex"
+ "requestCompletion_v3(...) failed with ExternalProviderError: %s"
+ "requestCompletion_v3: streaming event error: %{public}@"
+ "unexpected confirmation request"
+ "unexpected disambiguation request"
+ "unexpected value request"
+ "version"
- "EPS init start"
- "Error during XPC call to fetch externalProviders: %{public}@. Trying local fallback."
- "External providers changed; notify observers."
- "ExternalProviderService: configuration changed, refreshing cache"
- "Fetching externalProviders() locally"
- "Fetching externalProviders() via XPC"
- "No cache; retrieve fresh external providers"
- "No changes found in external providers list."
- "No providers returned (this is suspicious)"
- "Refreshing cache at medium priority"
- "Returning %{public}ld external providers from XPC"
- "Serving cached provider: %{public}s"
- "Storing retrieved external providers"
- "Updating external providers list now."
- "Using cache for externalProviders"
- "[Non-XPC-client path] Setting the internal change handler"
- "[XPC-client path] Setting the internal change handler through XPC"
- "externalProviders() failed with exception: %{public}@"
- "externalProviders() returning %{public}ld providers"
```

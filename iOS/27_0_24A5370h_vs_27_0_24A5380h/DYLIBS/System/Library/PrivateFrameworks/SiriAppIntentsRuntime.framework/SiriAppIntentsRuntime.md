## SiriAppIntentsRuntime

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/SiriAppIntentsRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7982c` | `0x7c728` | **`+0x2efc`** |
| `__DATA_DIRTY.__data` | `—` | `0xd28` | **`+0xd28`** |
| `__DATA_DIRTY.__bss` | `—` | `0xb80` | **`+0xb80`** |
| `__DATA.__bss` | `0x1f00` | `0x1400` | **`-0xb00`** |
| `__AUTH.__objc_data` | `0xa60` | `0xa0` | **`-0x9c0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x9c0` | **`+0x9c0`** |
| `__AUTH.__data` | `0xba8` | `0x570` | **`-0x638`** |
| `__DATA.__data` | `0xd28` | `0x7e8` | **`-0x540`** |
| `__TEXT.__oslogstring` | `0x305d` | `0x32dd` | **`+0x280`** |
| `__DATA.__common` | `0x198` | `0x88` | **`-0x110`** |
| `__DATA_DIRTY.__common` | `—` | `0x110` | **`+0x110`** |
| `__AUTH_CONST.__const` | `0x4288` | `0x4378` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0xc18` | `0xcc8` | **`+0xb0`** |
| `__TEXT.__const` | `0x26e8` | `0x2798` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0xc24` | `0xc9c` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x16e8` | `0x1758` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0xc86` | `0xcf6` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x8d4` | `0x940` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x13d1` | `0x1431` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x1297` | `0x12f3` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x120` | `0x170` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1840` | `0x1888` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x19f0` | `0x1a10` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x2e4` | `0x2cc` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x430` | `0x438` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x4668` | `0x4670` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xac` | `0xb4` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x178` | `0x170` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x100` | `0x104` | **`+0x4`** |

### Other Changes

```diff

-3600.82.2.1.1
+3600.82.15.0.0

+  - /System/Library/PrivateFrameworks/IntelligencePlatformLibrary_AppleInternal.framework/IntelligencePlatformLibrary_AppleInternal

-  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 2753
-  Symbols:   212
-  CStrings:  320
+  Functions: 2792
+  Symbols:   214
+  CStrings:  330
Symbols:
+ _swift_allocBox
+ _swift_release_x12
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
- _swift_deallocPartialClassInstance
- _swift_isaMask
CStrings:
+ "%{public}s ✅ Connection accepted via code signing fallback (identity verified at resume)"
+ "No matching token-generation request for plannerID: "
+ "SiriAppIntentsDaemon: skipping RemoteXPC listener (customer build)"
+ "SiriAppIntentsDaemon: startup complete kind=summary internalBuild=%{bool}d"
+ "SiriHeliosTokenGenerationReplay"
+ "TokenGeneration stream fetch failed: "
+ "TokenGenerationStreamHandler.fetchEvents: kind=summary plannerID=%s matched=%ld"
+ "TokenGenerationStreamHandler.fetchEvents: kind=summary status=failed plannerID=%s error=%s"
+ "XPCServer: FeatureStore event stream created, beginning live delivery to client"
+ "XPCServer: fetchSessionEvents yielding %ld message(s) for session %s"
+ "XPCServer: startStreaming — creating FeatureStore event stream"
+ "[Replay] No matching token-generation request for plannerID: %s"
+ "[Replay] Stream returned payload (%ld chars) for requestIdentifier: %s"
+ "[Replay] TokenGeneration stream fetch failed: %@"
+ "[Replay] TokenGeneration stream unavailable for plannerID: %s"
+ "[Replay] invalidPlannerID rejected by stream handler: %s"
+ "fetchEvents(plannerID:requestTimestamp:)"
+ "fetchPlannerToolsByType: unrecognised plannerType '%s'"
- "%{public}s Connection rejected: no bundle ID provided"
- "No Execute Request signpost found for plannerID: "
- "[ReplayExport] tgtool not available, skipping replay payload fetch"
- "[Replay] No Execute Request signpost found for plannerID: %s"
- "[Replay] tgtool failed: %@"
- "[Replay] tgtool returned %ld characters for requestIdentifier: %s"
- "kind=parseFailed fetchRawInferenceEventData plannerID=%s outputLen=%ld lineCount=%ld parseFailures=%ld"
- "tgtool replay list failed: "
```

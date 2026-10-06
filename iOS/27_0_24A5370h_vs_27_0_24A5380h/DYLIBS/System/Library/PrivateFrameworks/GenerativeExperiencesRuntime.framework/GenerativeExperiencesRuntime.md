## GenerativeExperiencesRuntime

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/GenerativeExperiencesRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe5084` | `0xe7014` | **`+0x1f90`** |
| `__AUTH_CONST.__const` | `0x7d80` | `0x8428` | **`+0x6a8`** |
| `__DATA_DIRTY.__data` | `0x2ff0` | `0x32d0` | **`+0x2e0`** |
| `__TEXT.__eh_frame` | `0x8e1c` | `0x90ec` | **`+0x2d0`** |
| `__TEXT.__swift5_capture` | `0x24c8` | `0x276c` | **`+0x2a4`** |
| `__DATA.__bss` | `0x29f0` | `0x2770` | **`-0x280`** |
| `__DATA.__data` | `0xd00` | `0xad8` | **`-0x228`** |
| `__AUTH.__data` | `0x5f8` | `0x430` | **`-0x1c8`** |
| `__DATA_DIRTY.__bss` | `0x2780` | `0x2900` | **`+0x180`** |
| `__TEXT.__const` | `0x5afc` | `0x5a7c` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x1f1c` | `0x1ea8` | **`-0x74`** |
| `__AUTH.__objc_data` | `0x428` | `0x3b8` | **`-0x70`** |
| `__TEXT.__cstring` | `0x1ed5` | `0x1e65` | **`-0x70`** |
| `__TEXT.__swift5_typeref` | `0x28dc` | `0x286c` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x3330` | `0x33a0` | **`+0x70`** |
| `__DATA.__common` | `0xd8` | `0x78` | **`-0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x147c` | `0x1428` | **`-0x54`** |
| `__TEXT.__swift_as_cont` | `0x6b0` | `0x6fc` | **`+0x4c`** |
| `__AUTH_CONST.__objc_const` | `0x3108` | `0x3150` | **`+0x48`** |
| `__DATA_DIRTY.__common` | `0x280` | `0x2b0` | **`+0x30`** |
| `__DATA_DIRTY.__objc_data` | `0x698` | `0x6c8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x6c0` | `0x6e0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x420` | `0x400` | **`-0x20`** |
| `__TEXT.__swift_as_ret` | `0x33c` | `0x354` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2770` | `0x2780` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x94c` | `0x95c` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x8770` | `0x8760` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xfed` | `0xffd` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x324` | `0x334` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x228` | `0x21c` | **`-0xc`** |
| `__TEXT.__swift5_proto` | `0x304` | `0x300` | **`-0x4`** |

### Other Changes

```diff

-284.0.7.0.0
+287.0.6.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 5048
-  Symbols:   283
-  CStrings:  650
+  Functions: 5122
+  Symbols:   282
+  CStrings:  647
Symbols:
+ _OBJC_CLASS_$_BGNonRepeatingSystemTaskRequest
- _OBJC_CLASS_$_NSXPCListenerEndpoint
- _swift_getFunctionTypeMetadata0
CStrings:
+ "ExternalProviderServiceXPC.Server init"
+ "PQAReadinessPollOneShot.schedule: FF off; no-op"
+ "PQAReadinessPollOneShot.schedule: submitTaskRequest returned: %{public}@"
+ "PQAReadinessPollOneShot.schedule: submitted"
+ "PeriodicTask: Running task for %{public}s with priority %{public}s"
+ "XPC: client subscribed to provider changes"
+ "XPC: client unsubscribed from provider changes"
+ "XPC: failed to forward provider change: %@"
+ "XPC: forwarding provider change to client: %{public}s"
+ "com.apple.GenerativeFunctions.PeriodicTasks.AvailabilityUpdateTask.PQAReadinessPollOneShot"
+ "runEnhancedSiriOnboardingCheck()"
- "ExternalProviderServiceXPC.ResidentService: sending change notification: %{public}s"
- "ExternalProviderServiceXPC.Server: Deinitializing"
- "ExternalProviderServiceXPC.init"
- "ResidentService deinitializing"
- "ResidentService initializing"
- "ResidentService: registered ExternalProviderServiceXPC.ResidentService as an observer"
- "XPC: Invalid observer ID: %s"
- "XPC: Registered observer: %s"
- "XPC: Unregistered observer: %s, success: %{bool}d"
- "XPC: registerObserver() called with ID: %s"
- "XPC: unregisterObserver() called with ID: %s"
- "com.apple.generativeexperiences.ExternalPartnerCredentialStorage"
- "com.apple.generativeexperiences.ExternalProviderService"
- "com.apple.generativeexperiences.ExternalProviderTCCManagingXPC"
```

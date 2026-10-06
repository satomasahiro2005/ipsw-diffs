## SiriAvailability

> `/System/Library/PrivateFrameworks/SiriAvailability.framework/SiriAvailability`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ddc` | `0x3a80` | **`+0xca4`** |
| `__TEXT.__cstring` | `0x4d4` | `0x693` | **`+0x1bf`** |
| `__AUTH_CONST.__objc_const` | `0x5d0` | `0x6c0` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x6e0` | `0x7c0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x1c6` | `0x29d` | **`+0xd7`** |
| `__TEXT.__objc_methlist` | `0x39c` | `0x424` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d0` | `0x330` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x20` | `0x40` | **`+0x20`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__const` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x150` | `0x158` | **`+0x8`** |

### Other Changes

```diff

-3600.13.1.0.0
+3600.13.4.0.0

-  Functions: 65
-  Symbols:   99
-  CStrings:  70
+  Functions: 77
+  Symbols:   107
+  CStrings:  82
Symbols:
+ ___error
+ _free
+ _malloc_type_calloc
+ _objc_release_x25
+ _objc_release_x27
+ _objc_release_x28
+ _objc_release_x9
+ _sysctlbyname
CStrings:
+ "#SiriAvailability failed to allocate memory for boot session UUID: %{darwin.errno}d"
+ "#SiriAvailability failed to get kern.bootsessionuuid data: %{darwin.errno}d"
+ "#SiriAvailability failed to get kern.bootsessionuuid length: %{darwin.errno}d"
+ "<%@: %p; isAvailable: %@; siriLocale: %@; desiredOrchestrationMode: %@; desiredOrchestrationModeIfEnabled: %@; currentOrchestrationMode: %@; unavailabilityReasons: %@; linwoodEverAvailable:%@; bootUUID:%@ fromCurrentBootSession:%@>"
+ "Domain answer: invalid"
+ "Domain answer: not yet available"
+ "Error fetching domain answer: %{public}d"
+ "NotAccessRestricted"
+ "SOSiriAvailability {\n  isAvailable: %@\n  siriLocale: %@\n  desiredOrchestrationMode: %@\n  desiredOrchestrationModeIfEnabled: %@\n  currentOrchestrationMode: %@\n  unavailabilityReasons: %@\n  linwoodEverAvailable:%@\n  bootUUID: %@\n  fromCurrentBootSession: %@\n}"
+ "Sanity check failed - unknown domain answer (%lld)"
+ "Succesfully updated domain"
+ "Updating domain failed with error code %{public}d"
+ "UseCaseNotDisabled"
+ "bootUUID"
+ "currentOrchestrationMode"
+ "desiredOrchestrationModeIfEnabled"
+ "fromCurrentBootSession"
+ "kern.bootsessionuuid"
+ "linwoodEverAvailable"
- "<%@: %p; isAvailable: %@; siriLocale: %@; desiredOrchestrationMode: %@; unavailabilityReasons: %@>"
- "Error fetching Linwood eligibility: %{public}d"
- "Linwood eligibility not implemented yet"
- "SOSiriAvailability {\n  isAvailable: %@\n  siriLocale: %@\n  desiredOrchestrationMode: %@\n  unavailabilityReasons: %@\n}"
- "Sanity check failed - unknown Linwood availability (%lld)"
- "Succesfully updated Linwood eligibility"
- "Updating Linwood eligibility failed with error code %{public}d"
```

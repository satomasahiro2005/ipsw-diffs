## SiriKitFlow

> `/System/Library/PrivateFrameworks/SiriKitFlow.framework/SiriKitFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65082c` | `0x651a7c` | **`+0x1250`** |
| `__TEXT.__oslogstring` | `0x24ac7` | `0x24bf7` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x3a668` | `0x3a780` | **`+0x118`** |
| `__DATA_DIRTY.__data` | `0xa0b8` | `0xa198` | **`+0xe0`** |
| `__DATA.__data` | `0xc658` | `0xc588` | **`-0xd0`** |
| `__TEXT.__const` | `0x31350` | `0x313d0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x3a978` | `0x3a9e0` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x1bf48` | `0x1bfa8` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x189d0` | `0x18a08` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xed04` | `0xed30` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x112b1` | `0x112d9` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2bd8` | `0x2bd0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1bb0` | `0x1bb8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x10bc` | `0x10c4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2bf4` | `0x2bf8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x2f20` | `0x2f24` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3605.14.1.0.0
+3605.15.1.1.2

-  Functions: 40665
-  Symbols:   6459
-  CStrings:  4055
+  Functions: 40685
+  Symbols:   6463
+  CStrings:  4058
Symbols:
+ _symbolic Say______pG 11SiriKitFlow27ConfirmationResponseParsingP
+ _symbolic _____ 11SiriKitFlow33ChainedConfirmationResponseParserV
+ _symbolic _____ 11SiriKitFlow34OnDeviceConfirmationResponseParserV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 11SiriKitFlow27ConfirmationResponseParsingP
CStrings:
+ "EAC: execute() after completion; the result is already settled"
+ "HomePodSpeechProfileCheckFlow: Apple TV has no per-user ASR personalization, so no speech profile is required: PASS"
+ "OnDeviceConfirmationResponseParser: USO parse carries no accepted/rejected/cancelled dialog act"
+ "OnDeviceConfirmationResponseParser: no on-device confirmation in %s"
+ "PAC: execute() after completion; settling the result"
- "EAC: invoking execute() on a flow that has already completed!?"
- "PAC: invoking execute() on a flow that has already completed!?"
```

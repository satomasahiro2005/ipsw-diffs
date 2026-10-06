## SiriAnalytics

> `/System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11111c` | `0x1150c4` | **`+0x3fa8`** |
| `__TEXT.__eh_frame` | `0xb6ac` | `0xba2c` | **`+0x380`** |
| `__AUTH_CONST.__const` | `0x8a00` | `0x8c20` | **`+0x220`** |
| `__DATA.__bss` | `0xe110` | `0xe290` | **`+0x180`** |
| `__TEXT.__cstring` | `0x3e1d` | `0x3f5c` | **`+0x13f`** |
| `__TEXT.__oslogstring` | `0x3b9b` | `0x3cd5` | **`+0x13a`** |
| `__TEXT.__unwind_info` | `0x5c30` | `0x5d60` | **`+0x130`** |
| `__TEXT.__const` | `0xb640` | `0xb760` | **`+0x120`** |
| `__TEXT.__swift5_capture` | `0x1b04` | `0x1bb0` | **`+0xac`** |
| `__DATA_CONST.__const` | `0xff0` | `0x1068` | **`+0x78`** |
| `__DATA_DIRTY.__objc_data` | `0x2bb8` | `0x2c08` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x21e0` | `0x2228` | **`+0x48`** |
| `__DATA.__data` | `0x25f8` | `0x2638` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x2c14` | `0x2c54` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x3998` | `0x39d0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x2d0` | `0x304` | **`+0x34`** |
| `__TEXT.__swift_as_cont` | `0x814` | `0x848` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0x21dd` | `0x220d` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x6ac0` | `0x6aa0` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x38da` | `0x38fa` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x14a0` | `0x14b8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1758` | `0x1768` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x4450` | `0x4460` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x3c4` | `0x3d4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x448` | `0x458` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x7a8` | `0x7b4` | **`+0xc`** |
| `__DATA.__common` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x41c` | `0x420` | **`+0x4`** |

### Other Changes

```diff

-3605.29.1.0.0
+3605.33.1.0.0

-  Functions: 7942
-  Symbols:   3463
-  CStrings:  692
+  Functions: 8018
+  Symbols:   3481
+  CStrings:  706
Symbols:
+ -[AssistantSiriAnalyticsService handler:ensureActiveClockWithCompletion:]
+ -[SiriAnalyticsSensitiveConditionsObservers pollAllObservers]
+ -[SiriAnalyticsWhiteRose ensureActiveClockWithCompletion:]
+ -[SiriAnalyticsXPCConnection _ensureActiveClockWithCompletion:]
+ -[SiriAnalyticsXPCConnection ensureActiveClockWithCompletion:]
+ -[SiriAnalyticsXPCConnectionHandler ensureActiveClockWithCompletion:]
+ GCC_except_table100
+ GCC_except_table169
+ GCC_except_table173
+ GCC_except_table181
+ GCC_except_table329
+ GCC_except_table332
+ GCC_except_table339
+ GCC_except_table346
+ GCC_except_table353
+ GCC_except_table378
+ GCC_except_table385
+ GCC_except_table392
+ GCC_except_table398
+ GCC_except_table404
+ GCC_except_table411
+ GCC_except_table418
+ GCC_except_table83
+ GCC_except_table84
+ ___58-[SiriAnalyticsWhiteRose ensureActiveClockWithCompletion:]_block_invoke
+ ___58-[SiriAnalyticsWhiteRose ensureActiveClockWithCompletion:]_block_invoke_2
+ ___61-[SiriAnalyticsSensitiveConditionsObservers pollAllObservers]_block_invoke
+ ___62-[SiriAnalyticsXPCConnection ensureActiveClockWithCompletion:]_block_invoke
+ ___63-[SiriAnalyticsXPCConnection _ensureActiveClockWithCompletion:]_block_invoke
+ ___63-[SiriAnalyticsXPCConnection _ensureActiveClockWithCompletion:]_block_invoke_2
+ ___69-[SiriAnalyticsXPCConnectionHandler ensureActiveClockWithCompletion:]_block_invoke
+ ___73-[AssistantSiriAnalyticsService handler:ensureActiveClockWithCompletion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e32_v16?0"SiriAnalyticsRootClock"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"NSUUID"8"NSError"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40bs48w_e28_v24?0"NSUUID"8"NSError"16ls32l8w48l8s40l8
+ _associated conformance 13SiriAnalytics16RuntimeXPCClientC10ClockErrorOSHAASQ
+ _symbolic ScCy___________pG 10Foundation4UUIDV s5ErrorP
+ _symbolic _____ 13SiriAnalytics16RuntimeXPCClientC10ClockErrorO
- -[SiriAnalyticsSensitiveConditionsObservers pollAllObserversWithCompletion:]
- GCC_except_table168
- GCC_except_table172
- GCC_except_table180
- GCC_except_table325
- GCC_except_table328
- GCC_except_table335
- GCC_except_table342
- GCC_except_table367
- GCC_except_table374
- GCC_except_table381
- GCC_except_table387
- GCC_except_table393
- GCC_except_table400
- GCC_except_table407
- GCC_except_table80
- GCC_except_table81
- GCC_except_table98
- ___76-[SiriAnalyticsSensitiveConditionsObservers pollAllObserversWithCompletion:]_block_invoke
- ___76-[SiriAnalyticsSensitiveConditionsObservers pollAllObserversWithCompletion:]_block_invoke_2
CStrings:
+ "%s Ensured active clock: %@"
+ "%s Ensured active clock: %@ for connection:%@"
+ "%s Ensuring active clock"
+ "%s Ensuring active logical clock for connection: %@"
+ "%s Failed to ensure active logical clock due to %@"
+ "%s polling completed: %@"
+ "%s polling started: %@"
+ "-[AssistantSiriAnalyticsService handler:ensureActiveClockWithCompletion:]"
+ "-[AssistantSiriAnalyticsService handler:ensureActiveClockWithCompletion:]_block_invoke"
+ "-[SiriAnalyticsSensitiveConditionsObservers pollAllObservers]_block_invoke"
+ "-[SiriAnalyticsXPCConnection _ensureActiveClockWithCompletion:]"
+ "-[SiriAnalyticsXPCConnection _ensureActiveClockWithCompletion:]_block_invoke"
+ "Clearing stream and clockId"
+ "Direct staging with clockId: %s"
+ "ensureActiveClock()"
- "-[SiriAnalyticsSensitiveConditionsObservers pollAllObserversWithCompletion:]_block_invoke"
```

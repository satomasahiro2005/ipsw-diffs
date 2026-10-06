## SiriInference

> `/System/Library/PrivateFrameworks/SiriInference.framework/SiriInference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x309e20` | `0x30ae4c` | **`+0x102c`** |
| `__DATA_DIRTY.__data` | `0x8b20` | `0x9050` | **`+0x530`** |
| `__TEXT.__eh_frame` | `0x125dc` | `0x12204` | **`-0x3d8`** |
| `__AUTH.__data` | `0x48c8` | `0x4540` | **`-0x388`** |
| `__DATA.__bss` | `0x2e220` | `0x2df20` | **`-0x300`** |
| `__DATA_DIRTY.__bss` | `0x9300` | `0x9600` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x12d40` | `0x12fc0` | **`+0x280`** |
| `__DATA.__data` | `0x4d20` | `0x4b50` | **`-0x1d0`** |
| `__AUTH_CONST.__const` | `0x27f78` | `0x28090` | **`+0x118`** |
| `__AUTH.__objc_data` | `0x628` | `0x588` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x940` | `0x9e0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xab78` | `0xaad8` | **`-0xa0`** |
| `__TEXT.__swift5_capture` | `0x5814` | `0x5854` | **`+0x40`** |
| `__DATA.__common` | `0x128` | `0xf0` | **`-0x38`** |
| `__DATA_DIRTY.__common` | `0x2a8` | `0x2e0` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d78` | `0x1d98` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2f68` | `0x2f78` | **`+0x10`** |
| `__TEXT.__const` | `0x25bb0` | `0x25bc0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0xa6d0` | `0xa6e0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x8b92` | `0x8ba2` | **`+0x10`** |

### Other Changes

```diff

-3600.34.6.0.0
+3600.34.11.0.0

-  Functions: 19863
-  Symbols:   4949
-  CStrings:  3173
+  Functions: 19905
+  Symbols:   4957
+  CStrings:  3179
Symbols:
+ _OUTLINED_FUNCTION_235
+ _OUTLINED_FUNCTION_236
+ _OUTLINED_FUNCTION_237
+ _OUTLINED_FUNCTION_238
+ _OUTLINED_FUNCTION_239
+ _OUTLINED_FUNCTION_240
+ ___swift_closure_destructor.445Tm
+ ___swift_closure_destructor.547Tm
+ _swift_release_x10
+ _symbolic _____y_____SgG s23_ContiguousArrayStorageC 13SiriInference8DateTimeC0G0C
- ___swift_closure_destructor.434Tm
- ___swift_closure_destructor.536Tm
CStrings:
+ "CalendarComponentConstraintSolver: mapped negative weekday ordinal %ld to ordinal %ld of %ld occurrences"
+ "CommsAppResolutionTrainingLogEmitter#emitLogInternal: Failed to derive inferenceId from requestUUID, skipping"
+ "CommsAppResolutionTrainingLogEmitter#emitLogInternal: No streamUUID passed in and could not resolve requestUUID from Biome, skipping"
+ "CommsAppResolutionTrainingLogEmitter#emitLogInternal: No streamUUID passed in, derived from requestUUID via Biome"
+ "CommsAppResolutionTrainingLogEmitter#emitRequestLink: Failed to create SISchemaRequestLink"
+ "CommsAppResolutionTrainingLogEmitter#emitRequestLink: RequestLink emitted"
+ "CommsAppResolutionTrainingLogEmitter: event: %@"
- "CommsAppResolutionTrainingLogEmitter#emitLog No streamUUID passed in"
```

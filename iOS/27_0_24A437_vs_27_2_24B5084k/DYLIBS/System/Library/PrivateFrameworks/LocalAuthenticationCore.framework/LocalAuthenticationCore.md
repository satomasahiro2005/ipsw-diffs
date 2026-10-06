## LocalAuthenticationCore

> `/System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/LocalAuthenticationCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x195984` | `0x196e28` | **`+0x14a4`** |
| `__AUTH_CONST.__objc_const` | `0x595b0` | `0x59880` | **`+0x2d0`** |
| `__AUTH_CONST.__cfstring` | `0x76c0` | `0x77e0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x109d8` | `0x10a98` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x8998` | `0x8a48` | **`+0xb0`** |
| `__AUTH.__data` | `0x24b0` | `0x2558` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0xd410` | `0xd4b0` | **`+0xa0`** |
| `__TEXT.__const` | `0xae4c` | `0xaed4` | **`+0x88`** |
| `__AUTH.__objc_data` | `0x76c0` | `0x7730` | **`+0x70`** |
| `__DATA.__data` | `0x7730` | `0x7798` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x6b00` | `0x6b58` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x1ad0` | `0x1b20` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xd28` | `0xd70` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x49f0` | `0x4a20` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1790` | `0x17c0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xb0c5` | `0xb0f5` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2eb8` | `0x2ee0` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x282c` | `0x2848` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x40f8` | `0x410a` | **`+0x12`** |
| `__AUTH_CONST.__auth_got` | `0x1578` | `0x1588` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8ac` | `0x8b4` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc28` | `0xc30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x528` | `0x530` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x444` | `0x448` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x2c0` | `0x2c4` | **`+0x4`** |

### Other Changes

```diff

-2319.0.63.0.0
+2319.40.29.0.0

-  Functions: 10894
-  Symbols:   21968
-  CStrings:  3123
+  Functions: 10929
+  Symbols:   22035
+  CStrings:  3132
Symbols:
+ -[LACDTOLostModeProviderAKAdapter _analyticsOutcomeForError:]
+ -[LACDTOLostModeProviderAKAdapter initWithWorkQueue:deviceInfo:telemetry:]
+ -[LACDTOTelemetryReporter .cxx_destruct]
+ -[LACDTOTelemetryReporter initWithAnalyticsReporter:]
+ -[LACDTOTelemetryReporter sendLostModeQueryResult:lost:confirmed:durationMs:]
+ -[LACDTOTelemetryReporter sendRatchetConfigAnomaly:secondsSinceBoot:]
+ -[LACFlags featureFlagLightweightTouchIDEnabled]
+ _$s23LocalAuthenticationCore18LACContinuousClockV16startMeasurements8DurationVycyFAFycfU_Tm
+ _$s23LocalAuthenticationCore18LACContinuousClockVMaTm
+ _$s23LocalAuthenticationCore18LACContinuousClockVMrTm
+ _$s23LocalAuthenticationCore18LACContinuousClockVWObTm
+ _$s23LocalAuthenticationCore18LACSuspendingClockV16startMeasurements8DurationVycyF
+ _$s23LocalAuthenticationCore18LACSuspendingClockV16startMeasurements8DurationVycyFAFycfU_
+ _$s23LocalAuthenticationCore18LACSuspendingClockV16startMeasurements8DurationVycyFAFycfU_TA
+ _$s23LocalAuthenticationCore18LACSuspendingClockV16startMeasurements8DurationVycyFAFycfU_TATm
+ _$s23LocalAuthenticationCore18LACSuspendingClockVAA8LACClockA2aDP16startMeasurements8DurationVycyFTW
+ _$s23LocalAuthenticationCore18LACSuspendingClockVAA8LACClockAAMc
+ _$s23LocalAuthenticationCore18LACSuspendingClockVAA8LACClockAAWP
+ _$s23LocalAuthenticationCore18LACSuspendingClockVACycfC
+ _$s23LocalAuthenticationCore18LACSuspendingClockVMF
+ _$s23LocalAuthenticationCore18LACSuspendingClockVMa
+ _$s23LocalAuthenticationCore18LACSuspendingClockVMf
+ _$s23LocalAuthenticationCore18LACSuspendingClockVMl
+ _$s23LocalAuthenticationCore18LACSuspendingClockVMn
+ _$s23LocalAuthenticationCore18LACSuspendingClockVMr
+ _$s23LocalAuthenticationCore18LACSuspendingClockVN
+ _$s23LocalAuthenticationCore18LACSuspendingClockVWOb
+ _$s23LocalAuthenticationCore18LACSuspendingClockVWOc
+ _$s23LocalAuthenticationCore18LACSuspendingClockVWV
+ _$s23LocalAuthenticationCore18LACSuspendingClockVwet
+ _$s23LocalAuthenticationCore18LACSuspendingClockVwst
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreE11readElapsed33_E1BC965FF3CDA4CADCD474FFAAE20AE2LLs8DurationVycvpWvd
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreE19elapsedMillisecondsSivg
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreE19elapsedMillisecondsSivgTo
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreE19elapsedMillisecondsSivpMV
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreE5clock33_E1BC965FF3CDA4CADCD474FFAAE20AE2LLAC18LACSuspendingClockVvpZ
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreE5clock33_E1BC965FF3CDA4CADCD474FFAAE20AE2LL_WZ
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreE5clock33_E1BC965FF3CDA4CADCD474FFAAE20AE2LL_Wz
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreEABycfC
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreEABycfc
+ _$sSo12LACStopwatchC23LocalAuthenticationCoreEABycfcTo
+ _$sSo12LACStopwatchCML
+ _$sSo12LACStopwatchCMa
+ _$sSo12LACStopwatchCfETo
+ _$ss15SuspendingClockV3nowAB7InstantVvg
+ _$ss15SuspendingClockV7InstantV8duration2tos8DurationVAD_tF
+ _$ss15SuspendingClockV7InstantVMa
+ _$ss15SuspendingClockV7InstantVMn
+ _$ss15SuspendingClockVABycfC
+ _$ss15SuspendingClockVMa
+ _$ss15SuspendingClockVMn
+ _LACDTOAnalyticsRatchetConfigAnomalyReasonForLength
+ _OBJC_CLASS_$_LACStopwatch
+ _OBJC_IVAR_$_LACDTOLostModeProviderAKAdapter._telemetry
+ _OBJC_IVAR_$_LACDTOTelemetryReporter._analyticsReporter
+ _OBJC_METACLASS_$_LACStopwatch
+ __DATA_LACStopwatch
+ __INSTANCE_METHODS_LACStopwatch
+ __IVARS_LACStopwatch
+ __METACLASS_DATA_LACStopwatch
+ __OBJC_$_INSTANCE_VARIABLES_LACDTOTelemetryReporter
+ __PROPERTIES_LACStopwatch
+ ___block_descriptor_56_e8_32s40bs48w_e33_v16?0"LACBackgroundTaskResult"8lw48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40bs48w_e41_v24?0"LACDTOLostModeState"8"NSError"16ls32l8w48l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___der_key_state_abs_last_mesa_auth
+ ___der_key_state_abs_last_mesa_unlock
+ ___der_key_state_abs_last_passcode_auth
+ ___der_key_state_abs_last_passcode_unlock
+ ___der_key_state_abs_lock_time
+ ___swift_get_extra_inhabitant_indexTm
+ ___swift_store_extra_inhabitant_indexTm
+ _der_key_state_abs_last_mesa_auth
+ _der_key_state_abs_last_mesa_unlock
+ _der_key_state_abs_last_passcode_auth
+ _der_key_state_abs_last_passcode_unlock
+ _der_key_state_abs_lock_time
+ _symbolic _____ 23LocalAuthenticationCore18LACSuspendingClockV
+ _symbolic _____ s15SuspendingClockV
+ _symbolic _____ s15SuspendingClockV7InstantV
- -[LACDTOLostModeProviderAKAdapter initWithWorkQueue:deviceInfo:]
- _$s23LocalAuthenticationCore18LACContinuousClockV16startMeasurements8DurationVycyFAFycfU_
- _$s23LocalAuthenticationCore18LACContinuousClockVWOb
- _$s23LocalAuthenticationCore18LACContinuousClockVWOc
- ___118-[LACDTOTelemetryReporter sendRatchetEvaluationResult:ratchetOperationAbandoned:ratchetStateBefore:ratchetStateAfter:]_block_invoke
- ___146-[LACDTOTelemetryReporter sendFeatureEnablementResult:strictModeEnabled:extendedPolicyProtectionEnabled:source:isAutoEnablement:success:liveness:]_block_invoke
- ___50-[LACDTOTelemetryReporter sendSecurityDelayEvent:]_block_invoke
- ___52-[LACDTOTelemetryReporter sendSecurityDelayUIEvent:]_block_invoke
- ___66-[LACDTOTelemetryReporter sendAutoEnablementCheckResult:liveness:]_block_invoke
- ___66-[LACDTOTelemetryReporter sendCollapseEvaluationResult:mechanism:]_block_invoke
- ___block_descriptor_40_e8_32s_e19_"NSDictionary"8?0ls32l8
- ___block_descriptor_48_e8_32bs40w_e41_v24?0"LACDTOLostModeState"8"NSError"16lw40l8s32l8
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
CStrings:
+ "Device list request failed"
+ "Ratchet config-and-status payload anomaly (reason=%ld, secondsSinceBoot=%ld)"
+ "TouchIDSpinner"
+ "com.apple.LocalAuthentication.DTO.LostModeQueryResult"
+ "com.apple.LocalAuthentication.DTO.RatchetConfigAnomaly"
+ "confirmed"
+ "durationMs"
+ "lost"
+ "outcome"
+ "reason"
+ "secondsSinceBoot"
- "@\"NSDictionary\"8@?0"
- "Sent event: %s, payload: %@"
```

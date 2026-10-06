## libsystem_sanitizers.dylib

> `/usr/lib/system/libsystem_sanitizers.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d44` | `0x7bc8` | **`-0x17c`** |

### Other Changes

```text
Functions:
~ __ZNK6config3env6Parser10getSettingILm34EbLm3EEET0_RAT__KcS3_RAT1__KNS1_7SettingIS3_EE : 144 -> 136
~ __ZNK6config3env6Parser10getSettingILm30EbLm3EEET0_RAT__KcS3_RAT1__KNS1_7SettingIS3_EE : 144 -> 136
~ __ZNK6config3env6Parser10getSettingILm27ENS0_16AllocationTracesELm4EEET0_RAT__KcS4_RAT1__KNS1_7SettingIS4_EE : 144 -> 136
~ __ZNK6config3env6Parser10getSettingILm48EbLm3EEET0_RAT__KcS3_RAT1__KNS1_7SettingIS3_EE : 144 -> 136
~ __ZNK6config3env6Parser10getSettingILm37EbLm3EEET0_RAT__KcS3_RAT1__KNS1_7SettingIS3_EE : 144 -> 136
~ __ZNK6config3env6Parser10getSettingILm18ENS0_7AddressELm2EEET0_RAT__KcS4_RAT1__KNS1_7SettingIS4_EE : 144 -> 136
~ __ZNK6config3env6Parser10getSettingILm36EbLm3EEET0_RAT__KcS3_RAT1__KNS1_7SettingIS3_EE : 144 -> 136
~ ___asan_locate_address : 184 -> 164
~ ___asan_get_alloc_stack : 208 -> 224
~ ___asan_get_free_stack : 208 -> 224
~ __ZNK4asan19GlobalsRegistryImpl12getGlobalVarEm : 88 -> 120
~ __ZZN4asan14initGlobalVarsEP6ShadowPNS_15GlobalsRegistryEEN3$_08__invokeEPK11mach_headerl : 208 -> 212
~ __ZN4asan15ReportGenerator8StackVar5parseERPKc : 200 -> 212
~ __ZN4asan11reportErrorENS_9RegistersENS_12MemoryAccessE : 1072 -> 1060
~ __ZNK10ASanShadow16regionIsPoisonedEmm : 256 -> 268
~ __ZN13bounds_safety14SoftTrapLoggerINS_22OSFaultWithPayloadImplEE10should_logEPv : 376 -> 372
~ __ZN13bounds_safety7PCCacheILi2EE3addEPv : 104 -> 100
~ __ZN6config3env6Parser11getTrialValILm34EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm30EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm19EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm27EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm39EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm44EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm18EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm36EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm37EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm31EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm32EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ __ZN6config3env6Parser11getTrialValILm48EEEPKcS4_RAT__S3_RA128_c : 224 -> 196
~ _sanitizers_diagnose_memory_error : 804 -> 812
~ __ZN5trace5DepotILm65536ELm64ELm8EN4hash7Murmur2EXadL_Z15backtrace_asyncEEE11insertTraceEPmm : 360 -> 356
~ __ZN5trace5DepotILm524288ELm64ELm8EN4hash7Murmur2EXadL_Z15backtrace_asyncEEE11insertTraceEPmm : 364 -> 360
~ __ZN9libmalloc12MallocLoggerIXadL_ZL7onAllocmmmEEXadL_ZL9onDeallocmmEEXadL_ZN9mach_timeL9hasPassedEyEEE10loggerFuncEjmmmmj : 2996 -> 2964
~ __ZNK5trace9ExtractorINS_5DepotILm524288ELm64ELm8EN4hash7Murmur2EXadL_Z15backtrace_asyncEEEENS_13AllocationMapILm1048576EXadL_ZNS3_11hashPointerEmEEEEE14retrieveTracesERK14AllocationInfoR24sanitizers_stack_trace_tSC_ : 836 -> 828
```

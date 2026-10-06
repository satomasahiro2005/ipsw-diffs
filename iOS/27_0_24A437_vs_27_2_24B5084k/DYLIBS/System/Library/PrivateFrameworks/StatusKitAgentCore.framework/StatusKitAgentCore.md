## StatusKitAgentCore

> `/System/Library/PrivateFrameworks/StatusKitAgentCore.framework/StatusKitAgentCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd5f0` | `0x1be30c` | **`+0xd1c`** |
| `__TEXT.__oslogstring` | `0x192d6` | `0x19416` | **`+0x140`** |
| `__TEXT.__cstring` | `0x96dc` | `0x977c` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x9d40` | `0x9d98` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0xe90` | `0xecc` | **`+0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x11740` | `0x11770` | **`+0x30`** |
| `__TEXT.__const` | `0x5c08` | `0x5c28` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb0f0` | `0xb110` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5cb8` | `0x5cd8` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x1f48` | `0x1f38` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1608` | `0x1600` | **`-0x8`** |

### Other Changes

```diff

-154.100.1.0.0
+154.200.11.0.0

-  Functions: 7782
-  Symbols:   14200
-  CStrings:  2603
+  Functions: 7790
+  Symbols:   14201
+  CStrings:  2611
Symbols:
+ +[SKAMessagingProvider _isBlastdoorEnabledForServiceIdentifier:]
+ GCC_except_table3
+ GCC_except_table64
+ _$s18StatusKitAgentCore11SKACALoggerC20_checkErrorThreshold5event5error6client5clockyAA10SKACAEventO_So7NSErrorCAA14SKACALogClientCSgAA8SKAClock_ptFZTf4nnnen_nAA0Q7WrapperCys15ContinuousClockVG_Tg5Tf4nnnnd_n
+ _$s18StatusKitAgentCore14SKACALogClientC11descriptionSSvg
+ _$s18StatusKitAgentCore14SKACALogClientC11descriptionSSvgTo
+ _$s18StatusKitAgentCore14SKACALogClientC4hashSivg
+ _$s18StatusKitAgentCore14SKACALogClientC4hashSivgTo
+ _$s18StatusKitAgentCore14SKACALogClientC7isEqualySbypSgF
+ _$s18StatusKitAgentCore14SKACALogClientC7isEqualySbypSgFTo
+ _$sypSgWOcTm
+ __PROPERTIES_SKACALogClient
+ ___block_descriptor_64_e8_32s40s48bs_e49_v24?0"SKAUnpackedProtobufResponse"8"NSError"16ls32l8s40l8s48l8
+ ___logger_block_invoke
- +[SKAMessagingProvider _isBlastdoorEnabledForService:]
- +[SKAStatusServer sharedInstance]
- _$s18StatusKitAgentCore11SKACALogKeyO_yptWOc
- _$s18StatusKitAgentCore11SKACALoggerC20_checkErrorThreshold5event5error6client5clockyAA10SKACAEventO_So7NSErrorCAA14SKACALogClientCSgAA8SKAClock_ptFZTf4nnnen_nAA0Q7WrapperCys15ContinuousClockVG_Tt3g5
- _$s18StatusKitAgentCore14SKACALogClientCSgMR
- _$s18StatusKitAgentCore14SKACALogClientCSgMd
- _$sSGsE4next10upperBoundqd__qd___ts17FixedWidthIntegerRd__SURd__lFqd__s27SystemRandomNumberGeneratorVqd__AERszsACRd__SURd__r__lIetMnlr_Tpq5s6UInt64V_Tg5
- _$sSo8SKHandleCMaTm
- ___33+[SKAStatusServer sharedInstance]_block_invoke
- ___block_descriptor_56_e8_32s40bs_e49_v24?0"SKAUnpackedProtobufResponse"8"NSError"16ls32l8s40l8
- _sharedInstance.instance
- _sharedInstance.onceToken
- _swift_stdlib_random
CStrings:
+ "Delay for %s: using=%ss, next=%ss (max: %ss)"
+ "Not attempting repair for channel %{public}@ because of rate limit, reason: %@"
+ "Poll response checkpoint is 0, treating as an empty channel and applying state on channel %{public}@"
+ "Present device read from database has a missing required field: %@"
+ "Repeated error threshold (%ld within %lds) reached for %s; reporting to AutoBugCapture"
+ "SKADatabaseCoreDataAdapters"
+ "com.apple.StatusKit.presence.subscribeRegistration"
+ "com.apple.StatusKit.status.provisionedPayloads"
+ "provisionedPayloadCount"
- "Delay for %s: using=%ss (before jitter: %ss), next=%ss (max: %ss)"
```

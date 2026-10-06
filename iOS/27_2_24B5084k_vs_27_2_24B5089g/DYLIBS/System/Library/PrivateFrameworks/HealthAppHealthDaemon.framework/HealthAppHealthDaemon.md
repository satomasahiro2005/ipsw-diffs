## HealthAppHealthDaemon

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemon.framework/HealthAppHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48908` | `0x492f8` | **`+0x9f0`** |
| `__TEXT.__oslogstring` | `0x23d4` | `0x2514` | **`+0x140`** |
| `__DATA_DIRTY.__data` | `0x918` | `0xa48` | **`+0x130`** |
| `__AUTH.__objc_data` | `0x470` | `0x368` | **`-0x108`** |
| `__DATA_DIRTY.__objc_data` | `0xb88` | `0xc90` | **`+0x108`** |
| `__AUTH_CONST.__objc_const` | `0x3090` | `0x3190` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x14d8` | `0x15c8` | **`+0xf0`** |
| `__DATA.__data` | `0x1210` | `0x1120` | **`-0xf0`** |
| `__TEXT.__objc_methlist` | `0x1e14` | `0x1ea0` | **`+0x8c`** |
| `__TEXT.__swift5_typeref` | `0x820` | `0x8ac` | **`+0x8c`** |
| `__DATA.__bss` | `0x1e90` | `0x1e10` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0xd80` | `0xe00` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x148` | `0x1b8` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x640` | `0x690` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1430` | `0x1480` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1430` | `0x1478` | **`+0x48`** |
| `__TEXT.__cstring` | `0x1775` | `0x17b5` | **`+0x40`** |
| `__AUTH.__data` | `0xe8` | `0xc0` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0x114` | `0x138` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x10a8` | `0x10c8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x868` | `0x878` | **`+0x10`** |
| `__TEXT.__const` | `0x21c0` | `0x21d0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x688` | `0x698` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x11c` | `0x124` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x150` | `0x158` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 1639
-  Symbols:   1485
-  CStrings:  311
+  Functions: 1670
+  Symbols:   1511
+  CStrings:  316
Symbols:
+ -[HDHealthAppDailyAnalyticsEvent _gatherPluginPayloadIHAGated:]
+ -[HDHealthAppDailyAnalyticsEvent _mergePluginPayload:into:]
+ -[HDHealthAppDailyAnalyticsEvent _payloadGatherer]
+ -[HDHealthAppDailyAnalyticsEvent pluginPayloadTimeout]
+ -[HDHealthAppDailyAnalyticsEvent setPluginPayloadTimeout:]
+ -[HDHealthAppDailyAnalyticsEvent setUnitTest_payloadGatherer:]
+ -[HDHealthAppDailyAnalyticsEvent unitTest_payloadGatherer]
+ GCC_except_table15
+ GCC_except_table8
+ _OBJC_IVAR_$_HDHealthAppDailyAnalyticsEvent._pluginPayloadTimeout
+ _OBJC_IVAR_$_HDHealthAppDailyAnalyticsEvent._unitTest_payloadGatherer
+ __PROTOCOLS__TtC21HealthAppHealthDaemon40HealthAppHealthDaemonOrchestrationClient
+ __PROTOCOL_INSTANCE_METHODS__TtP21HealthAppHealthDaemon39HealthAppDailyAnalyticsPayloadGathering_
+ __PROTOCOL_METHOD_TYPES__TtP21HealthAppHealthDaemon39HealthAppDailyAnalyticsPayloadGathering_
+ __PROTOCOL_PROTOCOLS__TtP21HealthAppHealthDaemon39HealthAppDailyAnalyticsPayloadGathering_
+ __PROTOCOL__TtP21HealthAppHealthDaemon39HealthAppDailyAnalyticsPayloadGathering_
+ ___59-[HDHealthAppDailyAnalyticsEvent _mergePluginPayload:into:]_block_invoke
+ ___63-[HDHealthAppDailyAnalyticsEvent _gatherPluginPayloadIHAGated:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e25_v32?0"NSString"816^B24ls32l8s40l8
+ ___block_descriptor_57_e8_32s40s48r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r48l8s40l8
+ _objc_retainBlock
+ _swift_retain_x23
+ _symbolic $s09HealthAppA6Daemon0aB30DailyAnalyticsPayloadGatheringP
+ _symbolic SDySSypGSg______pSgIeghgg_ s5ErrorP
+ _symbolic So12NSDictionaryCSgSo7NSErrorCSgIeyBhyy_
+ _symbolic _____XDXMT 09HealthAppA6Daemon0abaC19OrchestrationClientC
CStrings:
+ "%{public}@: Failed to gather plugin daily analytics payload (ihaGated=%{public}d) with error %{public}@"
+ "%{public}@: Plugin daily analytics payload key %{public}@ is already present in the event payload; dropping the plugin value."
+ "%{public}@: Timed out gathering plugin daily analytics payload (ihaGated=%{public}d)."
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
+ "v32@?0@\"NSString\"8@16^B24"
```

## UsageTrackingAgent

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTrackingAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72840` | `0x73794` | **`+0xf54`** |
| `__TEXT.__objc_methname` | `0x5b01` | `0x5eb1` | **`+0x3b0`** |
| `__TEXT.__oslogstring` | `0x5726` | `0x5a86` | **`+0x360`** |
| `__TEXT.__objc_stubs` | `0x4560` | `0x47e0` | **`+0x280`** |
| `__TEXT.__objc_methlist` | `0x11b8` | `0x1290` | **`+0xd8`** |
| `__DATA.__objc_const` | `0x3070` | `0x3140` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x1448` | `0x14e8` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x17c4` | `0x1864` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x810` | `0x860` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1048` | `0x1090` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0xd80` | `0xdc0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x84` | `0x94` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2400` | `0x2410` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1210` | `0x1218` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x2838` | `0x2840` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1148` | `0x1150` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-403.0.0.0.0
+405.0.0.0.0

-  Functions: 1484
-  Symbols:   952
-  CStrings:  1439
+  Functions: 1512
+  Symbols:   954
+  CStrings:  1480
Symbols:
+ _$s14DeviceActivity12EventStreamsV36currentIntelligenceBundleIdentifiersSo12NSOrderedSetCvgZ
+ _BMIntelligenceUsageIdentifier
CStrings:
+ "Checking budgets for current intelligence bundle identifiers"
+ "Could not start tracking budgeted intelligence usage because an error occurred while fetching applications: %{public}@"
+ "Could not start tracking budgeted intelligence usage because an error occurred while fetching categories: %{public}@"
+ "Error fetching budgets for intelligence bundle identifiers: %{public}@, %{public}@"
+ "Intelligence"
+ "Intelligence alarm fired, checking budgets for current intelligence bundle identifiers"
+ "Intelligence alarm fired, no intelligence in use so not checking budgets for current intelligence"
+ "Intelligence registration fired, checking budgets for current intelligence bundle identifiers"
+ "Intelligence registration fired, no intelligence in use so not checking budgets for current intelligence"
+ "Intelligence tombstone event did fire"
+ "No intelligence in use so not checking budgets for current intelligence"
+ "T@\"BMBiomeScheduler\",R,V_intelligenceScheduler"
+ "T@\"BMBiomeScheduler\",R,V_intelligenceTombstoneScheduler"
+ "T@\"BPSDrivableSink\",&,V_intelligenceTombstoneSubscription"
+ "T@\"BPSSink\",&,V_intelligenceSubscription"
+ "Usage"
+ "_checkBudgetStatusForIntelligenceBundleIdentifiers:"
+ "_didCollectLocalActivityForIntelligenceBundleIdentifiers:"
+ "_intelligenceAlarmDidFire"
+ "_intelligenceRegistrationDidFire"
+ "_intelligenceScheduler"
+ "_intelligenceSubscription"
+ "_intelligenceTombstoneEventDidFire"
+ "_intelligenceTombstoneScheduler"
+ "_intelligenceTombstoneSubscription"
+ "_subscribeForApplicationTombstones"
+ "_subscribeForIntelligenceTombstones"
+ "_subscribeForIntelligenceUsage"
+ "_subscribeForNowPlayingTombstones"
+ "_subscribeForVideoTombstones"
+ "_subscribeForWebDomainTombstones"
+ "com.apple.UsageTrackingAgent.alarm.intelligence"
+ "com.apple.UsageTrackingAgent.intelligence-scheduler"
+ "com.apple.UsageTrackingAgent.intelligence-tombstone-scheduler"
+ "currentIntelligenceBundleIdentifiers"
+ "intelligenceScheduler"
+ "intelligenceSubscription"
+ "intelligenceTombstoneScheduler"
+ "intelligenceTombstoneSubscription"
+ "setIntelligenceSubscription:"
+ "setIntelligenceTombstoneSubscription:"
```

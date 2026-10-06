## PersistentConnection

> `/System/Library/PrivateFrameworks/PersistentConnection.framework/PersistentConnection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21388` | `0x21d48` | **`+0x9c0`** |
| `__TEXT.__oslogstring` | `0x4868` | `0x4e5d` | **`+0x5f5`** |
| `__AUTH_CONST.__objc_const` | `0x6eb0` | `0x6f18` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x1fb8` | `0x1fe8` | **`+0x30`** |
| `__TEXT.__const` | `0x250` | `0x278` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xc70` | `0xc88` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1b3a` | `0x1b4e` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x10a0` | `0x10a8` | **`+0x8`** |

### Other Changes

```diff

-562.100.1.0.0
+562.200.1.0.0

-  Functions: 807
-  Symbols:   1622
-  CStrings:  549
+  Functions: 814
+  Symbols:   1629
+  CStrings:  557
Symbols:
+ -[PCInterfaceMonitor logDetailedState]
+ -[PCInterfaceUsabilityMonitor logDetailedState]
+ -[PCNonCellularUsabilityMonitor logDetailedState]
+ -[PCPersistentInterfaceManager logDetailedState]
+ -[PCWWANUsabilityMonitor logDetailedState]
+ ___42-[PCWWANUsabilityMonitor logDetailedState]_block_invoke
+ ___49-[PCNonCellularUsabilityMonitor logDetailedState]_block_invoke
CStrings:
+ "PCInterfaceMonitor state dump: internal:nil"
+ "PCInterfaceUsabilityMonitor[%{public}@] state dump: usable:%{BOOL}d historicallyUsable:%{BOOL}d pathSatisfied:%{BOOL}d linkQuality:%{public}@(%d) constraint:%ld interface:%{public}s(%u) delegateInterface:%{public}s(%u) pathEvaluator:%{public}s lqDynamicStore:%{public}s lqKey:%{public}@ trackUsability:%{BOOL}d offTransitions:%lu/%lu within:%.0fs newestOffTransitionAge:%.1fs"
+ "PCNonCellularUsabilityMonitor state dump: usable:%{BOOL}d historicallyUsable:%{BOOL}d demoOverrideInterface:%{public}@ linkQuality:%{public}@(%d) previousLinkQuality:%d trackUsability:%{BOOL}d offThreshold:%lu trackedInterval:%.0fs"
+ "PCPersistentInterfaceManager state dump: isWWANInterfaceUp:%{BOOL}d recomputed:%{BOOL}d isWWANInterfaceDataActive:%{BOOL}d hasWWANStatusIndicator:%{BOOL}d avoidWWANOnCall:%{BOOL}d inCallOverrideTimer:%{BOOL}d isInCall:%{BOOL}d isWiFiUsable:%{BOOL}d wwanInterfaceName:%{public}@ isWWANInterfaceSuspended:%{BOOL}d isWWANInterfaceActivationPermitted:%{BOOL}d interfaceAssertion:%{public}s isWWANInterfaceInProlongedHighPowerState:%{BOOL}d isPowerStateDetectionSupported:%{BOOL}d ctIsWWANInHomeCountry:%{BOOL}d ctClient:%{public}s dataSimSlotID:%d lastActivationAge:%.0fs"
+ "PCWWANUsabilityMonitor state dump: usable:%{BOOL}d historicallyUsable:%{BOOL}d interfaceMonitor:%{public}s wwanContextID:%ld isInCall:%{BOOL}d isInHighPowerState:%{BOOL}d currentRAT:%d dataBearerSoMask:%u ctClient:%{public}s dataSimSlotID:%d trackUsability:%{BOOL}d offThreshold:%lu trackedInterval:%.0fs"
+ "held"
+ "live"
+ "nil"
+ "nil - no PDP context"
- "EmperorPenguin"
```

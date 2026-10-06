## MatterPlugin

> `/System/Library/PrivateFrameworks/MatterPlugin.framework/MatterPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4916c` | `0x4a158` | **`+0xfec`** |
| `__AUTH_CONST.__objc_intobj` | `0x438` | `0x990` | **`+0x558`** |
| `__TEXT.__oslogstring` | `0x5aff` | `0x5db9` | **`+0x2ba`** |
| `__DATA_CONST.__objc_arraydata` | `0x40` | `0x288` | **`+0x248`** |
| `__TEXT.__gcc_except_tab` | `0x1878` | `0x1a90` | **`+0x218`** |
| `__AUTH_CONST.__objc_const` | `0x6ae8` | `0x6c08` | **`+0x120`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x60` | `0x108` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x493c` | `0x49cc` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x990` | `0xa08` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cf8` | `0x1d68` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x11e0` | `0x1218` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x394` | `0x3ac` | **`+0x18`** |
| `__DATA.__bss` | `0x90` | `0xa0` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-81.0.0.0.0
+84.0.0.0.0

-  Functions: 1685
-  Symbols:   2723
-  CStrings:  617
+  Functions: 1702
+  Symbols:   2747
+  CStrings:  622
Symbols:
+ -[MTRPluginLocalClient setTemporarilyRetainedDevices:]
+ -[MTRPluginLocalClient temporarilyRetainedDevices]
+ -[MTRPluginResidentClientSession attributeReportCoalesceTimers]
+ -[MTRPluginResidentClientSession attributeReportSendSafetyTimeoutSeconds]
+ -[MTRPluginResidentClientSession inFlightAttributeReportSendCount]
+ -[MTRPluginResidentClientSession invalidated]
+ -[MTRPluginResidentClientSession pendingAttributeReports]
+ -[MTRPluginResidentClientSession setAttributeReportCoalesceTimers:]
+ -[MTRPluginResidentClientSession setAttributeReportSendSafetyTimeoutSeconds:]
+ -[MTRPluginResidentClientSession setInFlightAttributeReportSendCount:]
+ -[MTRPluginResidentClientSession setInvalidated:]
+ -[MTRPluginResidentClientSession setPendingAttributeReports:]
+ GCC_except_table42
+ _MTRPluginResidentClientSession_NoisyAttributesByCluster.sNoisyAttributesByCluster
+ _MTRPluginResidentClientSession_NoisyAttributesByCluster.sOnce
+ _OBJC_IVAR_$_MTRPluginLocalClient._temporarilyRetainedDevices
+ _OBJC_IVAR_$_MTRPluginResidentClientSession._attributeReportCoalesceTimers
+ _OBJC_IVAR_$_MTRPluginResidentClientSession._attributeReportSendSafetyTimeoutSeconds
+ _OBJC_IVAR_$_MTRPluginResidentClientSession._inFlightAttributeReportSendCount
+ _OBJC_IVAR_$_MTRPluginResidentClientSession._invalidated
+ _OBJC_IVAR_$_MTRPluginResidentClientSession._pendingAttributeReports
+ ___MTRPluginResidentClientSession_NoisyAttributesByCluster_block_invoke
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e8_v16?08ls32l8r40l8
+ ___block_descriptor_64_e8_32s40r48w_e5_v8?0lw48l8r40l8s32l8
- GCC_except_table48
CStrings:
+ "%@ device %@ attribute report relay safety-timeout fired (no IDS response in %.1fs); decremented in-flight to %lu"
+ "%@ device %@ receivedAttributeReport: %lu entries had no MTRAttributePathKey, passed through unfiltered"
+ "%@ device %@ receivedAttributeReport: dropped %lu Changes-Omitted-Quality diagnostic entries (GeneralDiagnostics / Thread / WiFi / Ethernet NetworkDiagnostics / PowerSource / TimeSynchronization / OperationalCredentials)"
+ "%@ device %@ receivedAttributeReport: missing nodeID, cannot coalesce"
+ "%@ device %@ receivedAttributeReport: nothing to relay after filtering"
+ "%@ device %@ relaying coalesced attribute report (%lu entries, %lu in-flight)"
+ "%@ device nodeID %@ receivedAttributeReport: dropping coalesced report - in-flight relay count %lu >= cap %lu"
- "\v"
- "%@ device %@ receivedAttributeReport %@, sending to remote controller"
```

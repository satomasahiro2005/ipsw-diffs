## wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34a9c4` | `0x34ce54` | **`+0x2490`** |
| `__TEXT.__gcc_except_tab` | `0x2a448` | `0x2a88c` | **`+0x444`** |
| `__TEXT.__const` | `0x17ea3` | `0x18113` | **`+0x270`** |
| `__TEXT.__objc_methname` | `0x1892c` | `0x18b2c` | **`+0x200`** |
| `__DATA_CONST.__cfstring` | `0x7320` | `0x74e0` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x2ed42` | `0x2eef2` | **`+0x1b0`** |
| `__DATA_CONST.__const` | `0x173a8` | `0x17528` | **`+0x180`** |
| `__TEXT.__objc_stubs` | `0xfae0` | `0xfc60` | **`+0x180`** |
| `__TEXT.__cstring` | `0x15ecb` | `0x1602b` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x10470` | `0x10548` | **`+0xd8`** |
| `__DATA.__objc_const` | `0x145b0` | `0x14670` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x78a4` | `0x7924` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x4528` | `0x4588` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x13e8` | `0x1410` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xa1c` | `0xa2c` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 14426
-  Symbols:   2058
-  CStrings:  10385
+  Functions: 14476
+  Symbols:   2063
+  CStrings:  10427
Symbols:
+ __ZN3abm15kRFSensingValueE
+ __ZN3abm15kTunerModeStateE
+ __ZN3abm17kRFSensingCommandE
+ __ZN3abm27kEventRFSensingStateChangedE
+ __ZN3abm34kRFSensingSubCommandQueryTunerModeE
CStrings:
+ "350.1~193"
+ "C20@0:8C16"
+ "DailyWirelessUsageMetric:No valid tuner mode state, skipping"
+ "DailyWirelessUsageMetric:Received RF sensing state dict %@"
+ "DailyWirelessUsageMetric:Received tuner mode state update: %u"
+ "DailyWirelessUsageMetric:handleDeviceStateChangedTo: numDeviceStateChanges %lu, numDeviceStateChangesConnected %lu"
+ "Failed to fetch initial RF sensing state, unsupported"
+ "Incorrect key for RF sensing in response, fixing"
+ "Received RF sensing state: %s"
+ "TB,N,V_isDeviceStateAvailable"
+ "TC,N,V_deviceState"
+ "TQ,N,V_numDeviceStateChanges"
+ "TQ,N,V_numDeviceStateChangesConnected"
+ "_deviceState"
+ "_isDeviceStateAvailable"
+ "_numDeviceStateChanges"
+ "_numDeviceStateChangesConnected"
+ "deviceState"
+ "deviceStateA"
+ "deviceStateAConnected"
+ "deviceStateB"
+ "deviceStateBConnected"
+ "deviceStateUnknown"
+ "deviceStateUnknownConnected"
+ "duration_device_state_a"
+ "duration_device_state_a_connected"
+ "duration_device_state_b"
+ "duration_device_state_b_connected"
+ "duration_device_usage_unknown"
+ "duration_device_usage_unknown_connected"
+ "handleABMRFSensingStateChangedWithState:"
+ "isDeviceStateAvailable"
+ "numDeviceStateChanges"
+ "numDeviceStateChangesConnected"
+ "num_device_usage_switches"
+ "num_device_usage_switches_connected"
+ "sarStateToWISDeviceUsageState:"
+ "setDeviceState:"
+ "setIsDeviceStateAvailable:"
+ "setNumDeviceStateChanges:"
+ "setNumDeviceStateChangesConnected:"
+ "unsignedShortValue"
+ "updateDeviceStateDurationTrackers"
- "350.1~198"
```

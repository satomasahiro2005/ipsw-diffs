## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x2ee35` | `0x2f525` | **`+0x6f0`** |
| `__TEXT.__text` | `0x17c858` | `0x17cc18` | **`+0x3c0`** |
| `__DATA.__objc_const` | `0x34450` | `0x34690` | **`+0x240`** |
| `__TEXT.__cstring` | `0x10886` | `0x10aa6` | **`+0x220`** |
| `__DATA_CONST.__cfstring` | `0x11ca0` | `0x11e20` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x1346c` | `0x135b4` | **`+0x148`** |
| `__DATA.__objc_selrefs` | `0x9ea0` | `0x9f90` | **`+0xf0`** |
| `__TEXT.__objc_stubs` | `0x1b540` | `0x1b600` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x17379` | `0x173b9` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x1654` | `0x1684` | **`+0x30`** |
| `__TEXT.__const` | `0x1588` | `0x1598` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2467.40.47.0.0
+2467.40.49.0.0

-  Functions: 8447
+  Functions: 8474

-  CStrings:  12585
+  CStrings:  12652
CStrings:
+ "IdleStack thermal max (start/run): low %d/%d, medium %d/%d, high %d/%d"
+ "PolicyDeviceActivityIdleStackHighBlockRunOnEarlyThermal"
+ "PolicyDeviceActivityIdleStackHighBlockStartOnEarlyThermal"
+ "PolicyDeviceActivityIdleStackLowBlockRunOnEarlyThermal"
+ "PolicyDeviceActivityIdleStackLowBlockStartOnEarlyThermal"
+ "PolicyDeviceActivityIdleStackMediumBlockRunOnEarlyThermal"
+ "PolicyDeviceActivityIdleStackMediumBlockStartOnEarlyThermal"
+ "PolicyThermalIdleStackHighMaxAllowableToRun"
+ "PolicyThermalIdleStackHighMaxAllowableToStart"
+ "PolicyThermalIdleStackLowMaxAllowableToRun"
+ "PolicyThermalIdleStackLowMaxAllowableToStart"
+ "PolicyThermalIdleStackMediumMaxAllowableToRun"
+ "PolicyThermalIdleStackMediumMaxAllowableToStart"
+ "TB,N,V_idleStackHighBlockRunOnEarlyThermal"
+ "TB,N,V_idleStackHighBlockStartOnEarlyThermal"
+ "TB,N,V_idleStackLowBlockRunOnEarlyThermal"
+ "TB,N,V_idleStackLowBlockStartOnEarlyThermal"
+ "TB,N,V_idleStackMediumBlockRunOnEarlyThermal"
+ "TB,N,V_idleStackMediumBlockStartOnEarlyThermal"
+ "Ti,N,V_idleStackHighRunMax"
+ "Ti,N,V_idleStackHighStartMax"
+ "Ti,N,V_idleStackLowRunMax"
+ "Ti,N,V_idleStackLowStartMax"
+ "Ti,N,V_idleStackMediumRunMax"
+ "Ti,N,V_idleStackMediumStartMax"
+ "_idleStackHighBlockRunOnEarlyThermal"
+ "_idleStackHighBlockStartOnEarlyThermal"
+ "_idleStackHighRunMax"
+ "_idleStackHighStartMax"
+ "_idleStackLowBlockRunOnEarlyThermal"
+ "_idleStackLowBlockStartOnEarlyThermal"
+ "_idleStackLowRunMax"
+ "_idleStackLowStartMax"
+ "_idleStackMediumBlockRunOnEarlyThermal"
+ "_idleStackMediumBlockStartOnEarlyThermal"
+ "_idleStackMediumRunMax"
+ "_idleStackMediumStartMax"
+ "activityTransferSize == %lu"
+ "boolTrialFactor:default:"
+ "idleStackHighBlockRunOnEarlyThermal"
+ "idleStackHighBlockStartOnEarlyThermal"
+ "idleStackHighRunMax"
+ "idleStackHighStartMax"
+ "idleStackLowBlockRunOnEarlyThermal"
+ "idleStackLowBlockStartOnEarlyThermal"
+ "idleStackLowRunMax"
+ "idleStackLowStartMax"
+ "idleStackMaxAllowableForActivity:"
+ "idleStackMediumBlockRunOnEarlyThermal"
+ "idleStackMediumBlockStartOnEarlyThermal"
+ "idleStackMediumRunMax"
+ "idleStackMediumStartMax"
+ "isHighPriorityIdleStackTask"
+ "isMediumPriorityIdleStackTask"
+ "rawTrialLevelForFactor:"
+ "setIdleStackHighBlockRunOnEarlyThermal:"
+ "setIdleStackHighBlockStartOnEarlyThermal:"
+ "setIdleStackHighRunMax:"
+ "setIdleStackHighStartMax:"
+ "setIdleStackLowBlockRunOnEarlyThermal:"
+ "setIdleStackLowBlockStartOnEarlyThermal:"
+ "setIdleStackLowRunMax:"
+ "setIdleStackLowStartMax:"
+ "setIdleStackMediumBlockRunOnEarlyThermal:"
+ "setIdleStackMediumBlockStartOnEarlyThermal:"
+ "setIdleStackMediumRunMax:"
+ "setIdleStackMediumStartMax:"
+ "shouldBlockIdleStackActivityOnEarlyThermal:withContext:"
+ "\x87"
- " Size %lu upload:%d, [wifiLQM] Required=%ld, Observed=%ld, [cellLQM] Required=%ld Observed=%ld\n"
- "W"
```

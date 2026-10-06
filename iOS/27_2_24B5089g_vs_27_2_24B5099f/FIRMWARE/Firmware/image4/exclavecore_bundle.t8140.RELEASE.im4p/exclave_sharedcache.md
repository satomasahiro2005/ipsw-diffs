## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xed86c4` | `0xedf674` | **`+0x6fb0`** |
| `__TEXT.__cstring` | `0xb20c1` | `0xb27d1` | **`+0x710`** |
| `__TEXT.__eh_frame` | `0x82c6c` | `0x83060` | **`+0x3f4`** |
| `__DATA.__const` | `0x13dca8` | `0x13e010` | **`+0x368`** |
| `__TEXT.__const` | `0x1ee2f4` | `0x1ee634` | **`+0x340`** |
| `__TEXT.__swift5_reflstr` | `0x4ba88` | `0x4bc68` | **`+0x1e0`** |
| `__TEXT.__swift5_fieldmd` | `0x7b3a0` | `0x7b534` | **`+0x194`** |
| `__DATA.__data` | `0x5c988` | `0x5cb10` | **`+0x188`** |
| `__TEXT.__constg_swiftt` | `0x732dc` | `0x73460` | **`+0x184`** |
| `__DATA.__ENDPOINTS` | `0x1bbd0` | `0x1bcd7` | **`+0x107`** |
| `__TEXT.__swift5_typeref` | `0x31506` | `0x31596` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x7085` | `0x70e5` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0x2f58` | `0x2f94` | **`+0x3c`** |
| `__TEXT.__swift_as_ret` | `0x1880` | `0x18a4` | **`+0x24`** |
| `__TEXT.__objc_methtype` | `0x556` | `0x576` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x379c` | `0x37bc` | **`+0x20`** |
| `__DATA.__auth_ptr` | `0x7e40` | `0x7e58` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xfe80` | `0xfe98` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xc054` | `0xc06c` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x792c` | `0x7940` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x1670` | `0x1684` | **`+0x14`** |
| `__DATA.__bss` | `0x24f70` | `0x24f80` | **`+0x10`** |
| `__DATA.__common` | `0x4901` | `0x48f1` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-1777.40.28.0.2
-  Functions: 53102
+1777.40.34.0.0
+  Functions: 53183

-  CStrings:  16512
+  CStrings:  16558
CStrings:
+ " DisplayManager is not configured!"
+ " but a session is already active!"
+ " but startTimestampUS is nil!"
+ " deferrals(hwBusy)="
+ " deferrals(pipelineBusy)="
+ " for Storage exclave"
+ " gateEarlyRejects="
+ " gateExemptedBuffers="
+ " is not a valid integer: "
+ " opted into prefers-waiting-through-sleep, blocking: "
+ " parked request(s) with mappers disabled; they will submit against unmapped DART state"
+ " parking until sleep cycle completes, parked: "
+ " rejected before IO prep. SleepCycle: "
+ "), deferring DART unmap"
+ "430.40.6"
+ ": panicking to prevent MTE tag brute-forcing"
+ "; using no-op control"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:45:47 PDT 2026; root:AppleImage4_exclavecore-374~19125/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.102.1"
+ "Applying MTE backoff of "
+ "Build Date: Mon Sep 28 22:24:15 PDT 2026"
+ "Builtin.Borrow is not supported in runtime type lookup"
+ "Bundle metadata for "
+ "Conclave MTE tag check fault: esr="
+ "Could not start storage: "
+ "ENABLED via driver opt-in"
+ "Empty value of bundle metadata "
+ "ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:45:47 PDT 2026; root:AppleImage4_exclavecore-374~19125/ExclaveImage4/RELEASE_ARM64E"
+ "In-flight HW or pipeline requests present (pipeline: "
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
+ "Invalid log level "
+ "MTE tag check fault #"
+ "Mon Sep 28 23:19:40 PDT 2026"
+ "Park-through-sleep "
+ "ParkThroughSleep enabled: "
+ "SEP power control wired but SoC type is unknown; disabling SEP reset lockout"
+ "SEP reset lockout not supported on "
+ "SEP reset protection "
+ "SEP reset protection enabled: "
+ "SEP reset protection requested but no SEP control is wired on this part"
+ "SetLogLevelFromBundle()"
+ "SleepCycle parked requests: "
+ "SleepCycle pipeline count: "
+ "SleepCycle totals: parks="
+ "Storage not ready"
+ "StorageExclaveComponent/XRTBundleResources.swift"
+ "[SecureM3Handler] ERROR firmware load failed"
+ "[SecureM3Handler] MCPU power "
+ "[SecureM3Handler] MCPU power %ld -> %ld"
+ "disabled (default)"
+ "getBundleMetadata(_:)"
+ "ns before launch"
+ "ns before next launch"
+ "releasePipelineReservation not called with workLoop Gate held!"
+ "sharedmem_framemap_getPhysicalAddress"
+ "sharedmem_framemap_setMapped_delta"
+ "takePipelineReservation called twice for request "
+ "takePipelineReservation not called with workLoop Gate held!"
+ "v24@?0{sharedmem_pagerange=QQ}8"
+ "waitForSleepCycleCompletion not called with workLoop Gate held!"
+ "writeFileInternal(client:catInfo:name:offset:length:encrypted:inputBuffer:)"
- " opted into prefers-waiting-through-sleep; option accepted but not yet implemented"
- "430.40.5"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Sat Sep 12 05:10:17 PDT 2026; root:AppleImage4_exclavecore-374~18509/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.101.1"
- "Build Date: Sat Sep 12 04:43:50 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Sat Sep 12 05:10:17 PDT 2026; root:AppleImage4_exclavecore-374~18509/ExclaveImage4/RELEASE_ARM64E"
- "In-flight HW requests present, deferring DART unmap"
- "Initialized count set to greater than specified capacity."
- "Tue Sep 15 12:41:23 PDT 2026"
- "[SecurePairingCoreComponent]: Could not start storage: "
- "localmap_map(%zx): localmap() remap with changed PA (%llx != %llx)\n"
- "sharedmem_framemap_getPhysicalAddresses"
- "sharedmem_framemap_setMapped"
- "storage not ready"
- "writeFileInternal(client:catInfo:name:offset:length:encrypted:)"
```

## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5eb94c` | `0x5f2020` | **`+0x66d4`** |
| `__TEXT.__cstring` | `0x4f671` | `0x4ffc1` | **`+0x950`** |
| `__DATA.__data` | `0x18770` | `0x18de0` | **`+0x670`** |
| `__TEXT.__constg_swiftt` | `0x27f0c` | `0x28564` | **`+0x658`** |
| `__DATA.__const` | `0x3d678` | `0x3dac8` | **`+0x450`** |
| `__TEXT.__const` | `0x1228c4` | `0x122d14` | **`+0x450`** |
| `__TEXT.__swift5_fieldmd` | `0x1c18c` | `0x1c4d4` | **`+0x348`** |
| `__TEXT.__swift5_reflstr` | `0x120a8` | `0x12398` | **`+0x2f0`** |
| `__TEXT.__swift5_typeref` | `0x14190` | `0x1439a` | **`+0x20a`** |
| `__TEXT.__eh_frame` | `0x35268` | `0x35448` | **`+0x1e0`** |
| `__DATA.__auth_ptr` | `0x2368` | `0x2420` | **`+0xb8`** |
| `__TEXT.__swift5_proto` | `0x3d98` | `0x3ddc` | **`+0x44`** |
| `__TEXT.__swift5_types` | `0x2490` | `0x24cc` | **`+0x3c`** |
| `__TEXT.__swift5_assocty` | `0x7b48` | `0x7b78` | **`+0x30`** |
| `__TEXT.__swift5_mpenum` | `0x3b4` | `0x3d4` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x15b8` | `0x15cc` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x978` | `0x988` | **`+0x10`** |

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
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 22985
+  Functions: 23028

-  CStrings:  7310
+  CStrings:  7363
CStrings:
+ "  Device state = "
+ " never came on during display wake allowance policy. "
+ " not allowed while strobe alternative indicator is active"
+ ", cutting sensor access"
+ "Alternative Indicator Triggered = "
+ "DEFAULT INDICATOR MACHINE: "
+ "Default display changed policy canceled ("
+ "Default display changed policy resolved @ GLTB "
+ "Default display changed policy violated @ GLTB "
+ "Display POST Failed = "
+ "Display issue detected: continuing to use health checks until microphone is turned on"
+ "Display issue detected: switching to strobe alternative indicator"
+ "Display power policy canceled ("
+ "Display power policy resolved @ GLTB "
+ "Display power policy violated @ GLTB "
+ "Enforcing new MOT @ GLTB "
+ "Failed to end strobe"
+ "Failed to end strobe after MOT met"
+ "Failed to get Medina state"
+ "Failed to notify corerepaird of strobe start"
+ "Failed to prepare strobe"
+ "Failed to prepare strobe before MOT was met"
+ "Failed to update strobe before MOT was met"
+ "Failed to update strobe power state"
+ "Failed to update strobe power state to "
+ "Force TCON Threshold Exceeded = "
+ "INDICATOR: CAM -> OFF ("
+ "INDICATOR: MIC -> OFF ("
+ "INDICATOR: STROBE ALT -> OFF"
+ "INDICATOR: STROBE ALT -> ON"
+ "INDICATOR: STROBE ALT -> PENDING STOP"
+ "INDICATOR: STROBE ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE ALT -> PREPARE"
+ "INDICATOR: STROBE FLASH ALT -> DONE"
+ "INDICATOR: STROBE FLASH ALT -> OFF"
+ "INDICATOR: STROBE FLASH ALT -> ON"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE FLASH ALT -> PREPARE"
+ "Invalid start state for strobe flash machine (pending: "
+ "MedinaStateAOP/MedinaStateAOP_Swift.swift"
+ "Notified corerepaird of strobe start"
+ "Starting default display changed policy @ GLTB "
+ "Starting display power policy @ GLTB "
+ "VIOLATION resolved: "
+ "display powered off"
+ "display-post-failed"
+ "display-post-failed-1"
+ "ignored in Medina state B"
+ "invalid rawValue for MedinaStateCode: "
+ "octopus_fang_alt_indicator"
+ "octopus_force_alt_indicator"
+ "octopus_force_display_POST_failed"
+ "octopus_force_tcon_threshold_exceeded"
+ "octopus_no_fang_alt_indicator"
+ "policy-alt-indicator"
+ "unknown indicator"
- "[B] Start Siri dark wake policy"
- "[B] Start prox policy"
- "[B] Stop Siri dark wake policy"
- "[B] Stop prox policy"
```

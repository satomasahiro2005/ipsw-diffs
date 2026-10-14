## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8150.RELEASE.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe9c5e0` | `0xe9d9ac` | **`+0x13cc`** |
| `__TEXT.__cstring` | `0xb2081` | `0xb24d1` | **`+0x450`** |
| `__TEXT.__constg_swiftt` | `0x6f080` | `0x6f128` | **`+0xa8`** |
| `__DATA.__data` | `0x59fe0` | `0x5a070` | **`+0x90`** |
| `__TEXT.__const` | `0x1ba554` | `0x1ba5c4` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x6aa08` | `0x6aa5c` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0x44968` | `0x449a8` | **`+0x40`** |
| `__DATA.__const` | `0x106128` | `0x106140` | **`+0x18`** |
| `__DATA.__bss` | `0x24fe0` | `0x24ff0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x30720` | `0x30730` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x82fd4` | `0x82fdc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__auth_ptr`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1777.40.34.0.0
-  Functions: 50909
+1777.40.37.0.0
+  Functions: 50914

-  CStrings:  16514
+  CStrings:  16529
CStrings:
+ " lastVerdictAge="
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Thu Oct  8 00:11:07 PDT 2026; root:AppleImage4_exclavecore-374~19439/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.102.2"
+ "Build Date: Wed Oct  7 23:45:10 PDT 2026"
+ "ExclaveOS Image4 Framework Version 7.0.0: Thu Oct  8 00:11:07 PDT 2026; root:AppleImage4_exclavecore-374~19439/ExclaveImage4/RELEASE_ARM64E"
+ "ExclaveSISP-6.104"
+ "FaceLivelinessFull"
+ "PatchKeypointTracker"
+ "Start not allowed: camera disabled by EDT policy"
+ "Status not allowed: camera disabled by EDT policy"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/faceliveliness_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/facelivelinessfull_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/ODTL.framework/PhoneTracking/odtl/0/0/PatchKeypointTracker.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/ODTL.framework/PhoneTracking/odtl/ObjectDetector.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/Visage.framework/VGUnifiedLightingH5Models.bundle/img_to_sg_exclave_model.bundle/*.bundle/main/main_ane"
+ "Thu Oct  8 00:48:12 PDT 2026"
+ "[BrightnessCheck] NOT EVALUATED ("
+ "])\n  deviceStateDisplayWake: allowance="
+ "fpwm-frequency-hz"
+ "policy-sil-disable"
+ "sil-disable-config"
+ "sil-disable-offset"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:45:47 PDT 2026; root:AppleImage4_exclavecore-374~19125/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.102.1"
- "Build Date: Mon Sep 28 22:24:15 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:45:47 PDT 2026; root:AppleImage4_exclavecore-374~19125/ExclaveImage4/RELEASE_ARM64E"
- "ExclaveSISP-6.103"
- "Mon Sep 28 23:19:17 PDT 2026"
- "])\n  medinaStateDisplayWake: allowance="
```

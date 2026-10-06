## AlwaysOnExclavesDaemon

> `/System/Library/PrivateFrameworks/AlwaysOnExclavesDaemon.framework/AlwaysOnExclavesDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8534` | `0x8e4c` | **`+0x918`** |
| `__DATA.__bss` | `0x300` | `0x480` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x4df` | `0x64f` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0xc8` | `0x1b0` | **`+0xe8`** |
| `__TEXT.__const` | `0x4f0` | `0x5d0` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x2c8` | `0x380` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x757` | `0x707` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x1e8` | `0x220` | **`+0x38`** |
| `__DATA.__data` | `0x1c0` | `0x1f0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x152` | `0x182` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x10e` | `0x13a` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x540` | `0x568` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x36c` | `0x388` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x220` | `0x23c` | **`+0x1c`** |
| `__DATA_DIRTY.__data` | `0x3f0` | `0x400` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x14` | `0x24` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1c` | `0x28` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x28` | `0x2c` | **`+0x4`** |

### Other Changes

```diff

-60.0.0.0.1
+66.0.0.0.1

-  Functions: 152
-  Symbols:   214
-  CStrings:  70
+  Functions: 160
+  Symbols:   224
+  CStrings:  75
Symbols:
+ ___swift__destructor
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ _associated conformance 22AlwaysOnExclavesDaemon21WorkerThreadPoolErrorOSHAASQ
+ _objc_retain_x25
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_x10
+ _swift_retain_x24
+ _swift_retain_x27
+ _symbolic So8NSObjectCSg
+ _symbolic _____ 22AlwaysOnExclavesDaemon21WorkerThreadPoolErrorO
+ _symbolic _____ s5Int32V
+ _symbolic ______p s5ErrorP
- ___swift_destroy_boxed_opaque_existential_1
- _objc_release
- _swift_retain_x12
CStrings:
+ "%s: xpcService: the existing defaults for current boot: %@"
+ "(error %d): exclaves_aoe_enumerate_and_setup_services failed"
+ "(error %d): exclaves_aoe_enumerate_and_setup_services succeeded but returned zero services"
+ ", could not launch daemon"
+ "[Forwarder] Forwarding connection setup for serviceName: %s, serviceId: %llu"
+ "[XPCService] error: "
+ "[XPCService] the daemon does not have a conclave"
+ "[XPCService] the daemon is not enabled"
+ "conclave for %s is not present, daemon.launch() skipped"
- "): exclaves_aoe_enumerate_and_setup_services failed"
- "): exclaves_aoe_enumerate_and_setup_services succeeded but returned zero services"
- "[Forwarder] Forwarding connection setup"
- "conclave for %s is not present, daemon.start() skipped"
```

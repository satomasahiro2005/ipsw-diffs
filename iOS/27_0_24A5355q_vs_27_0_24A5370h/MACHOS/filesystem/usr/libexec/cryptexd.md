## cryptexd

> `/usr/libexec/cryptexd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68ce4` | `0x69110` | **`+0x42c`** |
| `__TEXT.__oslogstring` | `0xb30c` | `0xb37c` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x2c0` | `0x320` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x25c0` | `0x25f0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x5e63` | `0x5e3c` | **`-0x27`** |
| `__DATA_CONST.__auth_got` | `0x12f0` | `0x1308` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1210` | `0x1220` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__object_init`
- `__DATA_CONST.__subsystem`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-746.0.0.0.0
+757.0.0.0.0

-  Functions: 1556
-  Symbols:   2916
-  CStrings:  2223
+  Functions: 1555
+  Symbols:   2918
+  CStrings:  2227
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/DaemonServer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/Logger+init.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/NSLock+With.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/acm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/aks.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/amfi.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/apfs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/authinstall.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/bin_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cf-8188d6d4d72721ff60e4bddfbef76192.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/collation_map.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/darwin_version.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/event_server.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/fs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/hdi-d5b67ac863665ce45ee4c5dacf5b90d7.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/img4.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/img4_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/iokit.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/launch_util.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/launchd_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/path.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/proc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/protex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/python.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/quire.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/resource.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sandboxing.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_collation.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_mount.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_pipeline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_remote_service.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/usermanager.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/view.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/watchdog.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
+ GCC_except_table28
+ GCC_except_table33
+ ____codex_rpc_install_block_invoke
+ ____remote_service_install_cryptex_block_invoke
+ ___block_descriptor_105_e8_32s40s48s56r_e35_v36?0^{__CFError=}8i16i20i24i28i32ls32l8r56l8s40l8s48l8
+ ___codex_rpc_install_block_invoke
+ _objc_retain_x28
+ _xpc_connection_create_from_endpoint
+ _xpc_remote_connection_send_message
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/DaemonServer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/Logger+init.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/NSLock+With.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/acm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/aks.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/amfi.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/apfs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/authinstall.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/bin_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/cf-f627b7fe50e598d7d53f0cda51ce99c7.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/collation_map.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/cryptexd.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/darwin_version.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/event_server.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/fs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/hdi-e414ad021219a4b8c13987c6d6dc8e6d.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/img4.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/img4_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/iokit.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/launch_util.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/launchd_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/path.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/proc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/protex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/python.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/quire.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/resource.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sandboxing.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_collation.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_mount.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_pipeline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_remote_service.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/usermanager.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/view.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/watchdog.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
- GCC_except_table27
- GCC_except_table31
- _OUTLINED_FUNCTION_68
- _OUTLINED_FUNCTION_69
- _OUTLINED_FUNCTION_70
- ___block_descriptor_32_e33_v16?0"NSObject<OS_xpc_object>"8l
- ___block_descriptor_88_e8_32s40s48r_e35_v36?0^{__CFError=}8i16i20i24i28i32ls32l8r48l8s40l8
CStrings:
+ "%{public}s: Lost connection to client's install event handler"
+ "%{public}s: Unexpected message from client's install event handler"
+ "%{public}s: keybag unlocked; firing source"
+ "757"
+ "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Tue Jun 16 00:24:43 PDT 2026; root:libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E"
+ "Darwin Cryptex Manager Version 2.0.0: Tue Jun 16 00:24:43 PDT 2026; root:libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E"
+ "Fingerprint"
+ "Mountpoint"
+ "Notifying remote peer that this device is locked."
+ "SubMountDevice"
+ "enable-install-events"
- "%{public}s: broadcast install event %{darwin.errno}d"
- "%{public}s: keybag event; firing source: event = %#x"
- "746"
- "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Thu May 21 12:37:09 PDT 2026; root:libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "Darwin Cryptex Manager Version 2.0.0: Thu May 21 12:37:09 PDT 2026; root:libcryptex_executables-746~636/cryptexd/RELEASE_ARM64E"
```

## cryptexd

> `/usr/libexec/cryptexd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69110` | `0x69120` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x350` | `0x358` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__object_init`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-757.0.0.0.0
+761.0.1.0.0

-  Functions: 1555
+  Functions: 1556
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/DaemonServer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/Logger+init.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/NSLock+With.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/acm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/aks.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/amfi.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/apfs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/authinstall.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/bin_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/cf-b821b8ce2d91fec361995938167255c2.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/collation_map.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/cryptexd.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/darwin_version.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/event_server.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/fs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/hdi-3bcc9360cf9f664cdd17815ca8810639.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/img4.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/img4_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/iokit.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/launch_util.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/launchd_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/path.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/proc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/protex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/python.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/quire.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/resource.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sandboxing.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_collation.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_mount.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_pipeline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_remote_service.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/usermanager.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/view.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/watchdog.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/DaemonServer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/Logger+init.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/NSLock+With.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/acm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/aks.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/amfi.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/apfs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/authinstall.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/bin_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cf-8188d6d4d72721ff60e4bddfbef76192.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/collation_map.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/darwin_version.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/event_server.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/fs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/hdi-d5b67ac863665ce45ee4c5dacf5b90d7.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/img4.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/img4_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/iokit.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/launch_util.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/launchd_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/path.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/proc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/protex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/python.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/quire.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/resource.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sandboxing.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_collation.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_mount.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_pipeline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_remote_service.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/usermanager.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/view.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/watchdog.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
Functions:
~ _apfs_volume_delete : 552 -> 560
~ _proc_resolve : 2732 -> 2700
~ __codex_import_initial_prep : 1388 -> 1384
~ _hdi_copy_mounted : 1816 -> 1832
+ _OUTLINED_FUNCTION_57
~ _OUTLINED_FUNCTION_59 : 20 -> 12
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 704 -> 716
~ _LibCall_ACMKernDoubleClickNotify : 172 -> 180
~ _LibCall_ACMContextVerifyPolicyEx : 196 -> 192
~ _LibCall_ACMSecContextVerifyPolicyAndCopyRequirementEx : 200 -> 196
~ _LibCall_ACMContextLoadFromImage : 464 -> 460
~ _LibCall_ACMSecSetBuiltinBiometry : 164 -> 172
CStrings:
+ "761.0.1"
+ "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Sat Jun 27 00:49:05 PDT 2026; root:libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E"
+ "Darwin Cryptex Manager Version 2.0.0: Sat Jun 27 00:49:05 PDT 2026; root:libcryptex_executables-761.0.1~27/cryptexd/RELEASE_ARM64E"
- "757"
- "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Tue Jun 16 00:24:43 PDT 2026; root:libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E"
- "Darwin Cryptex Manager Version 2.0.0: Tue Jun 16 00:24:43 PDT 2026; root:libcryptex_executables-757~1388/cryptexd/RELEASE_ARM64E"
```

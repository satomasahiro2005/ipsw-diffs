## cryptexd

> `/usr/libexec/cryptexd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x691c8` | `0x6979c` | **`+0x5d4`** |
| `__TEXT.__oslogstring` | `0xb3cc` | `0xb4e7` | **`+0x11b`** |
| `__TEXT.__cstring` | `0x5e3c` | `0x5e6c` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1b4c` | `0x1b68` | **`+0x1c`** |
| `__TEXT.__auth_stubs` | `0x25f0` | `0x2600` | **`+0x10`** |
| `__TEXT.__const` | `0xcc0` | `0xcd0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1308` | `0x1310` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x358` | `0x360` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-761.0.15.0.0
+761.0.17.502.1

-  Symbols:   2918
-  CStrings:  2228
+  Symbols:   2920
+  CStrings:  2235
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/DaemonServer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/Logger+init.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/NSLock+With.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/acm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/aks.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/amfi.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/apfs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/authinstall.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/bin_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cf-cd331fe09da4188e2c0a99d05e8f89d7.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/collation_map.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/darwin_version.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/event_server.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/fs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/hdi-2e21c6098e5531deac33baa05f499d23.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/img4.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/img4_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/iokit.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/launch_util.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/launchd_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/path.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/proc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/protex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/python.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/quire.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/resource.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sandboxing.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_collation.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_mount.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_pipeline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_remote_service.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/usermanager.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/view.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/watchdog.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
+ __DefaultRuneLocale
+ ___maskrune
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/DaemonServer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/Logger+init.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/NSLock+With.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/acm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/aks.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/amfi.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/apfs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/authinstall.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/bin_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/cf-5c148c897bce16405f41683c4fb5ebd4.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/collation_map.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/cryptexd.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/darwin_version.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/event_server.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/fs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/hdi-3b4ff42000ad7a622c1a6f58b769f28d.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/img4.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/img4_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/iokit.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/launch_util.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/launchd_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/path.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/proc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/protex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/python.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/quire.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/resource.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sandboxing.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_collation.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_mount.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_pipeline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_remote_service.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/usermanager.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/view.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/watchdog.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
Functions:
~ ____remote_service_install_block_invoke : 1184 -> 2136
~ __quire_bootstrap_continue2 : 5096 -> 5480
~ _rpc_reply_with_cferr : 596 -> 688
~ _OUTLINED_FUNCTION_8 : 8 -> 12
~ _OUTLINED_FUNCTION_9 : 12 -> 28
~ _OUTLINED_FUNCTION_10 : 16 -> 8
~ _OUTLINED_FUNCTION_11 : 28 -> 16
~ _OUTLINED_FUNCTION_20 : 12 -> 20
~ _OUTLINED_FUNCTION_21 : 20 -> 12
~ _LibSer_SEPControl_Deserialize : 160 -> 200
~ _LibSer_SEPControlResponse_Deserialize : 64 -> 88
CStrings:
+ "%{public}s: empty jetsam properties variant: %{darwin.errno}d"
+ "%{public}s: invalid character '%c' in jetsam properties variant '%s': %{darwin.errno}d"
+ "761.0.17.502.1"
+ "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Tue Aug  4 23:57:03 PDT 2026; root:libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E"
+ "Darwin Cryptex Manager Version 2.0.0: Tue Aug  4 23:57:03 PDT 2026; root:libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E"
+ "_remote_service_install_cryptex"
+ "invalid auth value: %llu"
+ "invalid nonce-persistence value: %llu"
+ "invalid persistence value: %llu"
+ "no reply message to send: %{darwin.errno}d"
- "761.0.15"
- "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Fri Jul 10 23:30:38 PDT 2026; root:libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E"
- "Darwin Cryptex Manager Version 2.0.0: Fri Jul 10 23:30:38 PDT 2026; root:libcryptex_executables-761.0.15~17/cryptexd/RELEASE_ARM64E"
```

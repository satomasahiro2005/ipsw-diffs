## cryptexd

> `/usr/libexec/cryptexd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xcd0` | `0xcc0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x5e6c` | `0x5e5c` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-761.0.17.502.1
+761.2.1.0.0
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/DaemonServer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/Logger+init.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/NSLock+With.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/acm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/aks.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/amfi.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/apfs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/authinstall.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/bin_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/cf-2df578de5e5017ba84d9e5df72eabc0f.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/collation_map.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/cryptexd.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/darwin_version.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/event_server.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/fs.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/hdi-93201b126f90bf471fba5a0167a059f6.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/img4.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/img4_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/iokit.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/launch_util.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/launchd_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/path.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/proc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/protex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/python.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/quire.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/resource.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sandboxing.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sm.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_codex.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_collation.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_daemon.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_mount.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_pipeline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_remote_service.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_session.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/usermanager.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/view.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/watchdog.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/DaemonServer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/Logger+init.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/NSLock+With.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/acm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/aks.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/amfi.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/apfs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/authinstall.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/bin_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cf-cd331fe09da4188e2c0a99d05e8f89d7.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/collation_map.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd.swiftmodule
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd_objc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/cryptexd_vers.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/darwin_version.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/devmode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/dyld_shared_region.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/event_server.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/fs.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/hdi-2e21c6098e5531deac33baa05f499d23.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/img4.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/img4_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/iokit.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/launch_util.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/launchd_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/path.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/proc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/protex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/python.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/quire.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/resource.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/restricted_exec_mode_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sandboxing.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sm.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_codex.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_codex_xpc.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_collation.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_daemon.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_endpoint_lookup.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_mount.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_pipeline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_remote_service.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_session.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_upgrade_lock.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/sub_upgrade_trampoline.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/upgrade_sequencer.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/upgrade_sysctl.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/usermanager.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/view.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/watchdog.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/libcryptex_executables/install/TempContent/Objects/libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E/xpc_entitlements.o
CStrings:
+ "761.2.1"
+ "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Mon Aug 10 04:27:24 PDT 2026; root:libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E"
+ "Darwin Cryptex Manager Version 2.0.0: Mon Aug 10 04:27:24 PDT 2026; root:libcryptex_executables-761.2.1~27/cryptexd/RELEASE_ARM64E"
- "761.0.17.502.1"
- "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Tue Aug  4 23:57:03 PDT 2026; root:libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E"
- "Darwin Cryptex Manager Version 2.0.0: Tue Aug  4 23:57:03 PDT 2026; root:libcryptex_executables-761.0.17.502.1~2/cryptexd/RELEASE_ARM64E"
```

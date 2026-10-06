## softwareupdated

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Support/softwareupdated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b240` | `0x2ba48` | **`+0x808`** |
| `__DATA_CONST.__cfstring` | `0x9660` | `0x9d20` | **`+0x6c0`** |
| `__TEXT.__cstring` | `0xb66d` | `0xbcb6` | **`+0x649`** |
| `__DATA_CONST.__const` | `0x17d0` | `0x1978` | **`+0x1a8`** |
| `__DATA.__bss` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa10` | `0xa20` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2717.0.0.0.0
+2718.0.2.0.0

-  Functions: 830
-  Symbols:   2301
-  CStrings:  2599
+  Functions: 836
+  Symbols:   2309
+  CStrings:  2657
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-4e1279833aea10e74fdbfc26932a0f10.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-83263c96618a1efacaa59ffa50b136f8.o
+ _APFSExtendedSpaceInfo
+ ___msu_NVRAM_has_system_namespace_block_invoke
+ __get_space_info_uint64_off
+ _get_volume_space_info
+ _nvram_var_is_a_system_nvram_var
+ msu_NVRAM_has_system_namespace.onceToken
+ msu_NVRAM_has_system_namespace.supportsSystemNVRAM
+ nvram_var_is_a_system_nvram_var
+ nvram_var_is_a_system_nvram_var.systemNVRAMVars
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-0c80cd7ca0968eae472db6188f9f093a.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-2b4a293d7b1650dc3108bc546d2cd37d.o
- _APFSVolumeGetSpaceInfo
CStrings:
+ "%s: Deleting value of %s from common region\n\n"
+ "%s: Deleting value of %s from system nvram\n\n"
+ "%s: Failed to allocate name of system nvram key for %s\n\n"
+ "%s: Failed to delete %s from system nvram region\n\n"
+ "%s: Failed to delete value of %s from common region\n\n"
+ "%s: Failed to determine if nvram %s is a system nvram or not\n\n"
+ "%s: Failed to set key %@ in IO registry: %d\n"
+ "%s: Failed to set value for ota-uuid in the common region\n\n"
+ "%s: Failed to set value of %s in the system nvram region\n\n"
+ "%s: Got request to set/delete ota-uuid\n\n"
+ "%s: Reading value of %s from system nvram\n\n"
+ "%s: Setting value for ota-uuid to common region\n\n"
+ "%s: Skipping system nvram check for %s\n\n"
+ "%s: Unable to allocate name for system nvram variable\n\n"
+ "%s: Will read value of %s from common nvram region\n\n"
+ "%s: Writing value for %s to non system nvram %s\n\n"
+ "%s: Writing value for %s to system nvram\n\n"
+ "%s:%@"
+ "40A0DDD2-77F8-4392-B4A3-1E7304206516"
+ "APFSExtendedSpaceInfo(%s) failed: %d (%#x)\n"
+ "Attempting to delete variable %s\n\n"
+ "Failed to clear system nvram version of %s\n\n"
+ "IODTNVRAMVariables"
+ "IONameMatch"
+ "IOProviderClass"
+ "IS"
+ "Invalid argument passed to system\n"
+ "NOT"
+ "SystemAudioVolume"
+ "SystemAudioVolumeExtension"
+ "alt-boot-volume"
+ "auto-boot"
+ "boot-args"
+ "boot-breadcrumbs"
+ "boot-command"
+ "boot-volume"
+ "bootdelay"
+ "copy_nvram_variable_with_system_nvram_check"
+ "debug-uarts"
+ "fs_free"
+ "fs_used"
+ "iboot-failure-reason"
+ "iboot1-precommitted"
+ "msu_NVRAM_has_system_namespace: system namespace %s present\n\n"
+ "one-time-boot-command"
+ "options-system"
+ "ota-retry-enabled"
+ "ota-tolerated-disable"
+ "ramrod-kickstart-aces"
+ "recovery-boot-mode"
+ "recovery-breadcrumbs"
+ "restore-retry-enabled"
+ "restored-host-timeout"
+ "root-live-fs"
+ "set_nvram_object_with_system_nvram_check"
+ "since system nvram check was passed in as false\n"
+ "target-uuid"
+ "update-volume"
+ "upgrade-boot-volume"
+ "upgrade-fallback-boot-command"
+ "upgrade-manifest-hash"
+ "upgrade-retry"
- "%s: Deleted value %s\n\n"
- "APFSVolumeGetSpaceInfo for data volume failed with result:%d"
- "APFSVolumeGetSpaceInfo for preboot volume failed with result:%d"
- "APFSVolumeGetSpaceInfo for system volume failed with result:%d"
```

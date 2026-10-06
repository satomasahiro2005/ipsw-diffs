## enhancedloggingd

> `/usr/libexec/enhancedloggingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa75fc` | `0xab250` | **`+0x3c54`** |
| `__DATA_CONST.__const` | `0x9460` | `0x9e48` | **`+0x9e8`** |
| `__TEXT.__cstring` | `0x2c57` | `0x2e97` | **`+0x240`** |
| `__TEXT.__objc_stubs` | `0x30e0` | `0x3240` | **`+0x160`** |
| `__TEXT.__swift5_capture` | `0x29d4` | `0x2b34` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x45f1` | `0x4731` | **`+0x140`** |
| `__DATA.__data` | `0x29a8` | `0x2aa8` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x2f4c` | `0x3028` | **`+0xdc`** |
| `__TEXT.__const` | `0x55ac` | `0x566c` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x2c76` | `0x2d36` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x1c4b` | `0x1cc1` | **`+0x76`** |
| `__TEXT.__objc_methtype` | `0x100b` | `0x1080` | **`+0x75`** |
| `__TEXT.__swift5_reflstr` | `0x15a1` | `0x1601` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0xf58` | `0xfb0` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x1b60` | `0x1ba8` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x1200` | `0x1234` | **`+0x34`** |
| `__TEXT.__gcc_except_tab` | `0x31c` | `0x2e8` | **`-0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x1824` | `0x1858` | **`+0x34`** |
| `__TEXT.__objc_methlist` | `0x1230` | `0x1258` | **`+0x28`** |
| `__DATA.__objc_const` | `0x2470` | `0x2490` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2130` | `0x2150` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x10a8` | `0x10b8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x960` | `0x968` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x160` | `0x164` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-236.0.0.0.0
+240.0.0.502.1

-  Functions: 2854
-  Symbols:   954
-  CStrings:  1323
+  Functions: 2901
+  Symbols:   956
+  CStrings:  1357
Symbols:
+ _$s15EnhancedLogging12FileProgressV14completedBytess5Int64Vvg
+ _$s15EnhancedLogging12FileProgressVSEAAMc
+ _$s15EnhancedLogging12FileProgressVSeAAMc
+ _$s15EnhancedLogging16PromptDescriptorV10processingAA010ProcessingD0VSgvg
+ _$s15EnhancedLogging16PromptDescriptorV8templateAC8TemplateOvg
+ _NSURLIsDirectoryKey
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _objc_retain_x9
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "@\"NSURL\"16@?0@\"NSURL\"8"
+ "Failed to get resource value for %{public}@: %{public}@"
+ "[%{public}s] Finisher config: %{public}s"
+ "[%{public}s] Finisher config: <container: %{public}s; useDevelopmentEnvironment: %{bool,public}d; cloudKitData: %{public}s>"
+ "_uploadProgress"
+ "archiveAndAttachURL:sourceID:queueKey:healthStudyID:encryptor:progressHandler:"
+ "archiveFile:deleteOriginal:progressHandler:"
+ "backwardCompatibility"
+ "boolValue"
+ "cloudkitContainer"
+ "cloudkitUseDevelopmentEnvironment"
+ "compressFilesFromExtension:urls:progressHandler:"
+ "compressSessionFile:progressHandler:"
+ "connectivity_wifi"
+ "coreMotionAndLocation"
+ "getResourceValue:forKey:error:"
+ "healthregulatory"
+ "hid-sleep-respiration_rate"
+ "hid_accel_archive"
+ "hid_cycle_tracking"
+ "hid_heart_rate_coordinator"
+ "hid_hermit_phone"
+ "hid_hermit_watch"
+ "hid_nebula_phone"
+ "hid_nebula_watch"
+ "hid_sleep_algorithms"
+ "hid_wrist_detect_state_archive"
+ "iclouddriveextradebug"
+ "logFileProcessingConfigurations"
+ "packaging"
+ "respiration_tracking"
+ "sessionFileProcessingConfigurations"
+ "setLogFileProcessingConfigurations:"
+ "setSessionFileProcessingConfigurations:"
+ "v64@0:8@16@24@32@40@?48@?56"
+ "{\"backwardCompatibility\":true}"
- "Finisher config: %{public}s"
- "setProcessingConfigurations:"
```

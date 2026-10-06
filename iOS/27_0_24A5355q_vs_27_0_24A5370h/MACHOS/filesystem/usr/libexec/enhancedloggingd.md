## enhancedloggingd

> `/usr/libexec/enhancedloggingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa4664` | `0xa75fc` | **`+0x2f98`** |
| `__DATA.__bss` | `0x7300` | `0x7080` | **`-0x280`** |
| `__TEXT.__eh_frame` | `0x2d70` | `0x2f4c` | **`+0x1dc`** |
| `__DATA_CONST.__const` | `0x92f0` | `0x9460` | **`+0x170`** |
| `__TEXT.__auth_stubs` | `0x2050` | `0x2130` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x3000` | `0x30e0` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x1b7f` | `0x1c4b` | **`+0xcc`** |
| `__TEXT.__objc_methname` | `0x4531` | `0x45f1` | **`+0xc0`** |
| `__DATA.__data` | `0x28f8` | `0x29a8` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x14f1` | `0x15a1` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x1ac0` | `0x1b60` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x2bf6` | `0x2c76` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x1038` | `0x10a8` | **`+0x70`** |
| `__TEXT.__const` | `0x560c` | `0x55ac` | **`-0x60`** |
| `__TEXT.__swift5_capture` | `0x2974` | `0x29d4` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x1060` | `0x100b` | **`-0x55`** |
| `__DATA_CONST.__got` | `0x918` | `0x960` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x17dc` | `0x1824` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0x500` | `0x540` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xf20` | `0xf58` | **`+0x38`** |
| `__TEXT.__cstring` | `0x2c27` | `0x2c57` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x258` | `0x228` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x1258` | `0x1230` | **`-0x28`** |
| `__DATA.__common` | `0x1f8` | `0x210` | **`+0x18`** |
| `__DATA.__objc_const` | `0x2458` | `0x2470` | **`+0x18`** |
| `__DATA.__objc_data` | `0x898` | `0x8b0` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x11ec` | `0x1200` | **`+0x14`** |
| `__TEXT.__gcc_except_tab` | `0x308` | `0x31c` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x3a0` | `0x38c` | **`-0x14`** |
| `__TEXT.__swift_as_cont` | `0x144` | `0x158` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x5f8` | `0x608` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x4c9` | `0x4d7` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0xbc` | `0xb4` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xa0` | `0xa4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x88` | `0x8c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-225.0.0.0.0
+236.0.0.0.0

-  Functions: 2822
-  Symbols:   933
-  CStrings:  1320
+  Functions: 2854
+  Symbols:   954
+  CStrings:  1323
Symbols:
+ _$s15EnhancedLogging20ProcessingDescriptorV11destinationSSvg
+ _$s15EnhancedLogging20ProcessingDescriptorV11payloadTypeSSSgvg
+ _$s15EnhancedLogging20ProcessingDescriptorV7channelSSSgvg
+ _$s15EnhancedLogging20ProcessingDescriptorV7studyIDSSSgvg
+ _$s15EnhancedLogging20ProcessingDescriptorV9encryptorSSSgvg
+ _$s15EnhancedLogging20ProcessingDescriptorV9packagingSSSgvg
+ _$s15EnhancedLogging20ProcessingDescriptorV9publicKeySSSgvg
+ _$ss15ContinuousClockV7InstantVMa
+ _$ss15ContinuousClockV7InstantVs0C8ProtocolsMc
+ _$ss15ContinuousClockVMa
+ _$ss15ContinuousClockVs0B0sMc
+ _$ss15InstantProtocolP8advanced2byx8DurationQz_tFTj
+ _$ss5ClockP3now7InstantQzvgTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTjTu
+ _$ss5ClockPss010ContinuousA0VRszrlE10continuousADvgZ
+ _OBJC_CLASS_$_DEDEncryptorFactory
+ _OBJC_CLASS_$_ELAEAEncryptionConfiguration
+ _OBJC_CLASS_$_ELHealthWrapEncryptionConfiguration
+ _OBJC_CLASS_$_ELMockUploadConfiguration
+ _OBJC_CLASS_$_ELProcessingConfiguration
+ _objc_release_x9
+ _swift_release_x1
- _ELSMetadataDeviceType
- _NSClassFromString
CStrings:
+ "!"
+ "CKRecordValue"
+ "Could not locate encryptor '%{public}@' for DE: %{public}@. Dropping attachment"
+ "Encrypting logs from %{public}@"
+ "No encryption required for logs from %{public}@"
+ "channel"
+ "cloudKitContainerID"
+ "com.apple.MobileBackup.framework.DiagnosticExtension"
+ "duration"
+ "encryptLogsWithProcessingConfiguration:extensionIdentifier:attachmentUrl:"
+ "encryptionConfiguration"
+ "encryptorIdentifier"
+ "eventManagers"
+ "forceFail"
+ "initWithChannel:payloadType:publicKey:studyID:"
+ "initWithContainerIdentifier:taskIdentifier:"
+ "initWithDestination:packaging:encryptionConfiguration:"
+ "initWithForceFail:duration:"
+ "initWithPublicKey:"
+ "initWithSessionTicketID:uploadToken:cloudKitContainerID:"
+ "initWithTicketID:uploadToken:additionalFields:"
+ "isUploading"
+ "mockConfiguration"
+ "payloadType"
+ "processingConfigurations"
+ "publicKey"
+ "sessionMetadata"
+ "sessionTicketID"
+ "setMockConfiguration:"
+ "setProcessingConfigurations:"
+ "setSessionMetadata:"
+ "uploadToken"
- "1"
- "DEDEncryptorFactory"
- "No encryption required on %@"
- "T@\"NSString\",&,N,V_timberLorryUUID"
- "TB,N,V_sandboxEnvironment"
- "_sandboxEnvironment"
- "_timberLorryUUID"
- "anonymizedDeviceId"
- "cloudKitContainer"
- "cloudKitData"
- "cloudKitUseDevelopmentEnvironment"
- "createAttachmentGroupWithData:"
- "gigafilesToken"
- "initWithCloudKitContainer:cloudKitData:"
- "initWithConfiguration:taskIdentifier:"
- "initWithContainerIdentifier:environment:"
- "mock"
- "mockUploaderDuration"
- "mockUploaderForceFail"
- "numberWithBool:"
- "sandboxEnvironment"
- "setCloudKitUseDevelopmentEnvironment:"
- "setMockUploaderDuration:"
- "setMockUploaderForceFail:"
- "setSandboxEnvironment:"
- "setTimberLorryUUID:"
- "setUseMockUploader:"
- "uploadTokenKey"
- "useMockUploader"
```

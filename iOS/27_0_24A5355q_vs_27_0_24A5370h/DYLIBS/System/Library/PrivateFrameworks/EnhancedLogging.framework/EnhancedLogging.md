## EnhancedLogging

> `/System/Library/PrivateFrameworks/EnhancedLogging.framework/EnhancedLogging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c340` | `0x3d2e8` | **`+0xfa8`** |
| `__AUTH_CONST.__objc_const` | `0x10d0` | `0x1690` | **`+0x5c0`** |
| `__TEXT.__objc_methlist` | `0x9e0` | `0xcb0` | **`+0x2d0`** |
| `__AUTH.__objc_data` | `0x2b0` | `0x440` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0xe0` | `0x260` | **`+0x180`** |
| `__DATA_CONST.__objc_selrefs` | `0x630` | `0x6d0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1108` | `0x1188` | **`+0x80`** |
| `__TEXT.__cstring` | `0xc6b` | `0xcab` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x220` | `0x258` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x44` | `0x6c` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x78` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x38` | **`+0x20`** |
| `__DATA.__data` | `0xc30` | `0xc18` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT.__const` | `0x3af4` | `0x3b04` | **`+0x10`** |
| `__AUTH.__data` | `0x3f8` | `0x3f0` | **`-0x8`** |

### Other Changes

```diff

-225.0.0.0.0
+236.0.0.0.0

+  - /usr/lib/swift/libswiftCoreLocation.dylib

+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

-  Functions: 2003
-  Symbols:   779
-  CStrings:  138
+  Functions: 2052
+  Symbols:   892
+  CStrings:  150
Symbols:
+ +[ELAEAEncryptionConfiguration archivedClasses]
+ +[ELAEAEncryptionConfiguration encryptorIdentifier]
+ +[ELAEAEncryptionConfiguration supportsSecureCoding]
+ +[ELEncryptionConfiguration archivedClasses]
+ +[ELEncryptionConfiguration encryptorIdentifier]
+ +[ELEncryptionConfiguration supportsSecureCoding]
+ +[ELHealthWrapEncryptionConfiguration archivedClasses]
+ +[ELHealthWrapEncryptionConfiguration encryptorIdentifier]
+ +[ELHealthWrapEncryptionConfiguration supportsSecureCoding]
+ +[ELMockUploadConfiguration archivedClasses]
+ +[ELMockUploadConfiguration supportsSecureCoding]
+ +[ELProcessingConfiguration archivedClasses]
+ +[ELProcessingConfiguration supportsSecureCoding]
+ -[ELAEAEncryptionConfiguration .cxx_destruct]
+ -[ELAEAEncryptionConfiguration classForCoder]
+ -[ELAEAEncryptionConfiguration copyWithZone:]
+ -[ELAEAEncryptionConfiguration encodeWithCoder:]
+ -[ELAEAEncryptionConfiguration initWithCoder:]
+ -[ELAEAEncryptionConfiguration initWithPublicKey:]
+ -[ELAEAEncryptionConfiguration publicKey]
+ -[ELEncryptionConfiguration copyWithZone:]
+ -[ELEncryptionConfiguration copy]
+ -[ELEncryptionConfiguration encodeWithCoder:]
+ -[ELEncryptionConfiguration encryptor]
+ -[ELEncryptionConfiguration initWithCoder:]
+ -[ELHealthWrapEncryptionConfiguration .cxx_destruct]
+ -[ELHealthWrapEncryptionConfiguration channel]
+ -[ELHealthWrapEncryptionConfiguration classForCoder]
+ -[ELHealthWrapEncryptionConfiguration copyWithZone:]
+ -[ELHealthWrapEncryptionConfiguration encodeWithCoder:]
+ -[ELHealthWrapEncryptionConfiguration initWithChannel:payloadType:publicKey:studyID:]
+ -[ELHealthWrapEncryptionConfiguration initWithCoder:]
+ -[ELHealthWrapEncryptionConfiguration payloadType]
+ -[ELHealthWrapEncryptionConfiguration publicKey]
+ -[ELHealthWrapEncryptionConfiguration studyID]
+ -[ELMockUploadConfiguration copyWithZone:]
+ -[ELMockUploadConfiguration duration]
+ -[ELMockUploadConfiguration encodeWithCoder:]
+ -[ELMockUploadConfiguration forceFail]
+ -[ELMockUploadConfiguration initWithCoder:]
+ -[ELMockUploadConfiguration initWithForceFail:]
+ -[ELMockUploadConfiguration initWithForceFail:duration:]
+ -[ELMockUploadConfiguration setDuration:]
+ -[ELMockUploadConfiguration setForceFail:]
+ -[ELProcessingConfiguration .cxx_destruct]
+ -[ELProcessingConfiguration copyWithZone:]
+ -[ELProcessingConfiguration copy]
+ -[ELProcessingConfiguration destination]
+ -[ELProcessingConfiguration encodeWithCoder:]
+ -[ELProcessingConfiguration encryptionConfiguration]
+ -[ELProcessingConfiguration initWithCoder:]
+ -[ELProcessingConfiguration initWithDestination:packaging:encryptionConfiguration:]
+ -[ELProcessingConfiguration packaging]
+ -[ELTimberLorryUploadConfiguration cloudKitContainerID]
+ -[ELTimberLorryUploadConfiguration copy]
+ -[ELTimberLorryUploadConfiguration initWithSessionTicketID:uploadToken:cloudKitContainerID:]
+ -[ELTimberLorryUploadConfiguration mockConfiguration]
+ -[ELTimberLorryUploadConfiguration processingConfigurations]
+ -[ELTimberLorryUploadConfiguration sessionMetadata]
+ -[ELTimberLorryUploadConfiguration sessionTicketID]
+ -[ELTimberLorryUploadConfiguration setCloudKitContainerID:]
+ -[ELTimberLorryUploadConfiguration setMockConfiguration:]
+ -[ELTimberLorryUploadConfiguration setProcessingConfigurations:]
+ -[ELTimberLorryUploadConfiguration setSessionMetadata:]
+ -[ELTimberLorryUploadConfiguration setSessionTicketID:]
+ -[ELTimberLorryUploadConfiguration setUploadToken:]
+ -[ELTimberLorryUploadConfiguration uploadToken]
+ _OBJC_CLASS_$_CKContainerID
+ _OBJC_CLASS_$_ELAEAEncryptionConfiguration
+ _OBJC_CLASS_$_ELEncryptionConfiguration
+ _OBJC_CLASS_$_ELHealthWrapEncryptionConfiguration
+ _OBJC_CLASS_$_ELMockUploadConfiguration
+ _OBJC_CLASS_$_ELProcessingConfiguration
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_IVAR_$_ELAEAEncryptionConfiguration._publicKey
+ _OBJC_IVAR_$_ELHealthWrapEncryptionConfiguration._channel
+ _OBJC_IVAR_$_ELHealthWrapEncryptionConfiguration._payloadType
+ _OBJC_IVAR_$_ELHealthWrapEncryptionConfiguration._publicKey
+ _OBJC_IVAR_$_ELHealthWrapEncryptionConfiguration._studyID
+ _OBJC_IVAR_$_ELMockUploadConfiguration._duration
+ _OBJC_IVAR_$_ELMockUploadConfiguration._forceFail
+ _OBJC_IVAR_$_ELProcessingConfiguration._destination
+ _OBJC_IVAR_$_ELProcessingConfiguration._encryptionConfiguration
+ _OBJC_IVAR_$_ELProcessingConfiguration._packaging
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._cloudKitContainerID
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._mockConfiguration
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._processingConfigurations
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._sessionMetadata
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._sessionTicketID
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._uploadToken
+ _OBJC_METACLASS_$_ELAEAEncryptionConfiguration
+ _OBJC_METACLASS_$_ELEncryptionConfiguration
+ _OBJC_METACLASS_$_ELHealthWrapEncryptionConfiguration
+ _OBJC_METACLASS_$_ELMockUploadConfiguration
+ _OBJC_METACLASS_$_ELProcessingConfiguration
+ __OBJC_$_CLASS_METHODS_ELAEAEncryptionConfiguration
+ __OBJC_$_CLASS_METHODS_ELEncryptionConfiguration
+ __OBJC_$_CLASS_METHODS_ELHealthWrapEncryptionConfiguration
+ __OBJC_$_CLASS_METHODS_ELMockUploadConfiguration
+ __OBJC_$_CLASS_METHODS_ELProcessingConfiguration
+ __OBJC_$_CLASS_PROP_LIST_ELEncryptionConfiguration
+ __OBJC_$_CLASS_PROP_LIST_ELMockUploadConfiguration
+ __OBJC_$_CLASS_PROP_LIST_ELProcessingConfiguration
+ __OBJC_$_INSTANCE_METHODS_ELAEAEncryptionConfiguration
+ __OBJC_$_INSTANCE_METHODS_ELEncryptionConfiguration
+ __OBJC_$_INSTANCE_METHODS_ELHealthWrapEncryptionConfiguration
+ __OBJC_$_INSTANCE_METHODS_ELMockUploadConfiguration
+ __OBJC_$_INSTANCE_METHODS_ELProcessingConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_ELAEAEncryptionConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_ELHealthWrapEncryptionConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_ELMockUploadConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_ELProcessingConfiguration
+ __OBJC_$_PROP_LIST_ELAEAEncryptionConfiguration
+ __OBJC_$_PROP_LIST_ELEncryptionConfiguration
+ __OBJC_$_PROP_LIST_ELHealthWrapEncryptionConfiguration
+ __OBJC_$_PROP_LIST_ELMockUploadConfiguration
+ __OBJC_$_PROP_LIST_ELProcessingConfiguration
+ __OBJC_CLASS_PROTOCOLS_$_ELEncryptionConfiguration
+ __OBJC_CLASS_PROTOCOLS_$_ELMockUploadConfiguration
+ __OBJC_CLASS_PROTOCOLS_$_ELProcessingConfiguration
+ __OBJC_CLASS_RO_$_ELAEAEncryptionConfiguration
+ __OBJC_CLASS_RO_$_ELEncryptionConfiguration
+ __OBJC_CLASS_RO_$_ELHealthWrapEncryptionConfiguration
+ __OBJC_CLASS_RO_$_ELMockUploadConfiguration
+ __OBJC_CLASS_RO_$_ELProcessingConfiguration
+ __OBJC_METACLASS_RO_$_ELAEAEncryptionConfiguration
+ __OBJC_METACLASS_RO_$_ELEncryptionConfiguration
+ __OBJC_METACLASS_RO_$_ELHealthWrapEncryptionConfiguration
+ __OBJC_METACLASS_RO_$_ELMockUploadConfiguration
+ __OBJC_METACLASS_RO_$_ELProcessingConfiguration
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftCoreLocation_$_EnhancedLogging
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers_$_EnhancedLogging
+ _objc_alloc
+ _objc_release_x9
- -[ELTimberLorryUploadConfiguration cloudKitContainer]
- -[ELTimberLorryUploadConfiguration cloudKitData]
- -[ELTimberLorryUploadConfiguration cloudKitUseDevelopmentEnvironment]
- -[ELTimberLorryUploadConfiguration hash]
- -[ELTimberLorryUploadConfiguration initWithCloudKitContainer:cloudKitData:]
- -[ELTimberLorryUploadConfiguration isEqual:]
- -[ELTimberLorryUploadConfiguration mockUploaderDuration]
- -[ELTimberLorryUploadConfiguration mockUploaderForceFail]
- -[ELTimberLorryUploadConfiguration setCloudKitContainer:]
- -[ELTimberLorryUploadConfiguration setCloudKitData:]
- -[ELTimberLorryUploadConfiguration setCloudKitUseDevelopmentEnvironment:]
- -[ELTimberLorryUploadConfiguration setMockUploaderDuration:]
- -[ELTimberLorryUploadConfiguration setMockUploaderForceFail:]
- -[ELTimberLorryUploadConfiguration setUseMockUploader:]
- -[ELTimberLorryUploadConfiguration useMockUploader]
- _CKAcceptableValueClasses
- _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._cloudKitContainer
- _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._cloudKitData
- _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._cloudKitUseDevelopmentEnvironment
- _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._mockUploaderDuration
- _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._mockUploaderForceFail
- _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._useMockUploader
- _objc_opt_isKindOfClass
CStrings:
+ "<%@: %p; sessionTicketID: %@; uploadToken: %@; cloudKitConfiguration: %@; mockConfiguration: %@>"
+ "AppleEncryptedArchive"
+ "channel"
+ "cloudKitContainerID"
+ "destination"
+ "duration"
+ "encryptionConfiguration"
+ "encryptor"
+ "forceFail"
+ "healthwrap"
+ "mockConfiguration"
+ "packaging"
+ "payloadType"
+ "processingConfigurations"
+ "publicKey"
+ "sessionMetadata"
+ "studyID"
+ "ticket"
+ "uploadToken"
- "<%@: %p; cloudkitContainer: %@; cloudkitUseDevelopmentEnvironment: %d; cloudkitData: %@; useMockUploader: %d; mockUploaderForceFail: %d; mockUploaderTime: %ld>"
- "cloudkitContainer"
- "cloudkitData"
- "cloudkitUseDevelopmentEnvironment"
- "mockUploaderDuration"
- "mockUploaderForceFail"
- "useMockUploader"
```

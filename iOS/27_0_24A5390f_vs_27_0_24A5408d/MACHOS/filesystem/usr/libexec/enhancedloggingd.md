## enhancedloggingd

> `/usr/libexec/enhancedloggingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaf980` | `0xb4114` | **`+0x4794`** |
| `__DATA_CONST.__const` | `0xa140` | `0xa558` | **`+0x418`** |
| `__DATA.__bss` | `0x6f80` | `0x6c80` | **`-0x300`** |
| `__TEXT.__objc_methname` | `0x49b9` | `0x4b6d` | **`+0x1b4`** |
| `__TEXT.__swift5_capture` | `0x2c58` | `0x2e04` | **`+0x1ac`** |
| `__TEXT.__oslogstring` | `0x2fe6` | `0x3176` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x3330` | `0x31dc` | **`-0x154`** |
| `__DATA.__objc_const` | `0x24c8` | `0x25f0` | **`+0x128`** |
| `__TEXT.__objc_methtype` | `0x10eb` | `0x120b` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x12a0` | `0x13ac` | **`+0x10c`** |
| `__DATA.__data` | `0x2a58` | `0x2b58` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x21a0` | `0x2270` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x1621` | `0x1551` | **`-0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x1848` | `0x178c` | **`-0xbc`** |
| `__TEXT.__swift5_typeref` | `0x1e2b` | `0x1d8b` | **`-0xa0`** |
| `__DATA_CONST.__auth_got` | `0x10e0` | `0x1148` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x970` | `0x9d8` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x324` | `0x37c` | **`+0x58`** |
| `__TEXT.__const` | `0x584c` | `0x57fc` | **`-0x50`** |
| `__DATA_CONST.__cfstring` | `0x540` | `0x580` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x3360` | `0x33a0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xff0` | `0x1018` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0xf0` | `0xc8` | **`-0x28`** |
| `__TEXT.__cstring` | `0x2fa7` | `0x2fcd` | **`+0x26`** |
| `__DATA.__objc_data` | `0x8a8` | `0x8c8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x11ec` | `0x11cc` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x240` | `0x228` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x384` | `0x36c` | **`-0x18`** |
| `__DATA_CONST.__objc_protolist` | `0xb0` | `0xc0` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xc0` | `0xb0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1cf8` | `0x1ce8` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0xac` | `0xb8` | **`+0xc`** |
| `__DATA.__common` | `0x200` | `0x208` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x2c` | `0x24` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x160` | `0x158` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb8` | `0xb4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-251.0.0.0.0
+267.2.3.0.0

+  - /System/Library/PrivateFrameworks/AuthKit.framework/AuthKit

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 2986
-  Symbols:   959
-  CStrings:  1386
+  Functions: 3017
+  Symbols:   985
+  CStrings:  1411
Symbols:
+ _$s10Foundation10URLRequestV19_bridgeToObjectiveCSo12NSURLRequestCyF
+ _$s10Foundation10URLRequestV19allHTTPHeaderFieldsSDyS2SGSgvg
+ _$s10Foundation10URLRequestV19allHTTPHeaderFieldsSDyS2SGSgvs
+ _$s10Foundation10URLRequestV3urlAA3URLVSgvg
+ _$s10Foundation10URLRequestV8httpBodyAA4DataVSgvg
+ _$s10Foundation3URLV14absoluteStringSSvg
+ _$s15EnhancedLogging10EncryptionOMn
+ _$s15EnhancedLogging10EncryptionON
+ _$s15EnhancedLogging10EncryptionOSeAAMc
+ _$s15EnhancedLogging16PromptDescriptorO4InfoV2id5event20titleLocalizationKey07contentiJ08imageUrl11displayOnceAE10Foundation4UUIDV_AC5EventOS2SAL3URLVSgSbtcfC
+ _$s15EnhancedLogging16PromptDescriptorO4SignV10processingAA010ProcessingD0VSgvg
+ _$s15EnhancedLogging16PromptDescriptorO4SignV2id5event9promptIds28titleOverrideLocalizationKey011contentTextklM011displayOnce10processingAE10Foundation4UUIDV_AC5EventOSayAOGSSSgASSbAA010ProcessingD0VSgtcfC
+ _$s15EnhancedLogging16PromptDescriptorO4SignVMa
+ _$s15EnhancedLogging16PromptDescriptorO4infoyA2C4InfoVcACmFWC
+ _$s15EnhancedLogging16PromptDescriptorO4signyA2C4SignVcACmFWC
+ _$s15EnhancedLogging16PromptDescriptorO5EventO10collectingyA2EmFWC
+ _$s15EnhancedLogging16PromptDescriptorO5EventO6reviewyA2EmFWC
+ _$s15EnhancedLogging16PromptDescriptorO5EventO7consentyA2EmFWC
+ _$s15EnhancedLogging16PromptDescriptorO5EventOMa
+ _$s15EnhancedLogging16PromptDescriptorO7ConsentV2id5event20titleLocalizationKey07contentiJ011displayOnceAE10Foundation4UUIDV_AC5EventOS2SSbtcfC
+ _$s15EnhancedLogging16PromptDescriptorO7consentyA2C7ConsentVcACmFWC
+ _$s15EnhancedLogging16PromptDescriptorOMa
+ _$s15EnhancedLogging16PromptDescriptorOMn
+ _$s15EnhancedLogging16PromptDescriptorOSEAAMc
+ _$s15EnhancedLogging16PromptDescriptorOSeAAMc
+ _$s15EnhancedLogging17CanopyClientErrorO15invalidResponseyA2CmFWC
+ _$s15EnhancedLogging17CanopyClientErrorO16failedWithStatusyACSicACmFWC
+ _$s15EnhancedLogging17CanopyClientErrorO25ticketNotPercentEncodableyA2CmFWC
+ _$s15EnhancedLogging17CanopyClientErrorOMa
+ _$s15EnhancedLogging17CanopyClientErrorOs0E0AAMc
+ _$s15EnhancedLogging17EnvironmentConfigO11containerIdSo13CKContainerIDCvgZ
+ _$s15EnhancedLogging17EnvironmentConfigO9serverURL10Foundation0F0VvgZ
+ _$s15EnhancedLogging17UploadConsentItemV7rootURL5filesAC10Foundation0G0V_SayAHGtcfC
+ _$s15EnhancedLogging20EncryptionDescriptorO9encryptor7channel11payloadType9publicKey7studyIDACSS_SSSgA3ItKcfC
+ _$s15EnhancedLogging20ProcessingDescriptorV10encryptionAA10EncryptionOvg
+ _$s15EnhancedLogging20ProcessingDescriptorV15compressionMode10encryptionAcA11CompressionOSg_AA10EncryptionOtcfC
+ _$s8Dispatch0A3QoSV7utilityACvgZ
+ _$sSS10FoundationE6format_S2Sh_s7CVarArg_pdtcfC
+ _$sSds7CVarArgsWP
+ _$sSo18NSNotificationNamea15EnhancedLoggingE18uploadStateChangedABvgZ
+ _$sSo7NSCoderC10FoundationE12decodeObject2of6forKeyxSgxm_SStSo8NSObjectCRbzSo8NSCodingRzlF
+ _$sSo7NSCoderC10FoundationE12decodeObject2of6forKeyypSgSayyXlXpGSg_SStF
+ _$ss22KeyedDecodingContainerV8containsySbxF
+ _$ss27_bridgeAnythingToObjectiveCyyXlxlF
+ _$ss7CVarArgMp
+ _AKInternalBuildHeaderKey
+ _AKSeedBuildHeaderKey
+ _AKTrueValue
+ _MobileGestalt_copy_productType_obj
+ _MobileGestalt_copy_productVersion_obj
+ _NSURLFileSizeKey
+ _OBJC_CLASS_$_AKAnisetteProvisioningController
+ _OBJC_CLASS_$_AKAttestationRequestData
+ _OBJC_CLASS_$_AKConfiguration
+ __swift_FORCE_LOAD_$_swiftCompression
+ _swift_deallocPartialClassInstance
+ _swift_isaMask
+ _swift_release_x10
- _$s15EnhancedLogging16PromptDescriptorV10processingAA010ProcessingD0VSgvg
- _$s15EnhancedLogging16PromptDescriptorV2id5event8template20titleLocalizationKey07contentiJ08imageUrl4once10processingAC10Foundation4UUIDV_AC5EventOAC8TemplateOS3SSgSbAA010ProcessingD0VSgtcfC
- _$s15EnhancedLogging16PromptDescriptorV5EventO10collectingyA2EmFWC
- _$s15EnhancedLogging16PromptDescriptorV5EventO6reviewyA2EmFWC
- _$s15EnhancedLogging16PromptDescriptorV5EventO7consentyA2EmFWC
- _$s15EnhancedLogging16PromptDescriptorV5EventO7defaultAEvgZ
- _$s15EnhancedLogging16PromptDescriptorV5EventOMa
- _$s15EnhancedLogging16PromptDescriptorV5EventOMn
- _$s15EnhancedLogging16PromptDescriptorV8TemplateO4infoyA2EmFWC
- _$s15EnhancedLogging16PromptDescriptorV8TemplateO4signyAESay10Foundation4UUIDVGcAEmFWC
- _$s15EnhancedLogging16PromptDescriptorV8TemplateO7consentyA2EmFWC
- _$s15EnhancedLogging16PromptDescriptorV8TemplateO7defaultAEvgZ
- _$s15EnhancedLogging16PromptDescriptorV8TemplateOMa
- _$s15EnhancedLogging16PromptDescriptorV8TemplateOMn
- _$s15EnhancedLogging16PromptDescriptorV8templateAC8TemplateOvg
- _$s15EnhancedLogging16PromptDescriptorVMa
- _$s15EnhancedLogging16PromptDescriptorVMn
- _$s15EnhancedLogging16PromptDescriptorVSEAAMc
- _$s15EnhancedLogging16PromptDescriptorVSeAAMc
- _$s15EnhancedLogging17UploadConsentItemV8titleKey16modificationDate7rootURL5filesACSS_10Foundation0I0VSgAH0K0VSayAMGtcfC
- _$s15EnhancedLogging20ProcessingDescriptorV11destination9encryptor15compressionMode11payloadType9publicKey7channel7studyID04caseO0ACSS_SSSgAA11CompressionOSgA5LtcfC
- _$s15EnhancedLogging20ProcessingDescriptorV11payloadTypeSSSgvg
- _$s15EnhancedLogging20ProcessingDescriptorV7channelSSSgvg
- _$s15EnhancedLogging20ProcessingDescriptorV7studyIDSSSgvg
- _$s15EnhancedLogging20ProcessingDescriptorV9encryptorSSSgvg
- _$s15EnhancedLogging20ProcessingDescriptorV9publicKeySSSgvg
- _$sSS10describingSSx_tclufC
- _$sScM6sharedScMvgZ
- _$sScMMa
- _$sScMScAsWP
- _NSFileModificationDate
- _OBJC_CLASS_$_ELSEnvironment
CStrings:
+ "$__lazy_storage_$_cancelledError"
+ "-[TLCloudKitFileUploadTask uploadLogFiles:sessionFilesDirectory:]"
+ "@\"<TLFileUploadTaskDelegate>\"16@0:8"
+ "@\"ELTimberLorryUploadConfiguration\"16@0:8"
+ "@\"NSError\""
+ "@\"NSError\"16@0:8"
+ "@\"NSSet\"16@0:8"
+ "@32@0:8@16@?24"
+ "B32@0:8q16@24"
+ "Extension %s is not in the allowlist, skipping."
+ "Failed to build prompts: %@"
+ "Failed to get BAA cert: %@"
+ "Failed to parse identifier %{public}@, skipping"
+ "Missing required keys to decode (sessionID: %@ anonymousDeviceUUID: %@ extensionFiles: %@ config: %@ attachments: %@ uploadedBytes: %@)"
+ "No attestation data present for request."
+ "No processing configuration for %{public}@; skipping"
+ "Processing object is missing encryption; falling back to legacy flat encryption fields"
+ "Restoring %ld persisted upload task(s)"
+ "Resuming mock upload for session [%{public}s] (status: %ld)"
+ "T@\"<TLFileUploadTaskDelegate>\",N,W,Vdelegate"
+ "T@\"<TLFileUploadTaskDelegate>\",W,N"
+ "T@\"<TLFileUploadTaskDelegate>\",W,N,Vdelegate"
+ "T@\"ELTimberLorryUploadConfiguration\",N,R,Vconfiguration"
+ "T@\"ELTimberLorryUploadConfiguration\",R,N"
+ "T@\"NSError\",&,N,V_error"
+ "T@\"NSError\",N,C"
+ "T@\"NSError\",R,N"
+ "T@\"TLCloudKitClient\",&,V_cloudKitClient"
+ "TB,N,R"
+ "User defaults format version mismatch: %{public}ld, expected %{public}ld. Flushing."
+ "[%s] %s has unexpected type %s; expected %s"
+ "[%s] Failed to decode %s with error %@"
+ "[%s] Failed to encode %s:%s with error %@"
+ "[%{public}s] Already finished (status: %ld)"
+ "[%{public}s] Compression progress: %lld / %lld"
+ "[%{public}s] Resuming persisted upload (status: %ld)"
+ "[%{public}s] Status changed to %ld"
+ "[%{public}s] Upload completed successfully"
+ "[%{public}s] Upload progress: %lld / %lld"
+ "[Canopy] Request CLAIM Ticket %s\nHeaders: %s\nBody: %s"
+ "[Canopy] Request FETCH Ticket %s\nHeaders: %s\nBody: %s"
+ "_error"
+ "_persistedUploadTasks"
+ "allHeaders"
+ "applyState:error:"
+ "archiveURL:progressHandler:"
+ "attestationDataForRequestData:completion:"
+ "com.apple.enhancedloggingd.TLCloudKitFileUploadTask"
+ "com.apple.enhancedloggingd.resume-persisted-uploads"
+ "configuration"
+ "decodeInt64ForKey:"
+ "dictionaryForKey:"
+ "encodeInt64:forKey:"
+ "encryptFileIfNeededAtURL:forExtensionIdentifier:"
+ "encryptFileIfNeededAtURL:withEncryptionConfiguration:identifier:"
+ "error"
+ "getError(sessionID:completionHandler:)"
+ "getErrorWithSessionID:completionHandler:"
+ "initWithRequest:requiredHeaders:"
+ "pendingFiles"
+ "processFlatDirectoriesAtURL:extensionID:queueKey:healthStudyID:progressHandler:"
+ "processSessionFile:progressHandler:"
+ "q24@0:8q16"
+ "setError:"
+ "sharedConfiguration"
+ "shouldHideInternalBuildHeader"
+ "shouldHideSeedBuildHeader"
+ "statusForState:"
+ "uploadLogFiles:sessionFilesDirectory:"
+ "uploadTasks"
+ "uploader:didTransitionToStatus:"
+ "v24@0:8@\"<TLFileUploadTaskDelegate>\"16"
+ "v24@?0@\"AKBAAAttestationData\"8@\"NSError\"16"
+ "v32@0:8@\"<TLFileUploadTask>\"16q24"
+ "v32@0:8@\"NSDictionary\"16@\"NSURL\"24"
+ "v32@0:8@16q24"
+ "v56@0:8@16@24@32@40@?48"
+ "x-apple-os-version"
+ "x-apple-primary-device-model"
- "!"
- "-[TLCloudKitFileUploadTask uploadLogFiles:sessionFilesDirectory:configuration:]"
- "CONSENT_FORM_SUBTITLE"
- "CONSENT_FORM_TITLE"
- "Could not identify diagnostic extension with id %@. No paylaod returned"
- "Could not locate an encryptor for: %@ for the DE: %@. Dropping attachment"
- "Could not parse extension identifier %{public}@, skipping"
- "Current user defaults format version is %{public}s, expected %{public}ld"
- "Error assembling UploadConsentItem: %@"
- "Error parsing payload from CloudKit data: %{public}@"
- "Extension identifier is nil"
- "Failed to find entry for identifier: %s"
- "JSONObjectWithData:options:error:"
- "Missing one or more required keys to decode (attachments: %@ uploadedBytes: %@)"
- "No encryptor specified for DE: %@ which requires encryption. Dropping file attachment"
- "Session file %{public}@ has unexpected compression mode %ld; expected none"
- "State changed for session [%{public}s]"
- "T@\"<TLFileUploadTaskDelegate>\",W,N,V_delegate"
- "T@\"NSDictionary\",&,N,V_queuePayload"
- "T@\"TLCloudKitClient\",&"
- "Tq,N,V_status"
- "Upload completed successfully for session [%{public}s]"
- "Upload failed for session [%{public}s]: %@"
- "_delegate"
- "_queuePayload"
- "activeUploads"
- "archiveAndAttachURL:sourceID:queueKey:healthStudyID:extensionID:progressHandler:"
- "caseID"
- "cloudKitContainerIdentifier"
- "com.apple.enhancedloggingd.TLCloudKitFinisher"
- "compressionFailed"
- "compressionFinished"
- "compressionStartedSessions"
- "dataUsingEncoding:"
- "dedExtensionIdentifier"
- "destination"
- "encryptAndAttachURL:sourceID:queueKey:healthStudyID:extensionID:"
- "encryptFileAtURL:forExtensionIdentifier:"
- "encryptFileAtURL:withProcessingConfiguration:extensionIdentifier:"
- "encryptorIdentifier"
- "findEntryForDEDIdentifier:"
- "https://logs.apple.com/api/v1"
- "parsePayloadData:forIdentifier:"
- "payload"
- "processFlatDirectoriesAtURL:sourceID:queueKey:healthStudyID:extensionID:progressHandler:"
- "processSessionFile:"
- "queuePayload"
- "setQueuePayload:"
- "stringForKey:"
- "uploadLogFiles:sessionFilesDirectory:configuration:"
- "uploadStartedSessions"
- "v40@0:8@\"NSDictionary\"16@\"NSURL\"24@\"ELTimberLorryUploadConfiguration\"32"
- "v40@0:8@16@24@32"
- "v56@0:8@16@24@32@40@48"
```

## BiomeLibrary

> `/System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x756610` | `0x7584dc` | **`+0x1ecc`** |
| `__AUTH_CONST.__objc_const` | `0xa2bf0` | `0xa2f50` | **`+0x360`** |
| `__TEXT.__objc_methlist` | `0x5039c` | `0x50564` | **`+0x1c8`** |
| `__TEXT.__cstring` | `0x4e8a6` | `0x4e9fa` | **`+0x154`** |
| `__AUTH_CONST.__cfstring` | `0x4b3a0` | `0x4b4c0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xb170` | `0xb210` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xf610` | `0xf678` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x9af8` | `0x9b38` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x129a0` | `0x129d8` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x6690` | `0x66c0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1eba8` | `0x1ebc8` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0xb258` | `0xb278` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x8204` | `0x8220` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x1c00` | `0x1c10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2310` | `0x2320` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b30` | `0x1b40` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 28688
-  Symbols:   53001
-  CStrings:  9763
+  Functions: 28727
+  Symbols:   53071
+  CStrings:  9772
Symbols:
+ +[BMPrivateCloudComputeClientRequestData columns]
+ +[BMPrivateCloudComputeClientRequestData eventWithData:dataVersion:]
+ +[BMPrivateCloudComputeClientRequestData latestDataVersion]
+ +[BMPrivateCloudComputeClientRequestData protoFields]
+ +[BMPrivateCloudComputeClientRequestData validKeyPaths]
+ +[BMPrivateCloudComputeClientRequestDataAppleReferenceImage columns]
+ +[BMPrivateCloudComputeClientRequestDataAppleReferenceImage eventWithData:dataVersion:]
+ +[BMPrivateCloudComputeClientRequestDataAppleReferenceImage latestDataVersion]
+ +[BMPrivateCloudComputeClientRequestDataAppleReferenceImage protoFields]
+ +[BMPrivateCloudComputeClientRequestDataAppleReferenceImage validKeyPaths]
+ -[BMPrivateCloudComputeClientRequestData .cxx_destruct]
+ -[BMPrivateCloudComputeClientRequestData appleReferenceImage]
+ -[BMPrivateCloudComputeClientRequestData dataVersion]
+ -[BMPrivateCloudComputeClientRequestData description]
+ -[BMPrivateCloudComputeClientRequestData initByReadFrom:]
+ -[BMPrivateCloudComputeClientRequestData initWithAppleReferenceImage:]
+ -[BMPrivateCloudComputeClientRequestData initWithJSONDictionary:error:]
+ -[BMPrivateCloudComputeClientRequestData isEqual:]
+ -[BMPrivateCloudComputeClientRequestData jsonDictionary]
+ -[BMPrivateCloudComputeClientRequestData serialize]
+ -[BMPrivateCloudComputeClientRequestData writeTo:]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage .cxx_destruct]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage dataVersion]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage description]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage imageCreationDate]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage initByReadFrom:]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage initWithJSONDictionary:error:]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage initWithPhotosAssetLocalIdentifier:imageCreationDate:]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage isEqual:]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage jsonDictionary]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage photosAssetLocalIdentifier]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage serialize]
+ -[BMPrivateCloudComputeClientRequestDataAppleReferenceImage writeTo:]
+ -[BMPrivateCloudComputeRequestLog clientRequestData]
+ -[BMPrivateCloudComputeRequestLog initWithTimestamp:requestId:pipelineKind:pipelineParameters:nodes:outboundCalls:assets:clientRequestData:]
+ _BMPrivateCloudComputeClientRequestDataAppleReferenceImageColumn
+ _BMPrivateCloudComputeClientRequestDataAppleReferenceImageImageCreationDateColumn
+ _BMPrivateCloudComputeClientRequestDataAppleReferenceImagePhotosAssetLocalIdentifierColumn
+ _BMPrivateCloudComputeRequestLogClientRequestDataColumn
+ _OBJC_CLASS_$_BMPrivateCloudComputeClientRequestData
+ _OBJC_CLASS_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ _OBJC_IVAR_$_BMPrivateCloudComputeClientRequestData._appleReferenceImage
+ _OBJC_IVAR_$_BMPrivateCloudComputeClientRequestData._dataVersion
+ _OBJC_IVAR_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage._dataVersion
+ _OBJC_IVAR_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage._hasRaw_imageCreationDate
+ _OBJC_IVAR_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage._photosAssetLocalIdentifier
+ _OBJC_IVAR_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage._raw_imageCreationDate
+ _OBJC_IVAR_$_BMPrivateCloudComputeRequestLog._clientRequestData
+ _OBJC_METACLASS_$_BMPrivateCloudComputeClientRequestData
+ _OBJC_METACLASS_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ _OUTLINED_FUNCTION_46
+ _OUTLINED_FUNCTION_47
+ _OUTLINED_FUNCTION_48
+ __OBJC_$_CLASS_METHODS_BMPrivateCloudComputeClientRequestData
+ __OBJC_$_CLASS_METHODS_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ __OBJC_$_CLASS_PROP_LIST_BMPrivateCloudComputeClientRequestData
+ __OBJC_$_CLASS_PROP_LIST_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ __OBJC_$_INSTANCE_METHODS_BMPrivateCloudComputeClientRequestData
+ __OBJC_$_INSTANCE_METHODS_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ __OBJC_$_INSTANCE_VARIABLES_BMPrivateCloudComputeClientRequestData
+ __OBJC_$_INSTANCE_VARIABLES_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ __OBJC_$_PROP_LIST_BMPrivateCloudComputeClientRequestData
+ __OBJC_$_PROP_LIST_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ __OBJC_CLASS_PROTOCOLS_$_BMPrivateCloudComputeClientRequestData
+ __OBJC_CLASS_PROTOCOLS_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ __OBJC_CLASS_RO_$_BMPrivateCloudComputeClientRequestData
+ __OBJC_CLASS_RO_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ __OBJC_METACLASS_RO_$_BMPrivateCloudComputeClientRequestData
+ __OBJC_METACLASS_RO_$_BMPrivateCloudComputeClientRequestDataAppleReferenceImage
+ ___42+[BMPrivateCloudComputeRequestLog columns]_block_invoke_5
+ ___49+[BMPrivateCloudComputeClientRequestData columns]_block_invoke
- -[BMPrivateCloudComputeRequestLog initWithTimestamp:requestId:pipelineKind:pipelineParameters:nodes:outboundCalls:assets:]
CStrings:
+ ", clientRequestData: %@"
+ "BMPrivateCloudComputeClientRequestData with appleReferenceImage: %@"
+ "BMPrivateCloudComputeClientRequestDataAppleReferenceImage with photosAssetLocalIdentifier: %@, imageCreationDate: %@"
+ "appleReferenceImage"
+ "appleReferenceImage_json"
+ "clientRequestData"
+ "clientRequestData_json"
+ "imageCreationDate"
+ "photosAssetLocalIdentifier"
```

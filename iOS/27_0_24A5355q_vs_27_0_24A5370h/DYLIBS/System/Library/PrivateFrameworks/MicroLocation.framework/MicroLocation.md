## MicroLocation

> `/System/Library/PrivateFrameworks/MicroLocation.framework/MicroLocation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bf7c` | `0x1d448` | **`+0x14cc`** |
| `__TEXT.__oslogstring` | `0xe82` | `0x1008` | **`+0x186`** |
| `__AUTH_CONST.__objc_const` | `0x3bc0` | `0x3d18` | **`+0x158`** |
| `__AUTH_CONST.__cfstring` | `0x2ec0` | `0x3000` | **`+0x140`** |
| `__TEXT.__cstring` | `0x2c41` | `0x2d69` | **`+0x128`** |
| `__DATA.__data` | `0x250` | `0x310` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x120` | `0x1c0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x748` | `0x7d8` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x2764` | `0x27c4` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x1070` | `0x10c0` | **`+0x50`** |
| `__DATA.__bss` | `0x10` | `0x48` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x798` | `0x7d0` | **`+0x38`** |
| `__DATA_CONST.__objc_catlist` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x40` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__const` | `0xe0` | `0xe8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x22c` | `0x230` | **`+0x4`** |

### Other Changes

```diff

-106.0.2.0.0
+114.0.0.0.0

-  Functions: 821
-  Symbols:   1564
-  CStrings:  530
+  Functions: 843
+  Symbols:   1609
+  CStrings:  547
Symbols:
+ +[ULConnection(Diagnostic) npdrUpdateWithDeltaX:deltaY:deltaZ:quaternionX:quaternionY:quaternionZ:quaternionW:northAlignmentAngle:timestamp:reply:]
+ -[ULLabel initWithName:timestamp:contextLayer:deviceClass:coordinate:probabilityVector:imageIdentifiersVector:metadata:]
+ -[ULLabel metadata]
+ -[ULLabel setMetadata:]
+ -[ULLabel(Metadata) addMetadata:]
+ GCC_except_table119
+ GCC_except_table121
+ GCC_except_table145
+ _OBJC_CLASS_$_ULPlatform
+ _OBJC_IVAR_$_ULLabel._metadata
+ _ULLabelMetadataIsValid
+ _ULLabelMetadataKeyDisplayName
+ _ULLabelMetadataKeyIRMediaType
+ _ULLabelMetadataKeyIdentifier
+ _ULLabelMetadataKeyIsGroup
+ _ULLabelMetadataOptionalSchemasByContextLayer.map
+ _ULLabelMetadataOptionalSchemasByContextLayer.once
+ _ULLabelMetadataRequiredSchemasByContextLayer
+ _ULLabelMetadataRequiredSchemasByContextLayer.map
+ _ULLabelMetadataRequiredSchemasByContextLayer.once
+ _ULLabelMetadataSanitize
+ _ULLabelMetadataSchemaForContextLayer
+ _ULLabelMetadataValueIsNonEmpty
+ __OBJC_$_CATEGORY_NSNumber_$_ULLabelMetadata
+ __OBJC_$_CATEGORY_NSString_$_ULLabelMetadata
+ __OBJC_$_CLASS_PROP_LIST_NSNumber_$_ULLabelMetadata
+ __OBJC_$_CLASS_PROP_LIST_NSString_$_ULLabelMetadata
+ __OBJC_$_INSTANCE_METHODS_ULLabel(Testing|Metadata)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS__ULNPDRFrameDataProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES__ULNPDRFrameDataProtocol
+ __OBJC_$_PROTOCOL_REFS_ULLabelMetadataValue
+ __OBJC_$_PROTOCOL_REFS__ULNPDRFrameDataProtocol
+ __OBJC_CATEGORY_PROTOCOLS_$_NSNumber_$_ULLabelMetadata
+ __OBJC_CATEGORY_PROTOCOLS_$_NSString_$_ULLabelMetadata
+ __OBJC_LABEL_PROTOCOL_$_ULLabelMetadataValue
+ __OBJC_LABEL_PROTOCOL_$__ULNPDRFrameDataProtocol
+ __OBJC_PROTOCOL_$_ULLabelMetadataValue
+ __OBJC_PROTOCOL_$__ULNPDRFrameDataProtocol
+ __OBJC_PROTOCOL_REFERENCE_$__ULNPDRFrameDataProtocol
+ ___147+[ULConnection(Diagnostic) npdrUpdateWithDeltaX:deltaY:deltaZ:quaternionX:quaternionY:quaternionZ:quaternionW:northAlignmentAngle:timestamp:reply:]_block_invoke
+ ___147+[ULConnection(Diagnostic) npdrUpdateWithDeltaX:deltaY:deltaZ:quaternionX:quaternionY:quaternionZ:quaternionW:northAlignmentAngle:timestamp:reply:]_block_invoke_2
+ ___ULLabelMetadataOptionalSchemasByContextLayer_block_invoke
+ ___ULLabelMetadataRequiredSchemasByContextLayer_block_invoke
+ ___block_descriptor_40_e5_v8?0l
+ ___block_descriptor_40_e8_32bs_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e5_v8?0ls40l8s32l8
+ _npdrUpdateWithDeltaX:deltaY:deltaZ:quaternionX:quaternionY:quaternionZ:quaternionW:northAlignmentAngle:timestamp:reply:.onceToken
+ _npdrUpdateWithDeltaX:deltaY:deltaZ:quaternionX:quaternionY:quaternionZ:quaternionW:northAlignmentAngle:timestamp:reply:.queue
+ _npdrUpdateWithDeltaX:deltaY:deltaZ:quaternionX:quaternionY:quaternionZ:quaternionW:northAlignmentAngle:timestamp:reply:.sharedConnection
- GCC_except_table112
- GCC_except_table114
- GCC_except_table138
- __OBJC_$_INSTANCE_METHODS_ULLabel(Testing)
CStrings:
+ "  metadata: %@\n"
+ "00000000-0000-0000-0000-000000000029"
+ "00000000-0000-0000-0000-000000000030"
+ "ULLabel: invalid metadata dropped (count=%{public}lu, layer=%{public}@)"
+ "ULLabelMetadataKeyDisplayName"
+ "ULLabelMetadataKeyIRMediaType"
+ "ULLabelMetadataKeyIdentifier"
+ "ULLabelMetadataKeyIsGroup"
+ "_checkAndRecoverIfNeeded called with self.connection == nil"
+ "com.apple.MicroLocation.npdrUpdate"
+ "com.apple.PowerUIAgent"
+ "com.apple.ospredictiond"
+ "metadata"
+ "npdrUpdate: XPC connection error: domain=%@ code=%ld msg=%@"
+ "npdrUpdate: XPC reply error: domain=%@ code=%ld msg=%@"
+ "npdrUpdate: shared XPC connection interrupted — frames may be dropped until milod is reachable"
+ "npdrUpdate: shared XPC connection invalidated"
```

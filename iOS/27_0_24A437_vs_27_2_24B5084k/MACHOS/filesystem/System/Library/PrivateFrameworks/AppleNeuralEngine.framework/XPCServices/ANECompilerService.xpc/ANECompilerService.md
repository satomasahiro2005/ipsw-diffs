## ANECompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANECompilerService.xpc/ANECompilerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1920` | `0x1940` | **`+0x20`** |
| `__TEXT.__cstring` | `0x12e6` | `0x1303` | **`+0x1d`** |
| `__TEXT.__objc_methname` | `0x25f1` | `0x25fa` | **`+0x9`** |
| `__DATA.__data` | `0x400` | `0x408` | **`+0x8`** |
| `__TEXT.__text` | `0x19a28` | `0x19a2c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-382.15.1.0.0
+382.100.2.0.0

-  Symbols:   965
-  CStrings:  879
+  Symbols:   966
+  CStrings:  880
Symbols:
+ _kANEFModelMutableClusterIndexKey
+ _objc_msgSend$cloneIfWritable:isEncryptedModel:cloneDirectory:useClone:
- _objc_msgSend$cloneIfWritable:isEncryptedModel:cloneDirectory:
Functions:
~ ___161-[_ANECompilerService compileModelAt:csIdentity:sandboxExtension:options:tempDirectory:cloneDirectory:outputURL:aotModelBinaryPath:maxModelMemorySize:withReply:]_block_invoke : 7496 -> 7500
CStrings:
+ "ANEFModelMutableClusterIndex"
+ "cloneIfWritable:isEncryptedModel:cloneDirectory:useClone:"
- "cloneIfWritable:isEncryptedModel:cloneDirectory:"
```

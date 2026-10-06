## VideoStabilizationV2

> `/System/Library/VideoProcessors/VideoStabilizationV2.bundle/VideoStabilizationV2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x589cc` | `0x59308` | **`+0x93c`** |
| `__TEXT.__objc_methname` | `0x5a6d` | `0x5bb7` | **`+0x14a`** |
| `__TEXT.__oslogstring` | `0xef79` | `0xf0c3` | **`+0x14a`** |
| `__TEXT.__cstring` | `0x964a` | `0x9725` | **`+0xdb`** |
| `__DATA.__objc_const` | `0x4448` | `0x4508` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x1b94` | `0x1c04` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x3260` | `0x32c0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x850` | `0x8a8` | **`+0x58`** |
| `__DATA.__objc_selrefs` | `0xfc8` | `0xff0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xd50` | `0xd60` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4a4` | `0x4b0` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x6b8` | `0x6c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 1414
-  Symbols:   2218
-  CStrings:  2756
+  Functions: 1424
+  Symbols:   2231
+  CStrings:  2774
Symbols:
+ -[VISConfigurationV2 embeddedMotionPreprocessingEnabled]
+ -[VISConfigurationV2 motionPreprocessingOptions]
+ -[VISConfigurationV2 setEmbeddedMotionPreprocessingEnabled:]
+ -[VISConfigurationV2 setMotionPreprocessingOptions:]
+ -[VISWrapper _maProcessorOutputReady:status:]
+ OBJC_IVAR_$_VISConfigurationV2._embeddedMotionPreprocessingEnabled
+ OBJC_IVAR_$_VISConfigurationV2._motionPreprocessingOptions
+ OBJC_IVAR_$_VISWrapper._maSBPRef
+ _FigSampleBufferProcessorCreateForMotionAttachments
+ _objc_msgSend$_maProcessorOutputReady:status:
+ _objc_msgSend$embeddedMotionPreprocessingEnabled
+ _objc_msgSend$motionPreprocessingOptions
+ _visw_maProcessorOutputReadyCallback
CStrings:
+ "-[VISWrapper _maProcessorOutputReady:status:]"
+ "<<<< GyroVideoStabilizationV2 >>>> %s: Unable to create embedded motion attachments sample buffer processor"
+ "<<<< GyroVideoStabilizationV2 >>>> %s: Unable to set embedded motion attachments output callback"
+ "<<<< GyroVideoStabilizationV2 >>>> %s: motionPreprocessingOptions must be set when embeddedMotionPreprocessingEnabled is YES"
+ "Embedded motion attachments processor failed"
+ "T@\"NSDictionary\",&,N,V_motionPreprocessingOptions"
+ "TB,N,V_embeddedMotionPreprocessingEnabled"
+ "Unable to flush embedded motion attachments processor"
+ "Unable to submit frame to embedded motion attachments processor"
+ "_embeddedMotionPreprocessingEnabled"
+ "_maProcessorOutputReady:status:"
+ "_maSBPRef"
+ "_motionPreprocessingOptions"
+ "embeddedMotionPreprocessingEnabled"
+ "motionPreprocessingOptions"
+ "setEmbeddedMotionPreprocessingEnabled:"
+ "setMotionPreprocessingOptions:"
+ "\x91"
```

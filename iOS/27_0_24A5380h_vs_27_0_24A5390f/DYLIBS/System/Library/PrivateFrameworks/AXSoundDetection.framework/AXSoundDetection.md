## AXSoundDetection

> `/System/Library/PrivateFrameworks/AXSoundDetection.framework/AXSoundDetection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7780` | `0x7964` | **`+0x1e4`** |
| `__AUTH_CONST.__cfstring` | `0x1780` | `0x17e0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x1060` | `0x10ad` | **`+0x4d`** |
| `__AUTH_CONST.__objc_const` | `0x7f0` | `0x818` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x870` | `0x898` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x828` | `0x850` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x663` | `0x689` | **`+0x26`** |
| `__TEXT.__unwind_info` | `0x298` | `0x2a8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x210` | `0x218` | **`+0x8`** |

### Other Changes

```diff

-534.0.0.0.0
+536.0.0.0.0

-  Functions: 194
-  Symbols:   475
-  CStrings:  232
+  Functions: 198
+  Symbols:   481
+  CStrings:  236
Symbols:
+ +[AXSDSettings kShotCustomPipeFixedPath]
+ -[AXSDSettings customPipedInFile]
+ -[AXSDSettings pipeCustomFile:]
+ -[AXSDSettings setCustomPipedInFile:]
+ __OBJC_$_CLASS_PROP_LIST_AXSDSettings
+ _kAXSSoundDetectionKShotCustomPipedInFile
CStrings:
+ "%@#%@"
+ "/var/tmp/AXKShotCustomPipe.wav"
+ "AXSSoundDetectionKShotCustomPipedInFile"
+ "Ringing custom pipe file for %@ -> %@"
```

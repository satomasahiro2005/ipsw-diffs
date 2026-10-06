## NanoUniverse

> `/System/Library/PrivateFrameworks/NanoUniverse.framework/NanoUniverse`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x414d0` | `0x415c0` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0xdbe` | `0xe0e` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1b4e` | `0x1b5e` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd70` | `0xd68` | **`-0x8`** |

### Other Changes

```diff

-39.0.0.0.0
+40.0.0.0.0

-  Functions: 1461
+  Functions: 1462

-  CStrings:  379
+  CStrings:  380
Symbols:
+ -[NUNIClassicRenderer _createPipelineForProgramType:fromLibrary:archive:]
+ -[NUNIGlobetrotterRenderer _createPipelineForProgramType:fromLibrary:archive:]
- -[NUNIClassicRenderer _createPipelineForProgramType:fromLibrary:]
- -[NUNIGlobetrotterRenderer _createPipelineForProgramType:fromLibrary:]
CStrings:
+ "-[NUNIClassicRenderer _createPipelineForProgramType:fromLibrary:archive:]"
+ "-[NUNIGlobetrotterRenderer _createPipelineForProgramType:fromLibrary:archive:]"
+ "CalliopeResourceManager: Metal compilation failure Shader=%@ Device=%@"
- "-[NUNIClassicRenderer _createPipelineForProgramType:fromLibrary:]"
- "-[NUNIGlobetrotterRenderer _createPipelineForProgramType:fromLibrary:]"
```

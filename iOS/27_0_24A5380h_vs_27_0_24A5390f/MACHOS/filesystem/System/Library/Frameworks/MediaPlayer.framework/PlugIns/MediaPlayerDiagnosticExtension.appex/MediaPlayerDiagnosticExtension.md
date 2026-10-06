## MediaPlayerDiagnosticExtension

> `/System/Library/Frameworks/MediaPlayer.framework/PlugIns/MediaPlayerDiagnosticExtension.appex/MediaPlayerDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf98` | `0x10e8` | **`+0x150`** |
| `__DATA_CONST.__cfstring` | `0x480` | `0x4e0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x391` | `0x3f1` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x480` | `0x4e0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x1f4` | `0x230` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x130` | `0x148` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x68` | `0x74` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-4026.100.76.0.0
+4026.100.79.0.0

-  Functions: 8
-  Symbols:   51
-  CStrings:  81
+  Functions: 9
+  Symbols:   52
+  CStrings:  87
Symbols:
+ _OBJC_CLASS_$_NSFileManager
Functions:
~ sub_100000b70 : 228 -> 272
+ sub_100001280
CStrings:
+ "MUSICD_APP_GROUP"
+ "MusicDaemonAppGroup"
+ "containerURLForSecurityApplicationGroupIdentifier:"
+ "defaultManager"
+ "group.com.apple.musicd"
+ "musicDaemonAppGroupAttachment"
```

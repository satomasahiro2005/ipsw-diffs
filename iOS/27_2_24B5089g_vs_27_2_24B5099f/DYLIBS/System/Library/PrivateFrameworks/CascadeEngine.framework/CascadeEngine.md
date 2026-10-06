## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/CascadeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x658b0` | `0x65b8c` | **`+0x2dc`** |
| `__TEXT.__oslogstring` | `0x6cff` | `0x6d4f` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2a8f` | `0x2abf` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x17e0` | `0x1808` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x6f4` | `0x6d0` | **`-0x24`** |
| `__TEXT.__objc_methlist` | `0x1f2c` | `0x1f44` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a70` | `0x1a80` | **`+0x10`** |
| `__TEXT.__const` | `0x1250` | `0x1240` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x15a8` | `0x15b8` | **`+0x10`** |

### Other Changes

```diff

-256.0.1.0.0
+258.0.0.0.0

-  Functions: 2315
-  Symbols:   2086
-  CStrings:  833
+  Functions: 2317
+  Symbols:   2088
+  CStrings:  836
Symbols:
+ -[CCRapportManager _isFileTransferSessionPossibleWithPeer:error:]
+ -[CCRapportManager _peerHasIPLink:]
+ -[CCRapportManager _statusFlagsUnionForPeer:matchedDeviceCount:]
- -[CCRapportManager _isFileTransferSessionPossible:]
CStrings:
+ " no"
+ "%@ active device statusFlags: 0x%llx"
+ "%@ has%s IP link (%lu active device(s))"
+ "No transport available for a Rapport FileTransferSession"
- "WiFi is off"
```

## SoundAnalysis

> `/System/Library/Frameworks/SoundAnalysis.framework/SoundAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x341c90` | `0x34298c` | **`+0xcfc`** |
| `__TEXT.__cstring` | `0xea05` | `0xece5` | **`+0x2e0`** |
| `__AUTH_CONST.__const` | `0x2d158` | `0x2d1d0` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0x27610` | `0x27668` | **`+0x58`** |
| `__TEXT.__const` | `0x40550` | `0x40510` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x19f33` | `0x19f6b` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x5980` | `0x59b0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x13b58` | `0x13b78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf60` | `0xf70` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x8d88` | `0x8d78` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x84d2` | `0x84e2` | **`+0x10`** |
| `__DATA.__common` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xdb8` | `0xdbc` | **`+0x4`** |

### Other Changes

```diff

-500.185.0.0.0
+500.195.0.0.0

-  Functions: 28103
-  Symbols:   923
-  CStrings:  1591
+  Functions: 28123
+  Symbols:   924
+  CStrings:  1604
Symbols:
+ _RPOptionStatusFlags
CStrings:
+ " accessoryIdentifier="
+ " localDestination="
+ "Copying files: server="
+ "Copying home sound recognition audio capture detectorIdentifier="
+ "Deleting files: server="
+ "Discovering server: homeKitIdentifier="
+ "Listing files: server="
+ "[PUB] file server discovery "
+ "com.apple.SNFileSharing.FileSharingVersion"
+ "com.apple.SNFileSharing.FileTransferComplete"
+ "com.apple.SNFileSharing.FileTransferDeleteFile"
+ "com.apple.SNFileSharing.FileTransferListFiles"
+ "com.apple.SNFileSharing.FileTransferRequest"
+ "copyFiles(server:path:filenames:localDestination:deleteOnCopy:)"
+ "copyHomeSoundRecognitionAudioCapture(detectorIdentifier:timestamp:accessoryIdentifier:localDestination:deleteOnCopy:)"
+ "deleteFiles(server:path:filenames:)"
+ "discoverServer(homeKitIdentifier:timeoutSeconds:)"
+ "listFiles(server:path:)"
- "FileSharingVersion"
- "FileTransferComplete"
- "FileTransferDeleteFile"
- "FileTransferListFiles"
- "FileTransferRequest"
```

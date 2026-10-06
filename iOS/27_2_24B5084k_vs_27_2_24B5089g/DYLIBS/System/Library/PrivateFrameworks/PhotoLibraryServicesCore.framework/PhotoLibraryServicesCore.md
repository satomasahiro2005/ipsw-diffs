## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/PhotoLibraryServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x370` | `0xa0` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x24e0` | `0x27b0` | **`+0x2d0`** |
| `__TEXT.__text` | `0xccdc0` | `0xcce40` | **`+0x80`** |
| `__DATA.__bss` | `0xdc0` | `0xe28` | **`+0x68`** |
| `__DATA_DIRTY.__bss` | `0x408` | `0x3a0` | **`-0x68`** |
| `__TEXT.__oslogstring` | `0xb38c` | `0xb37a` | **`-0x12`** |

### Other Changes

```diff

-916.40.110.0.0
+916.45.110.0.0
Functions:
~ -[PLFileBackedLogger _inlock_createLoggerRecordWithLogFileURL:logRotate:didRebuildLogArchive:error:] : 640 -> 736
~ -[PLFileBackedLogger close] : 584 -> 616
CStrings:
+ "PLFileBackedLogger: Failed to open log file at %@. Error: %@"
+ "PLFileBackedLogger: close url backed logger: %@"
+ "PLFileBackedLogger: open url backed logger: %@"
+ "PLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %@"
- "PLFileBackedLogger: Failed to open log file. Error: %@"
- "PLFileBackedLogger: close url backed logger: %{public}@"
- "PLFileBackedLogger: open url backed logger: %{public}@"
- "PLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %{public}@"
```

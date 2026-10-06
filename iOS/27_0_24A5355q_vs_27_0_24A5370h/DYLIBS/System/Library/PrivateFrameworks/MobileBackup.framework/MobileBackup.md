## MobileBackup

> `/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e54c` | `0x2e0dc` | **`-0x470`** |
| `__AUTH_CONST.__cfstring` | `0x5880` | `0x5700` | **`-0x180`** |
| `__TEXT.__cstring` | `0x7afb` | `0x7a46` | **`-0xb5`** |
| `__AUTH_CONST.__objc_const` | `0x5268` | `0x5288` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2290` | `0x2270` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x3e74` | `0x3e84` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3b0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x10b0` | `0x10a8` | **`-0x8`** |

### Other Changes

```diff

-3033.0.0.0.0
+3036.0.0.0.0

-  CStrings:  1151
+  CStrings:  1139
Symbols:
+ -[MBBehaviorOptions backupPathsToFailSQLiteCompactionRegex]
+ -[MBBehaviorOptions simulateQuotaExceededError]
- +[MBError errorForHTTPURLResponse:error:]
- _OBJC_CLASS_$_NSHTTPURLResponse
CStrings:
+ "BackupPathsToFailSQLiteCompactionRegex"
+ "SimulateQuotaExceeded"
- "Account Moved"
- "Client error: %ld %@"
- "Conflict"
- "Failed Dependency"
- "HTTP connection error"
- "Insufficient Storage"
- "Locked"
- "No response or error"
- "Not Found"
- "Retry-After"
- "Server error: %ld %@"
- "Service Unavailable"
- "Unauthorized"
- "Unexpected HTTP status code: %ld"
```

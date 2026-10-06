## JetCore

> `/System/Library/PrivateFrameworks/JetCore.framework/JetCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2686ec` | `0x26827c` | **`-0x470`** |
| `__TEXT.__cstring` | `0xa5c1` | `0xa551` | **`-0x70`** |
| `__AUTH_CONST.__const` | `0x1a7a0` | `0x1a7d0` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x151c0` | `0x151e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x9a90` | `0x9aa8` | **`+0x18`** |
| `__DATA.__data` | `0x64d0` | `0x64e0` | **`+0x10`** |

### Other Changes

```diff

-10.0.43.0.0
+10.0.47.0.0

-  Functions: 12807
+  Functions: 12809

-  CStrings:  976
+  CStrings:  974
CStrings:
+ "com.apple.jetpackassetd.Metrics"
- "Could not determine the FileProtectionType"
- "Database file does not exist yet"
- "FileProtectionType for the database file is: "
```

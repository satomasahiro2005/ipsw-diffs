## SetupAssistantSupport

> `/System/Library/PrivateFrameworks/SetupAssistantSupport.framework/SetupAssistantSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16554` | `0x165d0` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0xabe` | `0xaf4` | **`+0x36`** |
| `__AUTH_CONST.__cfstring` | `0x15a0` | `0x1580` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1135` | `0x111e` | **`-0x17`** |
| `__DATA_CONST.__objc_selrefs` | `0x11f8` | `0x1200` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x360` | `0x368` | **`+0x8`** |

### Other Changes

```diff

-567.101.0.0.0
+568.1.3.0.0

+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration

-  Functions: 622
-  Symbols:   1288
+  Functions: 623
+  Symbols:   1289
Symbols:
+ _SCDynamicStoreCopyComputerName
Functions:
~ -[SASProximityInformation loadInformation] : 4944 -> 5016
+ -[SASProximityInformation loadInformation].cold.4
CStrings:
+ "Failed to check if backup is supported on cellular: %{public}@"
+ "Failed to determine if initial mega backup completed: %@{public}"
+ "Failed to get date of last backup: %@"
- "Failed to check if backup is supported on cellular: %@"
- "Failed to determine if initial mega backup completed: %@"
- "UserAssignedDeviceName"
```

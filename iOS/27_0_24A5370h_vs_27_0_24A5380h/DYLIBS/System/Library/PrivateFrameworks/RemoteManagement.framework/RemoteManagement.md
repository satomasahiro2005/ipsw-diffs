## RemoteManagement

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/RemoteManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `0x828` | `0xab8` | **`+0x290`** |
| `__AUTH.__objc_data` | `0x568` | `0x7f0` | **`+0x288`** |
| `__DATA_DIRTY.__data` | `0x290` | `0x8` | **`-0x288`** |
| `__DATA_DIRTY.__objc_data` | `0x670` | `0x3e8` | **`-0x288`** |
| `__TEXT.__text` | `0x4bd30` | `0x4bc50` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x49ab` | `0x492b` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0x15a4` | `0x15d8` | **`+0x34`** |
| `__AUTH_CONST.__cfstring` | `0x1ac0` | `0x1ae0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2337` | `0x2357` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xb50` | `0xb68` | **`+0x18`** |
| `__DATA.__bss` | `0x23d0` | `0x23c0` | **`-0x10`** |
| `__TEXT.__const` | `0x17fc` | `0x180c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf50` | `0xf60` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x590` | `0x598` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x9a0` | `0x9a8` | **`+0x8`** |

### Other Changes

```diff

-624.0.3.0.0
+624.0.8.0.0

-  Symbols:   1617
+  Symbols:   1620
Symbols:
+ +[RMErrorUtilities createMissingStatusValueErrorWithKeyPath:]
+ _RMSwitchToDaemonUserIfNeeded
+ _RMSwitchToMobileUserIfNeeded
+ _geteuid
+ _getpwnam
+ _setuid
- +[RMLocations _applicationSupportChildDirectoryURLInDomain:createIfNeeded:childName:descriptor:]
- ___96+[RMLocations _applicationSupportChildDirectoryURLInDomain:createIfNeeded:childName:descriptor:]_block_invoke
- __applicationSupportChildDirectoryURLInDomain:createIfNeeded:childName:descriptor:.onceToken
CStrings:
+ "Darwin User directory is %{public}@"
+ "Error.MissingStatusValue_%@"
+ "mobile"
- "Failed to find Application Support directory: %{public}@"
- "Failed to find Data Vault directory: %{public}@"
- "Unable to create Data Vault at %{public}@: %{public}@"
```

## com.apple.driver.AppleSEPCredentialManager

> `com.apple.driver.AppleSEPCredentialManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4f9b0` | `0x4fc8c` | **`+0x2dc`** |
| `__DATA.__data` | `0x3061` | `0x3229` | **`+0x1c8`** |
| `__TEXT.__cstring` | `0x13802` | `0x138b5` | **`+0xb3`** |
| `__TEXT_EXEC.__auth_stubs` | `0x660` | `0x670` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x330` | `0x338` | **`+0x8`** |

### Other Changes

```diff

-949.0.17.0.0
-  Functions: 1021
+949.40.7.0.0
+  Functions: 1022

-  CStrings:  2009
+  CStrings:  2014
CStrings:
+ "%s: %s: giving up waiting for SEP endpoint after %llums (cmd=%u).\n"
+ "121112222222221"
+ "23:10:33"
+ "DataValidation_DeviceInfo"
+ "Sep  4 2026"
+ "_milestoneReachedThreadCall"
+ "_milestoneReachedThreadCallHandler"
+ "ioService"
+ "newValue && newValueSize == sizeof(ACMDeviceInfo)"
- "1211122222222212"
- "21:32:40"
- "Aug 13 2026"
- "_milestoneReachedAction.actionTimer"
```

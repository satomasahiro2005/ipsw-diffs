## com.apple.driver.AppleMobileFileIntegrity

> `com.apple.driver.AppleMobileFileIntegrity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x29ab0` | `0x29df8` | **`+0x348`** |
| `__TEXT.__cstring` | `0xb796` | `0xb8fb` | **`+0x165`** |
| `__TEXT_EXEC.__auth_stubs` | `0x10d0` | `0x10c0` | **`-0x10`** |
| `__DATA.__data` | `0x4fa` | `0x4f2` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x868` | `0x860` | **`-0x8`** |

### Other Changes

```diff

-1171.0.3.0.0
-  Functions: 916
+1171.0.12.0.0
+  Functions: 917

-  CStrings:  1162
+  CStrings:  1169
CStrings:
+ "%s: Hash type is SHA1"
+ "21:45:38"
+ "AMFI: Platform binary with platform identifier not in trust cache\n"
+ "AMFI: bailing out because of restricted entitlements.\n"
+ "Aug  5 2026"
+ "Code has restricted entitlements, but the validation of its code signature failed.\nUnsatisfied Entitlements: %s"
+ "com.apple.amfi.developer_mode_state"
+ "developer_app_executions"
+ "developer_mode_state"
+ "lockdown_mode_state"
+ "platform binary with platform identifier not in trust cache\n"
- "%s: Hash type is not SHA256 (%u) but %u."
- "21:12:38"
- "Jul 14 2026"
- "com.apple.backboardd"
```

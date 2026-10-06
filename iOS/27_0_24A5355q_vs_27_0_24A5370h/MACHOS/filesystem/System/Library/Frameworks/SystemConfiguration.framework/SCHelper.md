## SCHelper

> `/System/Library/Frameworks/SystemConfiguration.framework/SCHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b78` | `0x4bc4` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0x497` | `0x4d7` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x3a0` | `0x380` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x720` | `0x740` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x390` | `0x3a0` | **`+0x10`** |
| `__TEXT.__const` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3ba` | `0x3b6` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1434.0.0.502.1
+1438.0.0.0.0

-  Symbols:   132
-  CStrings:  101
+  Symbols:   134
+  CStrings:  100
Symbols:
+ _CFDataGetLength
+ _audit_token_to_pid
Functions:
~ sub_100000ac8 : 1656 -> 1688
~ sub_1000014f4 -> sub_100001514 : 316 -> 312
~ sub_100001ca0 -> sub_100001cbc : 808 -> 800
~ sub_100002dec -> sub_100002e00 : 504 -> 532
~ sub_100003318 -> sub_100003348 : 588 -> 612
~ sub_100003840 -> sub_100003888 : 1800 -> 1812
~ sub_100004920 -> sub_100004974 : 784 -> 780
~ sub_100004c30 -> sub_100004c80 : 764 -> 760
CStrings:
+ "  %p {port = %p, pid = %d, path = %{private}s%s}"
+ "%p : open, pid=%d"
+ "SCPreferences access to \"%{private}@\" denied, no [read] entitlement for pid=%d"
+ "SCPreferences access to \"%{private}@\" denied, no [write] entitlement for pid=%d"
+ "SecTaskCopyValueForEntitlement(,\"%@\",) failed, error = %@ : pid=%d"
+ "SecTaskCreateWithAuditToken() failed: pid=%d"
+ "data not valid, length = %ld"
+ "hasAuthorization() session pid=%d: entitlement=%@: not valid"
+ "interface \"%{private}@\" not refreshed: %s"
+ "prefsID (%{private}@) not valid"
- "  %p {port = %p, caller = %@, path = %s%s}"
- "%p : open, prefs = %@"
- "???"
- "SCPreferences access to \"%@\" denied, no [read] entitlement for \"%@\""
- "SCPreferences access to \"%@\" denied, no [write] entitlement for \"%@\""
- "SecTaskCopyValueForEntitlement(,\"%@\",) failed, error = %@ : %@"
- "SecTaskCreateWithAuditToken() failed: %@"
- "data not valid, %@"
- "hasAuthorization() session=%@: entitlement=%@: not valid"
- "interface \"%@\" not refreshed: %s"
- "prefsID (%@) not valid"
```

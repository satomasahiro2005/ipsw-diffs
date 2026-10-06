## UserNotificationsServer

> `/System/Library/PrivateFrameworks/UserNotificationsServer.framework/UserNotificationsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bac8` | `0x3ba0c` | **`-0xbc`** |
| `__AUTH_CONST.__cfstring` | `0xe00` | `0xdc0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x1626` | `0x1616` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x687a` | `0x686a` | **`-0x10`** |

### Other Changes

```diff

-703.0.0.0.0
+708.0.0.0.0

-  CStrings:  526
+  CStrings:  524
CStrings:
+ "[%{public}@] Foreground app will not request ephemeral notifications"
+ "[%{public}@] defaultSectionInfo changed [ isRestricted %{BOOL}d -> %{BOOL}d, allowTimeSensitive %{BOOL}d -> %{BOOL}d, allowMessages %{BOOL}d -> %{BOOL}d, allowCriticalAlerts %{BOOL}d -> %{BOOL}d]"
- "NO"
- "YES"
- "[%{public}@] Foreground app will not request ephemeral notifications isAppClip: %{public}@ wantsEphemeral notifications: %{public}@"
- "[%{public}@] defaultSectionInfo changed [ isRestricted %{BOOL}d -> %{BOOL}d, allowTimeSensitive %{BOOL}d -> %{BOOL}d, allowMessages %{BOOL}d -> %{BOOL}d]"
```

## AnalyticsAgentFramework

> `/System/Library/PrivateFrameworks/AnalyticsAgentFramework.framework/AnalyticsAgentFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b520` | `0x1b200` | **`-0x320`** |
| `__AUTH_CONST.__const` | `0x748` | `0x6f8` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x124b` | `0x127b` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x154` | `0x140` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x788` | `0x798` | **`+0x10`** |
| `__TEXT.__const` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xa50` | `0xa5c` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x788` | `0x780` | **`-0x8`** |

### Other Changes

```diff

-559.0.0.502.1
+562.0.0.0.0

-  Functions: 329
-  Symbols:   368
-  CStrings:  101
+  Functions: 325
+  Symbols:   370
+  CStrings:  102
Symbols:
+ _AnalyticsIsEventUsed
+ _AnalyticsSendEventSync
CStrings:
+ "Event not enabled. { eventName=%s }"
+ "Failed to send event %{public}s, skipping %{public}s duration=%u collectedDate=%{public}s"
- "Event %{public}s not enabled, skipping %{public}s duration=%u collectedDate=%{public}s"
```

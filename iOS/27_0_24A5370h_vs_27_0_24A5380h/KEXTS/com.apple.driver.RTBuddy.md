## com.apple.driver.RTBuddy

> `com.apple.driver.RTBuddy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x449a4` | `0x44efc` | **`+0x558`** |
| `__DATA_CONST.__const` | `0xbce8` | `0xbe38` | **`+0x150`** |
| `__TEXT.__cstring` | `0x9a4b` | `0x9a9b` | **`+0x50`** |
| `__TEXT.__os_log` | `0xba9` | `0xbf1` | **`+0x48`** |
| `__DATA_CONST.__kalloc_type` | `0x1340` | `0x1380` | **`+0x40`** |
| `__DATA.__common` | `0xb70` | `0xb98` | **`+0x28`** |

### Other Changes

```diff

-778.0.2.0.0
-  Functions: 2408
+778.0.6.0.0
+  Functions: 2426

-  CStrings:  1127
+  CStrings:  1130
CStrings:
+ "21:00:05"
+ "Image[%zu] %s slide=0x%016llx\n"
+ "Jun 30 2026"
+ "RTBuddySymbolsDecoder"
+ "site.RTBuddySymbolsDecoder"
- "19:40:36"
- "Jun 18 2026"
```

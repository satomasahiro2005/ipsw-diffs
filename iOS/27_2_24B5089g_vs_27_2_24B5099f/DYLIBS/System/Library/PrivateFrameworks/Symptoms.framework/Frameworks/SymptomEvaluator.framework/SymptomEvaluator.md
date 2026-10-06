## SymptomEvaluator

> `/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomEvaluator.framework/SymptomEvaluator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1268` | `0xf98` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x4538` | `0x4808` | **`+0x2d0`** |
| `__TEXT.__text` | `0x2a4538` | `0x2a4790` | **`+0x258`** |
| `__TEXT.__oslogstring` | `0x47fc5` | `0x480a5` | **`+0xe0`** |
| `__DATA.__bss` | `0xf08` | `0xeb0` | **`-0x58`** |
| `__DATA_DIRTY.__bss` | `0x1800` | `0x1850` | **`+0x50`** |
| `__TEXT.__cstring` | `0x27c00` | `0x27c30` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x1f0` | `0x200` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x17c8` | `0x17d0` | **`+0x8`** |
| `__DATA.__common` | `0xa8` | `0xa0` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x1a8` | `0x1b0` | **`+0x8`** |

### Other Changes

```diff

-2394.40.15.0.0
+2394.40.16.0.0

-  Symbols:   20121
-  CStrings:  12269
+  Symbols:   20122
+  CStrings:  12273
Symbols:
+ _csops_audittoken
CStrings:
+ "Managed event caller (pid %d) authorized: %{public}s entitlement"
+ "Managed event caller (pid %d) authorized: platform binary"
+ "Managed event request from caller (pid %d) denied: not a platform binary and missing entitlement %{public}s"
+ "com.apple.symptoms.symptomsd.managed_events.read"
```

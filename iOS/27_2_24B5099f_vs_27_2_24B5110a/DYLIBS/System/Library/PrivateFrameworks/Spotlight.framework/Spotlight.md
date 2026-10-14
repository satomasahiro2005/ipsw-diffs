## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3cf8` | `0xa39d4` | **`-0x324`** |
| `__TEXT.__oslogstring` | `0x58f2` | `0x57d2` | **`-0x120`** |
| `__AUTH_CONST.__objc_intobj` | `0x270` | `0x240` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x30c0` | `0x30a0` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x5850` | `0x5834` | **`-0x1c`** |
| `__TEXT.__cstring` | `0x36dc` | `0x36cc` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1950` | `0x1948` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x30b0` | `0x30a8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1898` | `0x18a0` | **`+0x8`** |

### Other Changes

```diff

-2465.1.7.0.0
+2465.1.9.0.0

-  Functions: 1813
-  Symbols:   3341
-  CStrings:  950
+  Functions: 1812
+  Symbols:   3338
+  CStrings:  945
Symbols:
+ +[SPKGenerativeSearchMailQueryBase appScopeBundleIdentifiers]
+ +[SPKGenerativeSearchSiriTranscriptQuery appScopeBundleIdentifiers]
- -[SPSearchQueryContext(GenerativeSearch) appScopeBundleIdentifier]
- -[SPSearchQueryContext(GenerativeSearch) appScopeEntity]
- -[SPSearchQueryContext(GenerativeSearch) isAppScopedSearch]
- GCC_except_table18
- _OBJC_CLASS_$_SPSearchAppEntity
CStrings:
+ "(global)"
+ "[qid=%lu][SPKGenerativeSearchMailQuery] Enabled: scope=%{public}@"
- "(nil)"
- "(null)"
- "[qid=%lu][GenerativeSearch][AppScope] Bundle ID: %{public}@"
- "[qid=%lu][GenerativeSearch][AppScope] Detected app-scoped search"
- "[qid=%lu][SPKGenerativeSearchMailQuery] Disabled: app-scoped to %{public}@"
- "[qid=%lu][SPKGenerativeSearchMailQuery] Enabled for Mail app-scoped search"
- "[qid=%lu][SPKGenerativeSearchMailQuery] Enabled: using GenerativeSearch for mail"
```

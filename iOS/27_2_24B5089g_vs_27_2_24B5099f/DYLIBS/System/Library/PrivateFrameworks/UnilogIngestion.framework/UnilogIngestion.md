## UnilogIngestion

> `/System/Library/PrivateFrameworks/UnilogIngestion.framework/UnilogIngestion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x340` | `0x620` | **`+0x2e0`** |
| `__AUTH.__data` | `0x3f8` | `0x210` | **`-0x1e8`** |
| `__TEXT.__text` | `0x250c8` | `0x25204` | **`+0x13c`** |
| `__DATA.__data` | `0x870` | `0x780` | **`-0xf0`** |
| `__AUTH.__objc_data` | `0xf0` | `0x50` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__DATA.__bss` | `0x980` | `0x900` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `—` | `0x80` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1a1` | `0x201` | **`+0x60`** |
| `__DATA.__common` | `0x80` | `0x60` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `—` | `0x20` | **`+0x20`** |

### Other Changes

```diff

-2.9.0.0.0
+3.3.0.0.0

-  Functions: 700
+  Functions: 699

-  CStrings:  42
+  CStrings:  45
CStrings:
+ "Ingestion.Topics"
+ "Ingestion.Utility"
+ "Ingestion.Workflow"
+ "com.apple.unilog.processing"
- "com.apple.unilog.ingestion"
```

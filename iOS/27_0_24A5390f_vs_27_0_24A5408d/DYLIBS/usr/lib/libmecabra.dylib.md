## libmecabra.dylib

> `/usr/lib/libmecabra.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26b520` | `0x26c760` | **`+0x1240`** |
| `__TEXT.__gcc_except_tab` | `0x1a790` | `0x1a82c` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x16aab` | `0x16b15` | **`+0x6a`** |
| `__DATA.__bss` | `0x1c40` | `0x1c90` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x4a0e` | `0x4a59` | **`+0x4b`** |
| `__AUTH_CONST.__const` | `0x435f0` | `0x43620` | **`+0x30`** |
| `__TEXT.__const` | `0x3001c` | `0x3004c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xce60` | `0xce90` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x16860` | `0x16840` | **`-0x20`** |
| `__TEXT.__ustring` | `0x32ae` | `0x32cc` | **`+0x1e`** |
| `__DATA.__common` | `0xa28` | `0xa30` | **`+0x8`** |

### Other Changes

```diff

-1154.0.0.0.0
+1159.0.0.0.0

-  Functions: 11145
+  Functions: 11150

-  CStrings:  4423
+  CStrings:  4429
CStrings:
+ "%s: File size: %zu bytes"
+ "Blocklist is empty."
+ "Blocklist is truncated."
+ "Failed to reload blocklist."
+ "Malformed length in Blocklist."
+ "Malformed offset in Blocklist."
+ "[E5Runner] Path %zu: surface='%s', originalCost=%f, e5RunnerProb=%f, geometryCost=%f, syllableMatchPenalty=%f, adaptationBoost=%f, readingMismatchPenalty=%f, dynamicWordReward=%f, finalScore=%f"
- "[E5Runner] Path %zu: surface='%s', originalCost=%f, e5RunnerProb=%f, geometryCost=%f, syllableMatchPenalty=%f, adaptationBoost=%f, readingMismatchPenalty=%f, finalScore=%f"
```

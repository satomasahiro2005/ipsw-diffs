## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe96d4` | `0xe9840` | **`+0x16c`** |
| `__TEXT.__oslogstring` | `0x8bc8` | `0x8caf` | **`+0xe7`** |
| `__DATA.__bss` | `0x1709` | `0x16a9` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0x1198` | `0x11f8` | **`+0x60`** |
| `__AUTH_CONST.__objc_dictobj` | `0xfd48` | `0xfd70` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x6d100` | `0x6d120` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x45ef8` | `0x45f18` | **`+0x20`** |
| `__TEXT.__cstring` | `0x43920` | `0x43939` | **`+0x19`** |
| `__TEXT.__const` | `0x1c30` | `0x1c38` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3138` | `0x3140` | **`+0x8`** |

### Other Changes

```diff

-3486.40.92.0.0
+3486.40.98.0.0

-  Functions: 4966
+  Functions: 4969

-  CStrings:  15295
+  CStrings:  15299
CStrings:
+ "IBLMNotificationDecision"
+ "Ignoring requested owner of unexpected class %{public}@"
+ "Not applying requested ownership: move to submission destination failed: %{public}@"
+ "NotificationDecision"
+ "Refusing submission request: destination path is missing or of unexpected class %{public}@"
- "Error moving file %@"
```

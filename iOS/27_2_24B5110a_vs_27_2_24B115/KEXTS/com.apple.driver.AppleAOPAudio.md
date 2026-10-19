## com.apple.driver.AppleAOPAudio

> `com.apple.driver.AppleAOPAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x630` | `0x650` | **`+0x20`** |
| `__TEXT_EXEC.__text` | `0x2f9c0` | `0x2f9d4` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x318` | `0x328` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ __ZN23AppleAOPAudioController5startEP9IOService : 476 -> 496
CStrings:
+ "20:57:12"
+ "20:57:14"
+ "Oct 13 2026"
- "01:01:43"
- "01:01:54"
- "Oct 10 2026"
```

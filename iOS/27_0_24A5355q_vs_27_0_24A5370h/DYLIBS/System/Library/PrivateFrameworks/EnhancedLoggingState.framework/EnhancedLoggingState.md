## EnhancedLoggingState

> `/System/Library/PrivateFrameworks/EnhancedLoggingState.framework/EnhancedLoggingState`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8ec8` | `0x8e98` | **`-0x30`** |

### Other Changes

```text
Functions:
~ -[ELSSnapshot totalDuration] : 288 -> 284
~ -[ELSSnapshot needsFollowup] : 324 -> 320
~ -[ELSSnapshot encodedQueue] : 544 -> 540
~ -[ELSSnapshot decodeQueue:] : 680 -> 676
~ -[ELSSnapshot dictionaryRepresentationPretty:] : 2176 -> 2156
~ +[ELSWhitelist findEntryForParameterName:] : 340 -> 336
~ +[ELSWhitelist findEntryForBundleIdentifier:] : 340 -> 336
~ +[ELSWhitelist findEntryForDEDIdentifier:] : 344 -> 340
```

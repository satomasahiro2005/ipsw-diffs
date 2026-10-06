## OSIntelligence

> `/System/Library/PrivateFrameworks/OSIntelligence.framework/OSIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19648` | `0x1a5e8` | **`+0xfa0`** |
| `__TEXT.__oslogstring` | `0x1ec2` | `0x2609` | **`+0x747`** |
| `__TEXT.__gcc_except_tab` | `0x680` | `0x6a8` | **`+0x28`** |
| `__TEXT.__const` | `0x198` | `0x1a8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1200` | `0x1208` | **`+0x8`** |

### Other Changes

```diff

-279.0.0.0.0
+282.0.0.0.0

-  Functions: 919
+  Functions: 921

-  CStrings:  408
+  CStrings:  438
Symbols:
+ _OBJC_CLASS_$_NSNull
+ ___block_descriptor_72_e8_32s40r48r56r64r_e22_v16?0"BMStoreEvent"8lr40l8r48l8r56l8s32l8r64l8
- ___58-[_OSIBLMAnalyticsHandler historicalPluggedInDataForDate:]_block_invoke_2
- ___block_descriptor_72_e8_32s40r48r56r64r_e22_v16?0"BMStoreEvent"8lr40l8r48l8r56l8r64l8s32l8
CStrings:
+ "Charging segment extends to end of day: %@ to %@, duration %.1f mins"
+ "Daily charging summary: %ld segments, %.1f total minutes"
+ "Device was charging before midnight, starting new segment at %@"
+ "Duplicate mitigation disable event (level=%ld), already disengaged (ignoring)"
+ "Duplicate mitigation enable event (level=%ld), keeping original start time %@ (already engaged for %.1f mins)"
+ "Duplicate plug-in event while already charging (collapsing to same segment)"
+ "Duplicate unplug event while already unplugged (ignoring)"
+ "Ended charging segment: %@ to %@, duration %.1f mins (total: %.1f mins)"
+ "Engagement span: start=%@, end=%@, total=%.1f mins"
+ "Engagement started before yesterday (%@), clamping to %@"
+ "Mitigation disengaged, cleared engagement tracking (total engagement was %.1f mins)"
+ "Mitigation engaged, started engagement tracking at %@ (level=%ld)"
+ "Negative segment duration detected at end of day: %f seconds"
+ "Negative segment duration detected: %f seconds"
+ "Negative today duration detected: %f minutes (start=%@, now=%@)"
+ "Negative yesterday duration detected: %f minutes (start=%@, midnight=%@)"
+ "No existing engagement data, created new dictionary"
+ "Persisted engagement data for %lu day(s)"
+ "Processing engagement END (engaged→disengaged)"
+ "Recorded today: added %.1f mins (total now %ld mins), count now %ld"
+ "Recorded yesterday: added %.1f mins (total now %ld mins), count now %ld"
+ "Split calculation: includeYesterday=%d, effectiveStart=%@, midnightToday=%@"
+ "Started charging segment #%ld at %@"
+ "State evaluation: isCurrentlyEngaged=%d (since %@), newStateIsEngaged=%d"
+ "Today (%@) existing data: duration=%ld mins, count=%ld"
+ "Today (%@) had no data, initializing"
+ "Yesterday (%@) existing data: duration=%ld mins, count=%ld"
+ "Yesterday (%@) had no data, initializing"
+ "recordMitigationUpdate called: previous level=%ld, new level=%ld, decisionMaker=%ld"
+ "recordMitigationUpdate completed"
```

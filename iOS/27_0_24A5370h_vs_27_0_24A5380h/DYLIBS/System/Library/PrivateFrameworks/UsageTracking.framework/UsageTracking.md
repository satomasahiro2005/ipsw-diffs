## UsageTracking

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTracking`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29a90` | `0x2a118` | **`+0x688`** |
| `__TEXT.__oslogstring` | `0x1268` | `0x1487` | **`+0x21f`** |
| `__AUTH.__objc_data` | `0x50` | `0xf0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x730` | `0x690` | **`-0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x2930` | `0x2960` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xec8` | `0xef0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x784` | `0x7a8` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `0x1704` | `0x171c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1420` | `0x1430` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x318` | `0x320` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a8` | `0x1ac` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-403.0.0.0.0
+405.0.0.0.0

-  Functions: 614
-  Symbols:   1183
-  CStrings:  225
+  Functions: 623
+  Symbols:   1189
+  CStrings:  230
Symbols:
+ -[USUsageAccumulator _accumulateIntelligenceUsage:timestamp:]
+ -[USUsageAccumulator intelligenceUsageStartDates]
+ GCC_except_table30
+ GCC_except_table65
+ _OBJC_CLASS_$_BMIntelligenceUsage
+ _OBJC_IVAR_$_USUsageAccumulator._intelligenceUsageStartDates
+ ___block_descriptor_64_e8_32s40s48s56r_e42_v32?0"USTrustIdentifier"8"NSDate"16^B24ls32l8s40l8s48l8r56l8
- GCC_except_table61
CStrings:
+ "Ignoring intelligence usage start event for %{public}@ at %{public}@ because it already started at %{public}@"
+ "Intelligence usage for %{public}@ start date: %{public}@ is later than end date: %{public}@"
+ "Received intelligence usage end event at %{public}@ for %{public}@ that is earlier than its start date: %{public}@"
+ "Received intelligence usage end event for %{private}@ without a corresponding start event. This may be because the event was manually ended due to a backlight end event."
+ "Received malformed intelligence usage event: %{public}@"
```

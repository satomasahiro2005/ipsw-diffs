## WidgetKit

> `/System/Library/Frameworks/WidgetKit.framework/WidgetKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x215eb8` | `0x20f8ac` | **`-0x660c`** |
| `__TEXT.__oslogstring` | `0x3306` | `0x36b6` | **`+0x3b0`** |
| `__AUTH.__data` | `0x5ed0` | `0x5f58` | **`+0x88`** |
| `__TEXT.__const` | `0x21ad0` | `0x21b40` | **`+0x70`** |
| `__DATA.__data` | `0x6448` | `0x6488` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x62d0` | `0x6310` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xc1fc` | `0xc22c` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x74e0` | `0x7508` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x8f48` | `0x8f60` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0xe65c` | `0xe64c` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x578f` | `0x579f` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xcc76` | `0xcc86` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa28` | `0xa2c` | **`+0x4`** |

### Other Changes

```diff

-749.2.13.0.0
+749.2.13.200.0

-  Functions: 12658
-  Symbols:   4316
-  CStrings:  758
+  Functions: 12662
+  Symbols:   4318
+  CStrings:  767
Symbols:
+ _symbolic _____ 9WidgetKit0A14ViewCollectionC16ScrubbedTimeline33_6515E7F69E8BF24DFC04681C26643EFFLLV
+ _symbolic _____Sg 9WidgetKit0A18ArchivableMetadataV05EntryD0V
CStrings:
+ "All %{public}ld timeline entries for %{public}@ have a non-finite date; keeping only the first, dated now."
+ "Archive for %{public}@ has a non-finite creation date; treating it as the distant past."
+ "Archive for %{public}@ has a non-finite reload date; reloading one day after the archive was created."
+ "Archive for %{public}@ has entries out of order; first: %{public}s, last: %{public}s; entry count: %{public}ld"
+ "Archive for %{public}@ has no finite entry dates; entry count: %{public}ld"
+ "Dropped %{public}ld of %{public}ld timeline entries with a non-finite date for %{public}@"
+ "Reload policy for %{public}@ has a non-finite date; reloading one day after the timeline was created."
+ "Reload policy for %{public}@ is at end but every timeline entry has a non-finite date; reloading one day after the timeline was created."
+ "Timeline for %{public}@ has entries out of order; entry count: %{public}ld"
```

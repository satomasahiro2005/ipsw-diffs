## PosterUIFoundation

> `/System/Library/PrivateFrameworks/PosterUIFoundation.framework/PosterUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93e84` | `0x94324` | **`+0x4a0`** |
| `__AUTH.__objc_data` | `0x24b0` | `0x2410` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xd20` | `0xdc0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x3901` | `0x3961` | **`+0x60`** |
| `__TEXT.__cstring` | `0x6663` | `0x66a3` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xab5c` | `0xab8c` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x58c0` | `0x58e8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1078` | `0x1098` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x26d8` | `0x26f8` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0xd98` | `0xdb0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xf88` | `0xf98` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1680` | `0x1674` | **`-0xc`** |
| `__TEXT.__unwind_info` | `0x29e8` | `0x29f0` | **`+0x8`** |

### Other Changes

```diff

-344.0.101.0.0
+347.102.0.0.0

-  Functions: 4134
-  Symbols:   7394
-  CStrings:  1491
+  Functions: 4142
+  Symbols:   7403
+  CStrings:  1493
Symbols:
+ -[PUIPosterLevelSet copyByFilteringLevels:]
+ -[PUIPosterSnapshotter consecutiveStartupFailuresForTesting]
+ -[PUIPosterSnapshotter setConsecutiveStartupFailuresForTesting:]
+ -[PUIStylePickerHomeScreenItemView _compositingFilterNameForCurrentStyle]
+ __UIClamp
+ __UILerp
+ __UIMap
+ __UIUnlerp
+ ___52+[PUICodableImage dataRepresentationForImage:error:]_block_invoke
+ ___block_descriptor_40_e9_16?0^8l
+ _kCAFilterClearIconBlendMode
+ _kCAFilterScreenBlendMode
- ___68-[PUIPosterSnapshotBundlePredicate(SQLiteAdditions) SQLitePredicate]_block_invoke_6
- ___68-[PUIPosterSnapshotBundlePredicate(SQLiteAdditions) SQLitePredicate]_block_invoke_7
- ___68-[PUIPosterSnapshotBundlePredicate(SQLiteAdditions) SQLitePredicate]_block_invoke_8
CStrings:
+ "(%{public}@) Booted extension process is invalid (no error) — treating as a startup failure"
+ "(%{public}@) Exceeded %lu consecutive mid-snapshot interruptions, giving up"
+ "-[PUIPosterSnapshotter setConsecutiveStartupFailuresForTesting:]"
- "(%{public}@) Booted extension process is invalid but there was no error!"
```

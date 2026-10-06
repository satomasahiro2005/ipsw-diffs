## FindMyCore

> `/System/Library/PrivateFrameworks/FindMyCore.framework/FindMyCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a1c8` | `0x10c1c4` | **`+0x1ffc`** |
| `__TEXT.__eh_frame` | `0x7310` | `0x74e4` | **`+0x1d4`** |
| `__AUTH_CONST.__const` | `0x8c15` | `0x8ccd` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x1141` | `0x11e1` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x49b8` | `0x4a38` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3c68` | `0x3cc8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x580` | `0x5c8` | **`+0x48`** |
| `__DATA.__data` | `0x3dd0` | `0x3e10` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x27c6` | `0x27f6` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x250` | `0x270` | **`+0x20`** |
| `__TEXT.__const` | `0x1163c` | `0x1165c` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x49d1` | `0x49f1` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1a80` | `0x1a68` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x3724` | `0x373c` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x504` | `0x4f8` | **`-0xc`** |
| `__DATA_CONST.__got` | `0xaa8` | `0xaa0` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2ec` | `0x2f0` | **`+0x4`** |

### Other Changes

```diff

-470.31.6.16.30
+470.31.6.16.39

-  Functions: 6163
-  Symbols:   2219
-  CStrings:  480
+  Functions: 6186
+  Symbols:   2218
+  CStrings:  484
Symbols:
+ _symbolic So22SPLocationFetchContextC
+ _symbolic _____SgIeAgHr_ 10FindMyCore17PublishedLocationV
- _swift_asyncLet_begin
- _swift_asyncLet_finish
- _swift_asyncLet_get
CStrings:
+ "ENUM_ITEM_LOCATABLECAPABILITY_REPRESENTATION_SERVERREACHABLE_TITLE"
+ "Failed to reverse geocode, keeping location without an address: %{public}@"
+ "Failed to shift: %{public}@."
+ "FindItemIntent: subscribeAndFetchLocation exceeded its 12s budget, falling back to cache: %@"
+ "serverReachable"
- "Failed to shift/revgeo: %{public}@."
```

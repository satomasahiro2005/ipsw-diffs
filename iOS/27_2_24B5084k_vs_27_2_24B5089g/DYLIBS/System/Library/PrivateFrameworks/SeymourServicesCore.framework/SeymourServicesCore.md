## SeymourServicesCore

> `/System/Library/PrivateFrameworks/SeymourServicesCore.framework/SeymourServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e388` | `0x5f538` | **`+0x11b0`** |
| `__TEXT.__eh_frame` | `0x3b30` | `0x3c58` | **`+0x128`** |
| `__DATA_DIRTY.__data` | `0x1438` | `0x14e8` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x205d` | `0x210d` | **`+0xb0`** |
| `__DATA.__data` | `0xa60` | `0x9b8` | **`-0xa8`** |
| `__DATA.__bss` | `0x52a0` | `0x5220` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0xa80` | `0xb00` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x140` | `0x190` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x18f8` | `0x1930` | **`+0x38`** |
| `__TEXT.__cstring` | `0xc33` | `0xc53` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xbb3` | `0xbd3` | **`+0x20`** |
| `__TEXT.__const` | `0x4c28` | `0x4c40` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x11d4` | `0x11ec` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xf30` | `0xf38` | **`+0x8`** |
| `__AUTH_CONST.__const` | `0x3780` | `0x3788` | **`+0x8`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x198` | `0x1a0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1b8c` | `0x1b92` | **`+0x6`** |
| `__TEXT.__swift_as_entry` | `0x170` | `0x174` | **`+0x4`** |

### Other Changes

```diff

-2027.1.50.0.1
+2027.1.54.0.0

-  Functions: 1986
+  Functions: 1995

-  CStrings:  197
+  CStrings:  200
Symbols:
+ ___swift_memcpy121_8
+ _symbolic yyYbc
- ___swift_memcpy104_8
- _malloc_zone_pressure_relief
CStrings:
+ "%{public}s grace-compaction phys_footprint beforeDrop=%{public}s afterHandlers=%{public}s afterRelief=%{public}s dropReclaimedBytes=%{public}s reliefReclaimedBytes=%{public}s"
+ "%{public}s grace-compaction settled phys_footprint beforeDrop=%{public}s settled=%{public}s settledReclaimedBytes=%{public}s"
+ "Compaction %{public}s superseded, skipping pressure relief"
+ "[footprint-measurement]"
- "[footprint-measurement] grace-compaction phys_footprint beforeDrop=%{public}s afterHandlers=%{public}s afterRelief=%{public}s dropReclaimedBytes=%{public}s reliefReclaimedBytes=%{public}s"
```

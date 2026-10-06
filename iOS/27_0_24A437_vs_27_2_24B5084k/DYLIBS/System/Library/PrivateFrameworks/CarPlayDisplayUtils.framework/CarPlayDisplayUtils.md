## CarPlayDisplayUtils

> `/System/Library/PrivateFrameworks/CarPlayDisplayUtils.framework/CarPlayDisplayUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15e38` | `0x16de4` | **`+0xfac`** |
| `__TEXT.__oslogstring` | `0xa26` | `0xb76` | **`+0x150`** |
| `__TEXT.__eh_frame` | `0x368` | `0x2b0` | **`-0xb8`** |
| `__TEXT.__swift5_typeref` | `0x2f2` | `0x2c2` | **`-0x30`** |
| `__TEXT.__const` | `0x10e0` | `0x10b8` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x470` | `0x448` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x4b8` | `0x4dc` | **`+0x24`** |
| `__TEXT.__cstring` | `0x2ea` | `0x2ca` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x550` | `0x56e` | **`+0x1e`** |
| `__DATA.__data` | `0x1b0` | `0x1a0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x448` | `0x450` | **`+0x8`** |

### Other Changes

```diff

-799.3.0.0.0
+807.2.0.0.0

-  Functions: 511
-  Symbols:   224
-  CStrings:  57
+  Functions: 513
+  Symbols:   223
+  CStrings:  55
Symbols:
+ ___swift_memcpy6_1
+ _objc_retain_x21
+ _objc_retain_x25
+ _swift_release_x25
+ _swift_retain_x24
- ___swift_memcpy5_1
- _objc_retain_x26
- _objc_retain_x28
- _swift_release_x26
- _symbolic SS3key______5valuet 19CarPlayDisplayUtils14AppearanceInfoO
- _symbolic _____ySS3key______5valuetG s23_ContiguousArrayStorageC 19CarPlayDisplayUtils14AppearanceInfoO
CStrings:
+ " suports=perDispNight"
+ "Initial %{public}s: %{public}s setting:%{public}s"
+ "Initial display night mode: %{bool,public}d"
+ "Invalid initial %{public}s mode %{public}ld"
+ "Invalid initial %{public}s setting %{public}ld"
+ "No initial %{public}s: mode=%{bool,public}d setting=%{bool,public}d"
+ "No per-display night mode, using system: %{bool,public}d"
+ "Seeding DDP appearance for %{public}s: %{public}s"
+ "[Appearance-Params] primary=%{bool,public}d displayNightMode=%{bool,public}d locationNightMode=%{bool,public}d uiAppearance=%{bool,public}d mapAppearance=%{bool,public}d uiAppearanceMode=%{public}s uiAppearanceSetting=%{public}s mapAppearanceMode=%{public}s mapAppearanceSetting=%{public}s preference=%{public}s"
- "AppearanceInfo: airPlay("
- "AppearanceInfo: ddp("
- "Initial %s: %s setting:%s"
- "Initial display night mode: %{bool}d"
- "Invalid initial %s mode %ld"
- "Invalid initial %s setting %ld"
- "No initial %s: mode=%{bool}d setting=%{bool}d"
- "No per-display night mode, using system: %{bool}d"
- "Screen does not support appearance mode"
- "Screen does not support map appearance mode"
- "Seeding DDP appearance for %{public}s: %s"
```
